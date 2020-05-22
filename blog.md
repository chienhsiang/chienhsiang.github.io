---
title: Blog
permalink: "/blog/"
---

# Posts
---
{% for post in site.posts %}
<h5 style='font-weight: bold;'>{{ post.date | date: "%F" }}&ensp;{{ post.title }}</h5>
{{ post.excerpt }}
<a href="{{ post.url }}" style="color:blue;">Read more...</a>
{% endfor %}


