---
layout: archive
title: "Tools"
excerpt: "A library of tools of all kinds including practical best practices, free and open-source software, web applications, and more."
permalink: /tools/
author_profile: false
header:
  teaser: http://cdn.loc.gov/service/pnp/highsm/40300/40344v.jpg
  overlay_image: http://cdn.loc.gov/service/pnp/highsm/40300/40344v.jpg
  overlay_filter: .5
  caption: "Farmer Wally Keller's tool collection displayed inside the Duluth Trading Company store, Mt. Horeb, Wisconsin, 2016 August 29 by Carol M. Highsmith. Courtesy [Library of Congress](http://www.loc.gov/pictures/item/2016631162/) ([PD](https://creativecommons.org/publicdomain/mark/1.0/))."
---

<div class="grid__wrapper">
  {% for tool in site.tools %}
    {% include archive-single-tool.html type="grid" %}
  {% endfor %}
</div>
