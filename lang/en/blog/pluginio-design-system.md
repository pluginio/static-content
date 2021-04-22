---
title: "Plugin.IO Design System - Air"
author: "Gary Paluk"
description: test
keywords: test
og_type: article
og_site_name: Plugin.IO
og_title: test
og_description: test
og_image: test
og_url: test
fb_app_id: 523943968175208
twitter_card: test
twitter_site: "@pluginio"
twitter_site_id: 216319337
twitter_title: test
twitter_description: test
twitter_image: test
---

By **Gary Paluk** • Follow on [Twitter](https://twitter.com/garypaluk)

>Gary is the CEO of Plugin.IO and Senior UX Engineer at CrowdStrike, Inc. Throughout his 20 year development career, he has always been striving to empower creators and developers whilst pushing the boundaries of web tech and user experience.

![A Plugin.IO branded banner that shows a young woman in front of a vivid blue background.](https://raw.githubusercontent.com/pluginio/static-content/main/lang/en/docs/v1/images/header_banner.jpg)

# Plugin.IO Design System - AIR
April 15th, 2021 • *6 min read*

### **In this article I will explain some of the decisions and requirements whilst building the Plugin.IO design system.**

<br />

As a design focussed software engineer, the subject of design systems is my happy place. Orcastrating and formalizing the delicate balance between aesthetics, accessibility and usability is an enjoyable challenge with many nuances and considerations to remain mindful of. 

<br />

# What is a design system?

Design systems aren't new. In 1976, NASA published their Graphics Standards Manual, a guideline, presented to enable design consistency across the various NASA product groups. Such things as; logos, letterheads, fonts and colors are maticulously detailed, allowing any designer to understand the visual expectations and to bring consistency to their work and to the NASA brand.

<br />

# What has changed?

Whilst NASA themselves were amongst the first to utilize integrated circuits in 1961, I do doubt that they could have envisaged the technological revolution that would follow. Advancements in semiconductor manufacturing has brought about vastly increased capabilities and incredible new ways in how we interface with our electronic devices.

Powerful computers are now commonplace. We find them in our workplaces, our homes and even in our pockets. How we use these devices and how we manage our dependency upon them has also changed. Our relationship with our devices is increasingly understood and user expectations are ever more demanding. As UX designers, we must apply these considerations across all areas of our products.

<br />

# Design language

With any form of design communication, there must be a formal protocol, a design language. Any language that aims to lead in a given field must be able to evolve with a changing ecosystem. During our initial research, we defined the problem space into three key areas which became known internally as AIR:

- Adaptability
- Intent
- Reusability

<br />

### **Adaptability**

Design is ever-changing! If a design system cannot evolve then it will undoubtably lose relevance. The ability to quickly iterate is considered critical a Plugin.IO. We focussed our efforts on ensuring that components are able to adapt easily, from low level modular changes through to global themes that can adapt according to operating system settings.

Making changes should be quick, simple and never bogged down in technical details. To acheive this, we carefully considered foundational libraries that are deeply routed in modularity, accessibility, proven declarative APIs, industry best practices and reducing configuration overhead.

<br />

### **Intent**

When a user interacts with a system, that system must act to understand user intent:

- Allow mistakes without negative consequence.
- Help intuit actions.
- Leverage common UI/UX patterns.
- Enhance feedback appropriately using:
    - Animation
    - Haptic
    - Color
- Provide accessibity with an industry leading inclusivity posture.

<br />

### **Reusability**

By using discrete elements, our goal is to maximize reusability by generalizing modular blocks. These blocks are further composed into reusable components, pages and templates. Plugin.IO is fully cross-platform, meaning that these components must work seamlessly across; mobile, desktop, Smart TV, kiosks, game consoles and tablet etc. We want to ensure consistency by reusing the same components across all devices and had to design these accordingly.

# Documentation

Early adopters can start using the AIR design system for their personal projects and Plugin.IO apps today. You can find documentation over at: [https://air.plugin.io](https://air.plugin.io)

<br />

# Libraries and frameworks

We would like to thank the creators of tools and libraries that we have used and/or extended:

- [Figma](https://figma.com/)
- [Styled System](https://styled-system.com)
- [Storybook](https://storybook.js.org/)
- [Chakra UI](https://chakra-ui.com/)
- [ReactJS](https://reactjs.org/)
- [Material Design Icons](https://materialdesignicons.com/)
