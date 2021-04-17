---
title: Getting started
author: Gary Paluk
---

![A Plugin.IO branded banner that shows a young woman in front of a vivid blue background.](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.jpg)

<br />

# Plugin.IO SDK

The Plugin.IO SDK allows developers to easily add [Plugin.IO](https://plugin.io) features to their web applications. These features include; log in, monetization, social sharing and micro data storage as well as marketplace and NFT features etc.

Our focus at Plugin.IO is to provide great user experiences with simplicity, and most SDK features are available using a single API call.

<br/>

# 📖 Contents

* [Getting Started](#getting-started) ⚓ 
* [Advert API](./advert.md)
* [Analytics API](./analytics.md)
* [Camera API](./camera.md)
* [Console API](./console.md)
* [Data API](./data.md)
* [Purchase API](./purchase.md)
* [Share API](./share.md)
* [User API](./user.md)

<br />

<a name="getting-started"></a>
# 🚀 Getting started

* [Installation](#installation) ⚓
* [Application templates](#application-templates) ⚓
* [React provider](#react-provider) ⚓
* [Examples](#examples)  ⚓
* [Contributing](#contributing)  ⚓

<br />

<a name="installation"></a>
# ✳️ Installation

You can the use the Plugin.IO SDK from a CDN. (Coming soon)

or as an `npm` package.

Inside your project directory, install the Plugin.IO SDK by running either of the following commands:

```
npm i @pluginio/sdk
```

<br />

```
yarn add @pluginio/sdk
```

<br />

<a name="application-templates"></a>
# ✳️ Application templates

You can quickly create a new Plugin.IO application by using the [create-app](https://github.com/pluginio/create-app) monorepo templates. Use the excellent [Degit](https://github.com/Rich-Harris/degit) library to clone the relevant project structure.

<br />

JavaScript
```javascript
npx degit pluginio/create-app/javascript your-project-name
```

<br />

TypeScript
```
npx degit pluginio/create-app/typescript your-project-name
```

<br />

React
```
npx degit pluginio/create-app/react your-project-name
```

<br />

React hooks
```
npx degit pluginio/create-app/react-hooks your-project-name
```

<br />

> For **create-react-app** installation instructions, check this [CRA templates guide](guides/integrations/with-cra).

<br />

<a name="react-provider"></a>
# ✳️ React Provider

If you are using [React](https://github.com/facebook/react) you can add the **PluginProvider** at the root of your application.

```typescript
function App() {
  return (
    <PluginProvider>
      <App />
    </PluginProvider>
  )
}
```

<br />

> For **create-react-app**, you need to set this up in **index.js** or **index.tsx**

<br />

<a name="examples"></a>
# ✳️ Examples

* Coming soon...

<br />


<a name="contributing"></a>
# ✳️ Contributing

<br />

## [Code of conduct](./conduct.md)

Plugin.IO has adopted a Code of Conduct as outlined by [Contributor Covinent v2.0](./conduct.md). Please read the [full text](./conduct.md) so that you can understand what actions will and will not be considered acceptable.

<br />

## [Contribution guidelines](./contribution-guidelines.md)

Read our [contribution guidelines](./contribution-guidelines.md) to learn about our development processes, how to propose bugfixes and improvements, and how to build and test your changes to Plugin.IO.