---
layout: home
title: "42'nin yanındaki 2'yi attınız..."
---

Lorem ipsum dolor sit amet. \
I saw the tail of a comet.

Here is my latest posts: 
<div class="blog-post-list">
  {% for post in site.posts %}
    <section class="blog-excerpt">
      <h1>{{ post.title }}</h1>
      {{ post.excerpt }}
      <p class="continue-reading"><a href="{{ post.url }}">Continue Reading</a></p>
    </section>
  {% endfor %}
</div>
