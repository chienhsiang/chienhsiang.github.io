---
title: CH's Blog
permalink: "/blog/"
---
<!-- style='font-weight: bold;' -->

# Posts
---
{% for post in site.posts %}
<h5 style='font-weight: bold;'>
    <a href="{{ post.url }}">{{ post.date | date: "%F" }} &ensp; {{ post.title }}</a>
</h5>
<div style="margin-left: 40px">
    {{ post.excerpt | remove: '<p>' | remove: '</p>'}} <br>
    <a href="{{ post.url }}" style="color:blue;">(Read more...)</a>
</div>
<hr>
{% endfor %}


