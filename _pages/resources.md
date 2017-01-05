---
layout: single
title: Resources
permalink: /resources/
excerpt: 'Find, reuse, and remix educational resources created and collected by the Local Preservation School.'
header:
  teaser: /assets/images/18659u.jpg
  overlay_image: /assets/images/18659u.jpg
  overlay_filter: .5
---

<!-- The resource filter used below is based on Category Filtering with Isotope in Jekyll: http://cagrimmett.com/projects/2016/09/15/jekyll-categories-isotope.html -->

<h2>Filter by topic</h2>
<div class="button-group filter-button-group">
  <a class="btn btn--x-large active" data-filter="*">All</a>
  {% for topic in site.data.topics %}
		<a class="btn btn--x-large btn--info" data-filter=".{{ topic.name }}">{{ topic.name }}</a>
	{% endfor %}
</div>

<div class="grid">
	{% for resource in site.resources %}
     <div class="element-item {{ resource.topic | join: ' ' }}">
        <h2>
          <a class="post-link" href="{{ resource.url | prepend: site.baseurl }}">{{ resource.title }}</a>
        </h2>
        <i>{{ resource.date | date: "%b %-d, %Y" }}</i>
        <p class="archive__item-excerpt">
        <div style="max-width: 30%; max-height: 30%; " class="align-right">
          <img src="{{ resource.header.teaser | absolute_url }}" alt="{{ resource.title }}">
        </div>
          {{ resource.excerpt }}
        </p>
     </div>
    {% endfor %}
</div>

{% include isotope.html %}
