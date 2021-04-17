---
title: Getting started
author: Gary Paluk
---

![A Plugin.IO branded banner that shows a young woman in front of a vivid blue background.](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.jpg)


<br />

# About

The Plugin.IO SDK provides a collection of APIs that enable developers to easily add Plugin.IO features to their web applications. This include; log in, monetization, social sharing and micro data storage as well as marketplace and NFT features.

Our focus at Plugin.IO is to provide great user experience and simplicity. Most features can be invoked with a single API call.

<br/>

# 🗒 Contents

* [Getting Started](#getting-started)
* [Advert API](./advert.md)
* [Analytics API](./analytics.md)
* [Camera API](#./camera.md)
* [Console API](#./console.md)
* [Data API](#./data.md)
* [Purchase API](#./purchase.md)
* [Share API](#./share.md)
* [User API](#./user.md)

<br />

<a name="getting-started"></a>
# ✳️ Getting started

* [Installation](#installation)
* [Helper templates](#helper-templates.md)
* [React provider](#react-provider.md)

<br />

<a name="installation"></a>
## Installation

<br />

Inside your project directory, install the Plugin.IO SDK by running either of the following:

```typescript
npm i @pluginio/sdk
```

<br />

```typescript
yarn add @pluginio/sdk
```

<br />

<a name="helper-templates"></a>
# ✳️ Helper templates

We have created project templates to help you quickly and easily set up your new Plugin.IO Web App.

<br />

## JavaScript
```javascript
npx degit pluginio/sdk-starter/javascript my-project-name
```

<br />

## TypeScript
```
npx degit pluginio/sdk-starter/typescript my-project-name
```

<br />

## React
```
npx degit pluginio/sdk-starter/react my-project-name
```

<br />

## React hooks
```
npx degit pluginio/sdk-starter/react-hooks my-project-name
```

<br />
<br />

> For **create-react-app** installation instructions, check this [CRA templates guide](guides/integrations/with-cra).

<br />

<a name="react-provider"></a>
# ✳️ React Provider

If you are using React, you can add the **PluginProvider** at the root of your application.

Go to the root of your project and do this:

```typescript
function App() {
  return (
    <PluginProvider>
      <App />
    </PluginProvider>
  )
}
```

> For Create React App, you need to set this up in **index.js** or **index.tsx**

<br />

# Test area

### typography
# h1
## h2
### h3
#### h4
##### h5
###### h6
p

*italic*

**strong**

_emphasis_

~~strikethrough~~

> blockquote

<!-- ### image
![alt](https://mdx-logo.now.sh) -->

### ul
- List item 1
- List item 2

### ol
1. List item 1
2. List item 2

```
console.log("Hello world!");
```

<Button
    mt={4}
    colorScheme="red">
    Login
</Button>