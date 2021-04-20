---
title: Advert API
author: Gary Paluk
---

![A Plugin.IO branded banner that shows a young woman in front of a vivid blue background.](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.jpg)

<br />

### ⬅️ [Go back to Getting Started](./getting-started.md)

<br />

# ✳️ Advert API

<Image alt="This feature is in beta" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/beta-icon.png" height="30px" />

**WARNING:** Plugin.IO Ads are currently running in **beta mode** and will only display placeholder adverts. Ads will **NOT**
generate revenue during this time.

<br />

**Plugin.IO Ads** help publishers and advertisers to reach their business goals. Use **Plugin.IO Ads** to 
generate revenue from your apps and games. All ads are subject to our platform **[content guidelines](./content-guidelines)**.

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

<Image alt="This feature is in beta" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/beta-icon.png" height="30px" />

A Banner advert may be displayed at the top or bottom of the screen by specifying either `BannerPosition.TOP` or `BannerPosition.BOTTOM`. When no value is provided, the banner will be 
displayed at the top of the screen.

If no banner adverts are available when `showBanner` is called, the request will be ignored.

<br />

## Example

```typescript
await api.advert.showBanner(BannerPosition.Bottom, (e: MessageEvent) => {
    console.log("Data: ", e.data);
});
```

### Parameters

|name       |type                                |required|
|:----------|:-----------------------------------|:-------|
|position   |`enum BannerPosition`               |optional|
|callback   |`function(e: MessageEvent): void`   |optional|

<br />

### Success response
```json
{
    "data": {
        "id": "b5072db4-07e1-4885-bd06-311e19a5b09e",
        "timestamp": ""
    }
}
```

### Error response

```json
{
    "data": null,
    "errors": [{
        "code": "403",
        "message": "Ads are disabled for this application."
    }]
}
```

**Note:** If an error occurs during a banner advert request, no information is displayed to the user.


<br />

<a name="image"></a>

# 🎯 Image advert
<Image alt="This feature is in beta" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/beta-icon.png" height="30px" />

An Image advert displays a fullscreen advert which contains an image element. Image adverts can be skipped after 5 seconds.

If no banner adverts are available when `showImage` is called, the request will be ignored.

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

<Image alt="This feature is in beta" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/beta-icon.png" height="30px" />


```typescript
api.advert.showCarousel();
```

<br />

<a name="video"></a>

# 🎯 Video advert

<Image alt="This feature is in beta" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/beta-icon.png" height="30px" />

```typescript
api.advert.showVideo();
```

<br />

<a name="rewarded-video"></a>

# 🎯 Rewarded video advert

<Image alt="This feature is in beta" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/beta-icon.png" height="30px" />


```typescript
api.advert.showVideoReward("advert-reward-id");
```

<br />
<br />

---
Built with ❤️ by Team [Plugin.IO](https://github.com/orgs/pluginio/teams/plugin-io-team/members) 🚀

<Image style="float:right" alt="Plugin.IO logo" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/logo.png" height="75px" width="75px" />
