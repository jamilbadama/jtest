---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Home Page
layout: home
---

{{ page.title }}

{% assign name = "Tobi" %}

{% if name == "Tobi1" %}
This text will always appear since "name" is defined.
{% endif %}

<p class="featured">Featured posts</p>
<h2 class="heading-secondary dark-blue">Latest videos</h2>
<div class="includes-grid">
  {% include youtube.html youtube_id="7W7hEUGtv4U" %}
  {% include youtube.html youtube_id="E3a88_SjJR0" %}
</div>
