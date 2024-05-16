---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My research falls into explainable and trustworthy AI, especially for self-driving models. I also use network explanation results to achieve some useful applications, *e.g.,* network pruning method. Our ongoing work primarily revolves around end-to-end networks.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}