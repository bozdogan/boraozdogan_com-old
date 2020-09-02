---
layout: default
title: Blog Posts
---

{% for post in site.posts %}
 * {{ post.date | date: "%d.%m.%Y" }} [{{ post.title }}]({{ post.url }})
{% endfor %}