---
layout: page
title: Blog Posts
permalink: /blog/
---

<ul>
        {% for post in site.posts %}
        <li>
            <span class="date">{{ post.date | date: '%Y %b %d' }}</span> - <a href="{{ post.url }}">{{ post.title }}</a> <div class = "tag"> [{% for tag in post.tags %} <a href="/tag/#{{t | downcase | replace:" ","-" }}">{{ t | downcase }}</a> {% endfor %}]
            </div>
        </li>
        {% endfor %}
</ul>
