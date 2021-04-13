---
title: Getting started
author: Gary Paluk
---

# Getting started

## Installation

Inside your project directory, install PluginIO by running either of the following:

```js
npm i @pluginio/sdk
```

```js
yarn add @pluginio/sdk
```

> For **create-react-app** installation instructions, check this [CRA templates guide](guides/integrations/with-cra).

## Setup Provider

If you are using React, you can set up the **PluginProvider** at the root of your application.

Go to the root of your project and do this:

```
function App() {
  return (
    <PluginProvider>
      <App />
    </PluginProvider>
  )
}
```

> For Create React App, you need to set this up in **index.js** or **index.tsx**

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