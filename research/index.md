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
  lookup="url:https://proceedings.neurips.cc/paper_files/paper/2023/hash/297fe652867e4897e9f1fe1cd715de19-Abstract-Conference.html"
  style="rich"
%}

{%
  include citation.html
  lookup="doi:10.1103/PRXLife.1.013008"
  style="rich"
%}

{%
  include citation.html
  lookup="doi:10.1162/neco_a_01414"
  style="rich"
%}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="plain" %}
