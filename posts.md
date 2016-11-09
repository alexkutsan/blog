---
layout: page
title: Blog Posts
permalink: /posts/
---

<div class="post__back">
    <a href="/">&lt;-- home</a>
</div>

<h1>Blog Posts : </h1>
    <ul>
        {% for post in site.posts %}
        <li>
            <span class="date">{{ post.date | date: '%Y %b %d' }}</span> - <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        {% endfor %}
</ul>
