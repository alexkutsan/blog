---
layout: page
title: Blog Posts
permalink: /blog/
---

<ul>
        {% for post in site.posts %}
        {% assign p = post | first %}
        <li>
            <span>
            <span class="date">{{ post.date | date: '%Y %b %d' }}</span> - <a href="{{ post.url }}">{{ post.title }}</a> 
            <span class="tag"> 

                {% for tag in post.tags %}
                    <a href="/tag/#{{tag | downcase | replace:" ","-" }}">{{ tag | downcase }}</a> 
                {% endfor %}
            </span>
           </span>
        </li>
        {% endfor %}
</ul>
