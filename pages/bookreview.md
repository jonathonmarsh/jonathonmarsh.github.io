---
layout: page
show_meta: false
title: "Book Reviews"
header:
   image_fullwidth: "korabridge.jpg"
permalink: "/bookreview/"
---
<ul>
    {% for post in site.categories.bookreview %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
