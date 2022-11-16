---
layout: page
show_meta: false
title: "News"
header:
   image_fullwidth: "header_drop.jpg"
permalink: "/news/"
---
<ul>
    {% for post in site.categories.news %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
