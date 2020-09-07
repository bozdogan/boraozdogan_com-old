---
layout: default
title: Blog Posts
---
Latest blog posts:

{% for post in site.posts %}
 * {{ post.date | date: "%d.%m.%Y" }} [{{ post.title }}]({{ post.url }})
	
	tags: {% for tag in post.tags -%}
		{{tag}}{% unless last %}, {% endunless %}
	{%- endfor %}
{% endfor %}