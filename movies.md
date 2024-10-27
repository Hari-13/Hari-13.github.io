---
layout: default
title: "Movies Blogs"
---
# Movies Blogs

{% for post in site.categories.movies %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
