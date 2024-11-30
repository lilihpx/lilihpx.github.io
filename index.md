---
layout: default
title: Home
---

# Welcome to My Jekyll Site

This is a simple Jekyll website hosted on GitHub Pages.

## Latest Posts

{% for post in site.posts limit:3 %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
