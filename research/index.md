---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Description of our research.

{% include section.html %}

## Highlighted

{%
  include citation.html
  lookup="doi:10.1103/PRXLife.1.013008"
  style="rich"
%}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
