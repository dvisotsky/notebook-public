---
layout: default
title: Places
collection: places
---

<h1>Places</h1>
<ul>
  {% for post in site.places %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
