---
title: CH's Blog
permalink: "/blog/"
---
<!-- style='font-weight: bold;' -->

# Posts
---
{% for post in site.posts %}
<h5>{{ post.date | date: "%F" }} ~ {{ post.title }}</h5>
<blockquote>
    {{ post.excerpt }}
    <a href="{{ post.url }}" style="color:blue;">(Read more...)</a>
<blockquote>
<hr>
{% endfor %}


