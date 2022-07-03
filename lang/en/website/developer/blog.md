---
title: Developer Blog / Plugin.IO
description: Plugin.IO - Developer Blog
keywords: developer, blog, web3, social network, nft, plugin.io, pluginio, NEKO, token, cryptocurrency, crypto
author: Gary Paluk
og_type: article
og_title: Developer Blog / Plugin.IO
og_author: Gary Paluk
og_description: Plugin.IO - Developer Blog
og_url: https://plugin.io/developer/blog
og_image: https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.png
og_image_alt: A cartoon image of fairground. A hot air balloon floats by through an open blue sky
twitter_card: summary_large_image
---

![A Plugin.IO branded banner that shows a young woman in front of a vivid blue background.](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.png)

# Developer blog

<br />

## ✳️ Plugin.IO Design System - AIR
April 15th, 2021 • *6 min read*

<br />


By **Gary Paluk** • Follow on [Twitter](https://twitter.com/garypaluk)

>Gary is the CEO of Plugin.IO and Senior UX Engineer at CrowdStrike, Inc. Throughout his 20 year development career, he has always been striving to empower creators and developers whilst pushing the boundaries of web tech and user experience.

<br />

#### **In this article I will explain some of the decisions and requirements whilst building the Plugin.IO design system.**

<br />

As a design focused software engineer, the subject of design systems is my happy place. Orchestrating and formalizing the delicate balance between aesthetics, accessibility and usability is an enjoyable challenge with many nuances and considerations to remain mindful of. 

<br />

## 🎯 What is a design system?

Design systems aren't new. In 1976, NASA published their Graphics Standards Manual, a guideline, presented to enable design consistency across the various NASA product groups. Such things as; logos, letterheads, fonts and colors are maticulously detailed, allowing any designer to understand the visual expectations and to bring consistency to their work and to the NASA brand.

<br />

## 🎯 What has changed?

Whilst NASA themselves were amongst the first to utilize integrated circuits in 1961, I do doubt that they could have envisaged the technological revolution that would follow. Advancements in semiconductor manufacturing has brought about vastly increased capabilities and incredible new ways in how we interface with our electronic devices.

Powerful computers are now commonplace. We find them in our workplaces, our homes and even in our pockets. How we use these devices and how we manage our dependency upon them has also changed. Our relationship with our devices is increasingly understood and user expectations are ever more demanding. As UX designers, we must apply these considerations across all areas of our products.

<br />

## 🎯 Design language

With any form of design communication, there must be a formal protocol, a design language. Any language that aims to lead a given field must be able to evolve within a changing ecosystem. We built up our research and language upon a foundational model known as [Fit, Form, Function](https://www.technia.co.uk/blog/evaluating-the-change-form-fit-and-function-fff/) and then defined the problem space into three key areas which became known internally as AIR:

- Adaptability
- Intent
- Reusability

<br />

#### **Adaptability**

Design is ever-changing! If a design system cannot evolve then it will undoubtedly lose relevance. The ability to quickly iterate is considered critical at Plugin.IO.

Changes should never be hampered by underlying technical requirements. To achieve this, we carefully considered foundational libraries that are mindful of low level accessibility, separation of interests, proven declarative APIs, industry standard best practices and reduced configuration overhead.

<br />

#### **Intent**

When a user interacts with a system, that system aught to guide user intention:

- Allow mistakes without negative consequence.
- Help intuit actions.
- Leverage common UI/UX patterns.
- Enhance feedback appropriately using:
    - Animation
    - Haptics
    - Color
- Provide industry leading accessibility and an inclusive posture.

<br />

#### **Reusability**

It is important that we remain efficient by maximizing the re-usability of modular blocks. By using discrete elements, elements are composed into blocks which are then composed into reusable components, pages and templates. Our services are fully cross-platform, which means that components must work seamlessly across; mobile, tablet, desktop, Smart TV, kiosks, game consoles and tablets. AIR components are also designed to be multi-lingual, including full RTL language support.

<br />

## 🎯 Get started with AIR

We have made the bold decision to make the AIR design system free and open-source under the MIT license. Early adopters can start using the AIR design system in their personal projects and/or Plugin.IO Apps. Get started today at: [https://air.plugin.io](https://air.plugin.io)

<br />

## 🎯 Libraries and frameworks

We would like to thank the creators of tools and libraries that we have used and/or extended during the development of the AIR design system:

- [Figma](https://figma.com/)
- [Styled System](https://styled-system.com)
- [Storybook](https://storybook.js.org/)
- [Chakra UI](https://chakra-ui.com/)
- [ReactJS](https://reactjs.org/)
- [Material Design Icons](https://materialdesignicons.com/)

<br />
<br />

```javascript
█▀█ █░░ █░█ █▀▀ █ █▄░█ ░ █ █▀█
█▀▀ █▄▄ █▄█ █▄█ █ █░▀█ ▄ █ █▄█
```
---
Built with ❤️ by Team [Plugin.IO](https://github.com/orgs/pluginio/teams/plugin-io-team/members) 🚀

<br />
<br />
