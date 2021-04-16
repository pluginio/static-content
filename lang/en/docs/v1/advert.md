---
title: Advert
author: Gary Paluk
---

# Advert

<b>Plugin.IO Ads</b> helps publishers and advertisers to reach their business goals. Use <b>Plugin.IO Ads</b> to drive revenue from your apps and games.

<br />

## Contents

* [Banner](#banner)
* [Image](#image)
* [Video](#banner)
* [Rewarded Video](#banner)

<br />

<a name="banner"></a>
# Banner advert

A banner advert

<!-- ![alt](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/api_advert_banner.gif) -->

### Example
```
api.advert.showBanner(BannerPosition.Bottom);
```

### Parameters
<br />

><b>position</b> - optional

<br />

A banner advert may be displayed at the top or bottom of the screen. You may provide either of the position 
properties; `BannerPosition.TOP` or `BannerPosition.BOTTOM`. If no value is provided, the banner will be 
displayed at the top.

<b>Important:</b> If the is no advert available when this method is called, an ad can <b>not</b> be displayed.

<br />
<br />

### Errors

If an error occurs
<br />
<br />

# Image advert

<!-- ![alt](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/api_advert_banner.gif) -->

```
api.advert.showImage();
```

### Fields

> There are no fields associated with this API request.

<br />
<br />


### Response
| Name              | Description                | Type                                                                |
| :-----------------|:----------------------|:--------------------------------------------------------------------------|
| English           | English               | [link](https://github.com/pluginio/static-content/tree/main/lang/en)      |


## Example response
```
{
    "data": {
        "showBanner": {
            "id": "8beb26d0-9e3d-11eb-a8b3-0242ac130003"
        }
    }
}
```

## Error response

```
{
    "data": null,
    "errors": [
        {
            "message": "Banner could not be shown at this time."
        }
    ]
}
```

A banner advert as displayed by this particular image...

##### Show an image advert

```
api.advert.showImage() :void
```

##### Show a video advert

```
api.advert.showVideo(): void
```

##### Show a rewarded video advert

```
api.advert.showVideoReward(id: string): void
```
