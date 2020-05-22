---
title: Blog
permalink: "/blog/"
---

# Posts
---
{% for post in site.posts %}
<h5 style='font-weight: bold;'>{{ post.date | date: "%F" }} ~ {{ post.title }}</h5>
<p style="margin-left: 400px">
    {{ post.excerpt }}
    <a href="{{ post.url }}" style="color:blue;">Read more...</a>
</p>
{% endfor %}


