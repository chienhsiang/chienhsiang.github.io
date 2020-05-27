---
title: CH's Blog
permalink: "/blog/"
---
<!-- style='font-weight: bold;' -->

{% for post in site.posts %}
<hr>
<h5 style="font-weight: bold">
    <a href="{{ post.url }}" style="color:black;">
        {{ post.date | date: "%F" }} &ensp; {{ post.title }}
    </a>
</h5>
<div style="margin-left: 20px;">
    {{ post.excerpt | remove: '<p>' | remove: '</p>'}} &emsp;
    <a href="{{ post.url }}" style="color:blue;">(Read more...)</a>
</div>
{% endfor %}


