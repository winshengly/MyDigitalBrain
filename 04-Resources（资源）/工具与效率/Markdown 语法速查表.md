---
title: Markdown 语法速查表
source: https://markdown.com.cn/cheat-sheet.html
author:
  - "[[mrknight]]"
published:
created: 2026-11-12
description: Markdown 速查表提供了所有 Markdown 语法元素的基本解释。如果你想了解某些语法元素的更多信息，请参阅更详细的 基本语法 和 扩展语法。
tags:
  - markdown
  - 工具
---

# Markdown 语法速查表

## 总览

Markdown 速查表提供了所有 Markdown 语法元素的基本解释。如果你想了解某些语法元素的更多信息，请参阅更详细的 [基本语法](https://markdown.com.cn/basic-syntax/) 和 [扩展语法](https://markdown.com.cn/extended-syntax/).

## 基本语法

这些是 John Gruber 的原始设计文档中列出的元素。所有 Markdown 应用程序都支持这些元素。

| 元素 | Markdown 语法 |
| --- | --- |
| [标题（Heading）](https://markdown.com.cn/basic-syntax/headings.html) | <code># H1<br>## H2<br>### H3</code> |
| [粗体（Bold）](https://markdown.com.cn/basic-syntax/bold.html) | `**bold text**` |
| [斜体（Italic）](https://markdown.com.cn/basic-syntax/italic.html) | `*italicized text*` |
| [引用块（Blockquote）](https://markdown.com.cn/basic-syntax/blockquotes.html) | `> blockquote` |
| [有序列表（Ordered List）](https://markdown.com.cn/basic-syntax/lists.html) | <code>1. First item<br>2. Second item<br>3. Third item</code> |
| [无序列表（Unordered List）](https://markdown.com.cn/basic-syntax/lists.html) | <code>- First item<br>- Second item<br>- Third item</code> |
| [代码（Code）](https://markdown.com.cn/basic-syntax/code.html) | `` `code` `` |
| [分隔线（Horizontal Rule）](https://markdown.com.cn/basic-syntax/horizontal-rules.html) | `---` |
| [链接（Link）](https://markdown.com.cn/basic-syntax/links.html) | `[title](https://www.example.com)` |
| [图片（Image）](https://markdown.com.cn/basic-syntax/images.html) | `![alt text](image.jpg)` |

## 扩展语法

这些元素通过添加额外的功能扩展了基本语法。但是，并非所有 Markdown 应用程序都支持这些元素。

| 元素 | Markdown 语法 |
| --- | --- |
| [表格（Table）](https://markdown.com.cn/extended-syntax/tables.html) | <code>\| Syntax \| Description \|<br>\| --- \| --- \|<br>\| Header \| Title \|<br>\| Paragraph \| Text \|</code> |
| [代码块（Fenced Code Block）](https://markdown.com.cn/extended-syntax/fenced-code-blocks.html) | <code>&#96;&#96;&#96;<br>{<br>&nbsp;&nbsp;"firstName": "John",<br>&nbsp;&nbsp;"lastName": "Smith",<br>&nbsp;&nbsp;"age": 25<br>}<br>&#96;&#96;&#96;</code> |
| [脚注（Footnote）](https://markdown.com.cn/extended-syntax/footnotes.html) | <code>Here's a sentence with a footnote.[^1]<br><br>[^1]: This is the footnote.</code> |
| [标题编号（Heading ID）](https://markdown.com.cn/extended-syntax/heading-ids.html) | `### My Great Heading {#custom-id}` |
| [定义列表（Definition List）](https://markdown.com.cn/extended-syntax/definition-lists.html) | <code>term<br>: definition</code> |
| [删除线（Strikethrough）](https://markdown.com.cn/extended-syntax/strikethrough.html) | `~~The world is flat.~~` |
| [任务列表（Task List）](https://markdown.com.cn/extended-syntax/task-lists.html) | <code>- [x] Write the press release<br>- [ ] Update the website<br>- [ ] Contact the media</code> |
