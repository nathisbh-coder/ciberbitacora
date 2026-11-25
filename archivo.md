---
layout: default
title: Archivo
permalink: /archivo/
---
# Archivo de entradas

<ul class="archive">
{% for post in site.posts %}
  <li><time>{{ post.date | date: '%d/%m/%Y' }}</time> <a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span class="tag">{{ post.category }}</span></li>
{% endfor %}
</ul>
