---
layout: post
title: "@media (prefers-color-scheme)"
categories: [programming]
tags: [css, media-queries]
---

This is a new CSS3 feature, currently not supported by any browsers other than Safari on iOS, but hopefully other browsers follow suit.

```css
@media (prefers-color-scheme: dark) {
  body {
    background-color: #111;
    color: #dddddd;
  }
}
```