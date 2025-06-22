{% raw %}---
layout: default
title: Thomas (Tomer) Raz
---{% endraw %}

# Thomas (Tomer) Raz

## Latest Posts
{% raw %}{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ([{{ post.date | date: "%b %-d, %Y" }}])
{% endfor %}{% raw %}{% endraw %}

