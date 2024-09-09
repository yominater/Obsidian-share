---
title: "Obsidian Compatibility"
tags:
  - feature/transformer
---

Quartz was originally designed as a tool to publish Obsidian vaults as websites. Even as the scope of Quartz has widened over time, it hasn't lost the ability to seamlessly interoperate with Obsidian.

By default, Quartz ships with the [ObsidianFlavoredMarkdown](../plugins/ObsidianFlavoredMarkdown.md) plugin, which is a transformer plugin that adds support for [Obsidian Flavored Markdown](https://help.obsidian.md/Editing+and+formatting/Obsidian+Flavored+Markdown). This includes support for features like [wikilinks](wikilinks.md) and [Mermaid diagrams](Mermaid%20diagrams.md).

It also ships with support for [frontmatter parsing](https://help.obsidian.md/Editing+and+formatting/Properties) with the same fields that Obsidian uses through the [Frontmatter](../plugins/Frontmatter.md) transformer plugin.

Finally, Quartz also provides [CrawlLinks](../plugins/CrawlLinks.md) plugin, which allows you to customize Quartz's link resolution behaviour to match Obsidian.

## Configuration

This functionality is provided by the [ObsidianFlavoredMarkdown](../plugins/ObsidianFlavoredMarkdown.md), [Frontmatter](../plugins/Frontmatter.md) and [CrawlLinks](../plugins/CrawlLinks.md) plugins. See the plugin pages for customization options.
