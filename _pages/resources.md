---
layout: archive
title: Resources
permalink: /resources/
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.resources %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
