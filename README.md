# Re: Markdown PDF

This extension converts Markdown files to pdf or html files.

:warning: This Extension is currently a WIP (Work in Progress), please do not use it at its current state. :warning:

> **Note:**  
> This extension is originally a fork of [yzane/vscode-markdown-pdf](https://github.com/yzane/vscode-markdown-pdf/).

In this fork, the focus is on printing PDF files, not images.  
You'll find more support regarding the export to PDF with your VS Code
extensions and the built-in preview.

This fork was also made to support my extension to create graphs.

## Table of Contents
<!-- TOC depthFrom:2 depthTo:2 updateOnSave:false -->

- [Re: Markdown PDF](#re-markdown-pdf)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Install](#install)
  - [Extension Settings](#extension-settings)
  - [License](#license)

<!-- /TOC -->

## Features

This extension supports the following features:

- [Syntax highlighting](https://highlightjs.org/static/demo/)
- [emoji](https://www.webfx.com/tools/emoji-cheat-sheet/)
- [markdown-it-checkbox](https://github.com/mcecot/markdown-it-checkbox)
- [markdown-it-container](https://github.com/markdown-it/markdown-it-container)
- [markdown-it-include](https://github.com/camelaissani/markdown-it-include)
- [PlantUML](https://plantuml.com/)
  - [markdown-it-plantuml](https://github.com/gmunguia/markdown-it-plantuml)
- [mermaid](https://mermaid-js.github.io/mermaid/)

You can find the following sample files:

- [pdf](sample/README.pdf)
- [html](sample/README.html)

## Install

The first time you install and use this extension, we ask of you to accept to download chromium.  
If you already have Chromium installed, you can specify its location using the `reMarkdownPDF.chromiumPath` setting.

During the download of chromium, you'll see the `Installing Chromium` message displayed in the status bar.

If you are behind a proxy, set the `http.proxy` option to settings.json and restart Visual Studio Code.

## Extension Settings

TODO

## License

This package is under the MIT License, see [the license file](./LICENSE.txt)
