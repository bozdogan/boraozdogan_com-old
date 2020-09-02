---
layout: default
title: Blog Posts
---
Latest blog posts:

{% for post in site.posts %}
 * {{ post.date | date: "%d.%m.%Y" }} [{{ post.title }}]({{ post.url }})
{% endfor %}