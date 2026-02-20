---
layout: default
title: "Tomato Plant Anatomy Series"
permalink: /series/tomato-anatomy/
---

# Tomato Plant Anatomy Series

<p class="small">A story-driven anatomy series: kitchen logic + plant science.</p>

{% assign s = site.posts | where: "series", "tomato-anatomy" | sort: "series_order" %}

{% for post in s %}
  <div class="card" style="margin-bottom:14px">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <div class="meta">Part {{ post.series_order }} • {{ post.date | date: "%b %d, %Y" }}</div>
    <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
    <a class="btn" href="{{ post.url | relative_url }}">Read</a>
  </div>
{% endfor %}
