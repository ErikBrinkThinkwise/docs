## Thinkwise Platform Documentation

This project contains all platform related documentation, a knowledge base and information (blog posts) on new releases.

## Build status

[![Build status](https://dev.azure.com/thinkwise/Documentation/_apis/build/status/Documentation-CI)](https://dev.azure.com/thinkwise/Documentation/_build/latest?definitionId=57)

## Code style

Please use the [vscode-markdownlint](https://github.com/DavidAnson/vscode-markdownlint) extension.

## Framework

Built with [Docusaurus](https://docusaurus.io/).

## Installation

For detailed requirements and instructions, see the [Docusaurus docs](https://docusaurus.io/docs/en/installation).

1. Install Docusaurus

   ```sh
   npm install
   ```

2. Start the website

   ```sh
   npm start
   ```

## Guidelines

See the [markdownlint rules](https://github.com/DavidAnson/markdownlint/blob/master/doc/Rules.md). Some overrides are defined in the `.markdownlint.json` configuration file.

### New pages

New pages need to be registered in `sidebars.json`.

Start every page with a [YAML front matter](http://assemble.io/docs/YAML-front-matter.html) title definition. This title is displayed in the sidebar and at the top of the page.

```yaml
---
title: Title of the page
---
```

Start with level two `##` heading and always increment headings by one level.

### Images

Images are stored in the `/docs/assets` folder and referenced using a relative path, e.g. `..\assets\image.png`.

Use Visual Studio Code with the [vscode-markdown-paste-image](https://github.com/telesoho/vscode-markdown-paste-image) exension or [Typora](https://typora.io/) to auto copy images on paste.

![1538725116127](../assets/1538725116127.png)