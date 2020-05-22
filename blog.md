---
title: Blog
permalink: "/blog/"
href_style: "color:#A9A9A9;"
---

# Posts
---
{% for post in site.posts %}
<h2>{{ post.date | date: %F }} - {{ post.title }}</h2>
{{ post.excerpt }}
<a href="{{ post.url }}" style="color:blue;">Read more...</a>
{% endfor %}


