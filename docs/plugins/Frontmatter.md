---
title: "Frontmatter"
tags:
  - plugin/transformer
---

This plugin parses the frontmatter of the page using the [gray-matter](https://github.com/jonschlinkert/gray-matter) library. See [](../authoring%20content.md#Syntax), [Obsidian compatibility](../features/Obsidian%20compatibility.md) and [OxHugo compatibility](../features/OxHugo%20compatibility.md) for more information.

> [!note]
> For information on how to add, remove or configure plugins, see the [](../configuration.md#Plugins|Configuration) page.

This plugin accepts the following configuration options:

- `delimiters`: the delimiters to use for the frontmatter. Can have one value (e.g. `"---"`) or separate values for opening and closing delimiters (e.g. `["---", "~~~"]`). Defaults to `"---"`.
- `language`: the language to use for parsing the frontmatter. Can be `yaml` (default) or `toml`.

> [!warning]
> This plugin must not be removed, otherwise Quartz will break.

## API

- Category: Transformer
- Function name: `Plugin.Frontmatter()`.
- Source: [`quartz/plugins/transformers/frontmatter.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/transformers/frontmatter.ts).
