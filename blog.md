---
title: CH's Blog
permalink: "/blog/"
---
<!-- style='font-weight: bold;' -->

{% for post in site.posts %}
<hr>
<h5 style="font-weight: bold">
    <a href="{{ post.url }}" style="color:#505050;">
        {{ post.date | date: "%F" }} &ensp; {{ post.title }}
    </a>
</h5>
<div style="margin-left: 20px;padding-top: 0px;">
    <p style="padding-top: 0px;">
        {{ post.excerpt | remove: '<p>' | remove: '</p>'}} &emsp;
        <a href="{{ post.url }}" style="color:blue;">(Read more...)</a>
    </p>
</div>
{% endfor %}


