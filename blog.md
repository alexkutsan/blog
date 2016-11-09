---
layout: page
title: Blog Posts
permalink: /blog/
---

<ul>
        {% for post in site.posts %}
        <li>
            <span class="date">{{ post.date | date: '%Y %b %d' }}</span> - <a href="{{ post.url }}">{{ post.title }}</a> [
            {% for tag in post.tags %}
            <div class = "tag">
              <a href="/tag/#{{t | downcase | replace:" ","-" }}">{{ t | downcase }}</a> 
            </div>
            {% endfor %}
            ]
        </li>
        {% endfor %}
</ul>
