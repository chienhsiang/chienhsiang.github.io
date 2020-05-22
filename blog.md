---
title: Blog
permalink: "/blog/"
---

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ page.date | date_to_string }} - {{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
<!-- <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul> -->


