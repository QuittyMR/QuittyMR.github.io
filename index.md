---
layout: default
title: Thomas (Tomer) Raz
---

## Latest Articles

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ([{{ post.date | date: "%b %-d, %Y" }}])
{% endfor %}
