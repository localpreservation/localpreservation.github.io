---
layout: archive
title: Resources
permalink: /resources/
excerpt: 'Find, reuse, and remix educational resources created and collected by the Local Preservation School.'
header:
  teaser: /assets/images/18659u.jpg
  overlay_image: /assets/images/18659u.jpg
  overlay_filter: .5
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.resources %}
    {% include resource-single.html type="grid" %}
  {% endfor %}
</div>
