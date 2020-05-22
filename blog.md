---
title: Blog
permalink: "/blog/"
href_style: "color:#A9A9A9;"
---

# Posts
---
{% for post in site.posts %}
<a href="{{ post.url }}" style="{{ href_style }}">{{ post.date }} - {{ post.title }}</a>
{{ post.excerpt }}
<a href="{{ post.url }}" style="{{ href_style }}">Read more...</a>
{% endfor %}


