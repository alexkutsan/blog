---
layout: page
title: Blog Posts
permalink: /blog/
---

<ul>
        {% for post in site.posts %}
        {% assign p = post | first %}
        <li>
            <span class="date">{{ post.date | date: '%Y %b %d' }}</span> - <a href="{{ post.url }}">{{ post.title }}</a> <div class="tag"> <ul>
                {% for tag in post.tags %}
                  {% assign t = tag | first %}
                  <a href="/tag/#{{t | downcase | replace:" ","-" }}">{{ t | downcase }}</a> 
                {% endfor %}
                </ul>
            </div>
        </li>
        {% endfor %}
</ul>
