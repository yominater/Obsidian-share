---
title: Welcome to Quartz 4
---

Quartz is a fast, batteries-included static-site generator that transforms Markdown content into fully functional websites. Thousands of students, developers, and teachers are [already using Quartz](showcase.md) to publish personal notes, websites, and [digital gardens](https://jzhao.xyz/posts/networked-thought) to the web.

## 🪴 Get Started

Quartz requires **at least [Node](https://nodejs.org/) v20** and `npm` v9.3.1 to function correctly. Ensure you have this installed on your machine before continuing.

Then, in your terminal of choice, enter the following commands line by line:

```shell
git clone https://github.com/jackyzha0/quartz.git
cd quartz
npm i
npx quartz create
```

This will guide you through initializing your Quartz with content. Once you've done so, see how to:

1. [Writing content](authoring%20content.md) in Quartz
2. [Configure](configuration.md) Quartz's behaviour
3. Change Quartz's [layout](layout.md)
4. [Build and preview](../node_modules/mathjax-full/components/bin/build) Quartz
5. Sync your changes with [GitHub](setting%20up%20your%20GitHub%20repository.md)
6. [Host](hosting.md) Quartz online

If you prefer instructions in a video format you can try following Nicole van der Hoeven's
[video guide on how to set up Quartz!](https://www.youtube.com/watch?v=6s6DT1yN4dw&t=227s)

## 🔧 Features

- [Obsidian compatibility](features/Obsidian%20compatibility.md), [full-text search](features/full-text%20search.md), [graph view](features/graph%20view.md), note transclusion, [wikilinks](features/wikilinks.md), [backlinks](features/backlinks.md), [Latex](features/Latex.md), [syntax highlighting](features/syntax%20highlighting.md), [popover previews](features/popover%20previews.md), [Docker Support](features/Docker%20Support.md), [internationalization](features/i18n.md), [comments](features/comments.md) and [many more](./features) right out of the box
- Hot-reload for both configuration and content
- Simple JSX layouts and [page components](advanced/creating%20components.md)
- [Ridiculously fast page loads](features/SPA%20Routing.md) and tiny bundle sizes
- Fully-customizable parsing, filtering, and page generation through [plugins](advanced/making%20plugins.md)

For a comprehensive list of features, visit the [features page](/features). You can read more about the _why_ behind these features on the [philosophy](philosophy.md) page and a technical overview on the [architecture](advanced/architecture.md) page.

### 🚧 Troubleshooting + Updating

Having trouble with Quartz? Try searching for your issue using the search feature. If you haven't already, [upgrade](upgrading.md) to the newest version of Quartz to see if this fixes your issue.

If you're still having trouble, feel free to [submit an issue](https://github.com/jackyzha0/quartz/issues) if you feel you found a bug or ask for help in our [Discord Community](https://discord.gg/cRFFHYye7t).
