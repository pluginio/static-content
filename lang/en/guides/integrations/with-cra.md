---
title: With CRA / Integration / Plugin.IO
description: Plugin.IO - Integration Guide
keywords: cra, guide, integration, web3, social network, nft, plugin.io, pluginio, NEKO, token, cryptocurrency, crypto
author: Gary Paluk
og_type: article
og_title: Integration Guide / Plugin.IO
og_author: Gary Paluk
og_description: Plugin.IO - Integration Guide
og_url: https://plugin.io/guides/integrations/with-cra
og_image: https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.png
og_image_alt: A cartoon image of fairground. A hot air balloon floats by through an open blue sky
twitter_card: summary_large_image
---

![A Plugin.IO branded banner that shows a young woman in front of a vivid blue background.](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.png)

<br />

### ⬅️ [Go back to Getting Started](./getting-started.md)

# ✳️ With CRA

<br />

```typescript
await api.advert.showBanner(BannerPosition.Bottom, (e: MessageEvent) => {
    console.log("Data: ", e.data);
});
```

<br />

---
Built with ❤️ by Team [Plugin.IO](https://github.com/orgs/pluginio/teams/plugin-io-team/members) 🚀

<Image style="float:right" alt="Plugin.IO logo" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/logo.png" height="75px" width="75px" />
