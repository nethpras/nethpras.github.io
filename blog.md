
---
layout: default
title: "Blog"
permalink: /blog/
---

# Blog

<p class="small-note">
Short posts are fine. Post format: <b>what I built → what worked → what failed → next steps</b>.
</p>

{% for post in site.posts %}
  <div class="card" style="margin-bottom:14px">
    <h3 style="margin-bottom:6px"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <div class="meta">{{ post.date | date: "%b %d, %Y" }}</div>
    <p>{{ post.excerpt | strip_html | truncate: 200 }}</p>
    <a class="btn" href="{{ post.url | relative_url }}">Read</a>
  </div>
{% endfor %}
