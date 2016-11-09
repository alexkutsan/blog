---
layout: page
title: Blog Posts
permalink: /posts/
---
# Blog Posts :

<ul>
        {% for post in site.posts %}
        <li>
            <span class="date">{{ post.date | date: '%Y %b %d' }}</span> - <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        {% endfor %}
</ul>
