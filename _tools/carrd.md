---
title: Carrd
category: "websites"
description: "Carrd هي خدمة اشتراك لبناء صفحات هبوط (Landing Pages) ومواقع ويب بسيطة."
icon: carrd.png
website: https://carrd.co
syntax:
  - id: headings
    available: n
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: n
  - id: ordered-lists
    available: p
    notes: "Nested lists are not supported."
  - id: unordered-lists
    available: p
    notes: "Nested lists are not supported."
  - id: code
    available: p
    notes: "Code blocks are not supported."
  - id: horizontal-rules
    available: n
  - id: links
    available: p
    notes: "The link styles for [URLs and email addresses](/basic-syntax#urls-and-email-addresses) and [reference-style links](/basic-syntax#reference-style-links) are not supported."
  - id: images
    available: n
  - id: tables
    available: n
  - id: fenced-code-blocks
    available: n
  - id: syntax-highlighting
    available: n
  - id: footnotes
    available: n
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: n
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: n
  - id: auto-url-linking
    available: n
  - id: disabling-auto-url
    available: n
  - id: html
    available: n
---

[Carrd](https://carrd.co) is a web-based subscription services that helps you build landing pages and simple websites. It really shines when you need a one-page website _now_ — it literally takes minutes to build and publish a website using Caard. You can use Carrd's "no code" web interface to easily add and edit elements on your websites, like images and text.

{% include image.html file="/assets/images/tools/carrd.png" alt="The Carrd website builder with Markdown." %}

Carrd supports a limited subset of basic Markdown syntax for text. Carrd's Markdown support is fairly limited, but it works for this particular use case. The supported syntax elements are mostly limited to text formatting — bold, italic, and lists.

{% include tool-syntax-table.html %}

### Support for Additional Syntax Elements

As an added bonus, Carrd provides support for several obscure elements.

<table class="table table-bordered" style="font-size: 14px">
  <thead class="thead-light">
    <tr>
      <th>Element</th>
      <th>Markdown</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Highlight</td>
      <td><code>==word or phrase==</code></td>
      <td><mark>word or phrase</mark></td>
    </tr>
  </tbody>
</table>
