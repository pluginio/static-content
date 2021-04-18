---
title: Advert API
author: Gary Paluk
---

![A Plugin.IO branded banner that shows a young woman in front of a vivid blue background.](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.jpg)

<br />

### ⬅️ [Go back to Getting Started](./getting-started.md)

<br />

# ✳️ Advert API

<b>Plugin.IO Ads</b> help publishers and advertisers to reach their business goals. Use <b>Plugin.IO Ads</b> to 
generate revenue from your apps and games. All ads are subject to our platform <b>[content guidelines](./content-guidelines)</b>.

<br />

# 🗒 Contents

* [Banner advert](#banner)
* [Image advert](#image)
* [Carousel advert](#carousel)
* [Video advert](#video)
* [Rewarded video advert](#rewarded-video)

<br />

<a name="banner"></a>
# 🎯 Banner advert 

<!-- ![alt](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/api_advert_banner.gif) -->
A Banner advert may be displayed at the top or bottom of the screen. You may provide either of the position 
properties; `BannerPosition.TOP` or `BannerPosition.BOTTOM`. When no value is provided, a banner will be 
displayed at the top of the screen.

If there are no adverts are available when `showBanner` is called, no advert be displayed.

<br />

## Example

```typescript
api.advert.showBanner(BannerPosition.Bottom);
```

### Parameters
<br />

> <b>position</b> - optional

<br />

### Errors

If an error occurs during a banner advert request, no information is displayed to the end user.

<br />

<a name="image"></a>
# 🎯 Image advert

An Image advert displays a fullscreen advert which contains an image element.

If there are no adverts are available when `showImage` is called, no advert will be displayed.


<br />

```typescript
api.advert.showImage();
```

### Parameters
<br />

> There are no fields associated with this API request.

<br />

### Errors

If an error occurs during an image advert request, no information is displayed to the end user.

<br />

<a name="carousel"></a>
# 🎯 Carousel advert

```typescript
api.advert.showCarosel(): void
```

<br />

<a name="video"></a>
# 🎯 Video advert

```typescript
api.advert.showVideo(): void
```

<br />

<a name="rewarded-video"></a>
# 🎯 Rewarded video advert

```typescript
api.advert.showVideoReward(id: string): void
```
