---
title: "html"
date: "2021-07-07"
author: ""
path: "/html"
---

- [Head](#head)
  - [Meta Elements](#meta-elements)
    - [Viewport](#viewport)
    - [Description](#description)
- [Body](#body)
  - [Text Elements](#text-elements)
    - [Paragraph](#paragraph)
    - [Emphasize](#emphasize)
  - [Entities](#entities)
    - [Non-Breaking Space](#non-breaking-space)
  - [Hyperlinks](#hyperlinks)
    - [General](#general)
    - [Anker Tag](#anker-tag)
    - [In-Site Link](#in-site-link)

# Head

Contains the information about the webpage.

## Meta Elements

### Viewport
Defines initial width and zoom-factor.

### Description
Short text that shows up in search engines.

# Body

## Text Elements

### Paragraph
`<p>` represents a text paragraph element.
### Emphasize
`<em>` emphasizes content, often used by search engines to determine relevant content.

## Entities

### Non-Breaking Space
`&nbsp` acts like " " but puts word element on the next line.

## Hyperlinks
A hyperlink describes the complete html element:

`<h2 href="` Link `">Go to Fragment</h2>`

### General
`target="_blank"` will make hyperlink open a new tab.

### Anker Tag
`<a>` should always contain an `href` element.

### In-Site Link
1. Give Fragment an id: `<h2 id="fragment-id">Go to Fragment</h2>`
2. Clickable element linking to fragment: `<a href="#fragment-id">Fragment</a>`