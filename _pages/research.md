---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My research falls into explainable and trustworthy AI. I also use network explanation results to achieve some useful applications, *e.g.,* network pruning method. Our current work mainly focuses on image processing networks like CNNs and Vision Transformers (ViTs).

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}