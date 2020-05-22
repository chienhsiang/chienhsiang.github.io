---
title: CH's Blog
permalink: "/blog/"
---
<!-- style='font-weight: bold;' -->

# Posts
---
{% for post in site.posts %}
<h5 style='font-weight: bold;'>{{ post.date | date: "%F" }} &ensp; {{ post.title }}</h5>
<div style="margin-left: 200px">
    {{ post.excerpt }}
    <a href="{{ post.url }}" style="color:blue;">(Read more...)</a>
</div>
<hr>
{% endfor %}


