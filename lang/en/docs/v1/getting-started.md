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
```
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

If you are using [React](https://github.com/facebook/react) you can add the `PluginProvider` at the root of your application.

```jsx
import React from 'react';
import { render } from 'react-dom';
import { PluginProvider } from "@pluginio/sdk-react";

function App() {
  return (
    <div>
      <h2>My first Plugin.IO App 🚀</h2>
    </div>
  )
}

render (
  <PluginProvider>
    <App />
  </PluginProvider>
  document.getElementById('root');
);
```

Once your `PluginProvider` is hooked up, you're ready to start calling API services with `usePlugin()`

```jsx
import React, { useEffect } from 'react';
import { EventType, usePlugin } from "@pluginio/sdk-react";

const MyComponent = () => {
  const { api, addEventListener, config } = usePlugin();

  useEffect(() => {
    addEventListener(EventType.CAMERA_RESPONSE, (e: MessageEvent) => {
      console.log(EventType.CAMERA_RESPONSE, e.data);
    });
  }

  const startCamera = () => api.camera.start();

  return (
    <button onClick={startCamera}>
      Take a picture! 📸
    </button>
  )
}
```

<br />

> For **create-react-app**, you need to set this up in **index.js** or **index.tsx**

<br />

<a name="examples"></a>

# ✳️ Examples

<br />

We have created some examples to help you get started building Plugin.IO applications. These examples are MIT licenced and as such, you can do anything that you like with them. Have fun learning whilst adding new and exciting features.

**Note:** Please make significant changes if you plan on adding your App to the Plugin.IO [App Store](https://plugin.io/apps/).

<br />

### 📻 Loop - Online radio

<br />

<p float="left">
<Image alt="Loop App displaying light mode" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/loop_light.png" height="400px" /> <Image alt="Loop App displaying dark mode" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/loop_dark.png" height="400px" />
</p>

### Features:

* React TypeScript
* Chakra UI
* Functional programming style
* Uses `PluginProvider` context
* Light and dark modes

<br />

Clone this App using: 

```
npx degit pluginio/create-app/examples/loop your-project-name
```

View the source code on [GitHub](https://github.com/pluginio/create-app/examples/loop) 🔗

Try it live on [Plugin.IO](https://plugin.io/apps/?id=com.orkoa.loop) 🔗

<br />

<a name="contributing"></a>

# ✳️ Contributing

## [Code of conduct](./conduct.md)

Plugin.IO has adopted a Code of Conduct as outlined by [Contributor Covinent v2.0](./conduct.md). Please read the [full text](./conduct.md) so that you can understand what actions will and will not be considered acceptable.

<br />

## [Contribution guidelines](./contribution-guidelines.md)

Read our [contribution guidelines](./contribution-guidelines.md) to learn about our development processes, how to propose bugfixes and improvements, and how to build and test your changes to Plugin.IO.

<br />
<br />

---
Built with ❤️ by Team [Plugin.IO](https://github.com/orgs/pluginio/teams/plugin-io-team/members) 🚀

<div style="text-align:right;">
<Image alt="Plugin.IO logo" src="https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/logo.png" height="75px" width="75px" />
</div>
