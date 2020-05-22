---
title: Blog
permalink: "/blog/"
---

# Posts
---
{% for post in site.posts %}
<h5 style='font-weight: bold;'>{{ post.date | date: "%F" }} ~ {{ post.title }}</h5>
&ensp;{{ post.excerpt }}
&ensp;<a href="{{ post.url }}" style="color:blue;">Read more...</a>
<hr>
{% endfor %}


