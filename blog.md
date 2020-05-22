---
title: CH's log
permalink: "/blog/"
---

# Posts
---
{% for post in site.posts %}
<h5 style='font-weight: bold;'>{{ post.date | date: "%F" }} ~ {{ post.title }}</h5>
<p stype="margin-left:10%">
    {{ post.excerpt | remove: '<p>' | remove: '</p>' }}<a href="{{ post.url }}" style="color:blue;">(Read more...)</a>
</p>
<hr>
{% endfor %}


