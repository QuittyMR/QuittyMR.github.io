---
layout: default
title: Thomas (Tomer) Raz
---

## Latest Articles

{% for post in site.posts %}
- [{{ post.date | date: "%b %-d, %Y" }}] [{{ post.title }}]({{ post.url }})
{% endfor %}
