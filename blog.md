---
title: CH's Blog
permalink: "/blog/"
---
<!-- style='font-weight: bold;' -->

# Posts
---
{% for post in site.posts %}
<p style="margin-left: 200px">
    <h5 style='font-weight: bold;'>{{ post.date | date: "%F" }} &ensp; {{ post.title }}</h5>
    {{ post.excerpt | remove: '<p>' | | remove: '</p>' | markdownify }} <br>
    <a href="{{ post.url }}" style="color:blue;">(Read more...)</a>
</p>
<hr>
{% endfor %}


