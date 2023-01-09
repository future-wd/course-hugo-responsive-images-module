---
title: "Markdown"
date: 2022-07-06T00:36:24-08:00
draft: false
menu: main
weight: 60
image:
  widths: [640, 950, 1300]
resources:
- src: images/placeholder5.jpg
  params:
    aspect_ratio: [1,1]
    loading: eager
    sizes: "(min-width: 768px) 60wv, 100vw"
---

## Shortcode - Aspect ratio 4:3 widths 400,900,1300px

{{< picture src=images/placeholder6.jpg aspect_ratio=16,9  alt="Test Image" >}}

## Render hook using markdown image syntax - all defaults used

![Image ALT text](images/placeholder5.jpg "Image TITLE text")
