---
layout: single
title: Resources
permalink: /resources/
---

## Publication Directory

We have assembled a collection of publications on historic preservation and related topics from the National Park Service, National Alliance of Preservation Commissions, and Association for Preservation Technology International.

Our publication directory published as a [Google Sheet](https://docs.google.com/spreadsheets/d/1_IU4L6yUaZJLSSyonBmxYyotocSEaxeNdqi-Go-6Tyg/edit?usp=sharing) where you can comment with suggestions or corrections.

<div class="PublicationList">
{% for publication in site.data.publications %}
<div class="Publication">
<p><a href="{{ publication.Link }}">
      {{ publication.Title }}
</a></p>
<dl>
  <dt>Publication Year</dt>
  <dd class="Topic">{{ publication.Year }}</dd>
  <dt>Topic</dt>
  <dd class="Topic">{{ publication.Topic }}</dd>
  <dt>Published by</dt>
  <dd>{{ publication.Publisher }}</dd>
  <dt>Publication</dt>
  <dd>{{ publication.PublicationTitle }}</dd>
  <dt>Language</dt>
  <dd class="Language">{{ publication.Language }}</dd>
  <dt>Country</dt>
  <dd class="Country">{{ publication.Country }}</dd>
</dl>
</div>
{% endfor %}
</div>
