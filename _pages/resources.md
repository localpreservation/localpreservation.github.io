---
layout: archive
title: Resources
permalink: /resources/
excerpt: 'Find, reuse, and remix educational resources created and collected by the Local Preservation School.'
header:
  teaser: 571995cu-dark.jpg
  overlay_color: "#838383"
  overlay_image: 571995cu-dark.jpg
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.resources %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
