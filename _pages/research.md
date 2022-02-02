---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My research falls into two main areas: calculating neuron attributions, and then visualizing attributions. We also use attributions to achieve some useful applications, *e.g.,* network pruning method. Our current work mainly focuses on image processing networks like CNNs and Vision Transformers.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}