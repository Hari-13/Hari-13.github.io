---
layout: default
title: "Home"
---
# Welcome to My Personal Blog!
Explore my thoughts on Math, Movies, and Adventures.

## Latest Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date: "%B %d, %Y" }})
{% endfor %}
