---
title: Blog
permalink: "/blog/"
---

## Posts
<ul>
  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.date | date_to_string }} - {{ post.title }}</a></h2>
    {{ post.excerpt }}
  {% endfor %}
</ul>

