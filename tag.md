---
layout: page
title: Blog Posts by Tag
permalink: /tag/
---

<h2> Click on a tag to see associated list of posts. </h2>

<ul>
{% for tag in site.tags %}
  {% assign t = tag | first %}
  <a class="tag" href="/tag/#{{t | downcase | replace:" ","-" }}">@{{ t | downcase }}</a> 
{% endfor %}
</ul>

---

{% for tag in site.tags %}
  {% assign t = tag | first %}
  {% assign posts = tag | last %}

<div class="tag">
<h4><a name="{{t | downcase | replace:" ","-" }}"></a><a class="internal" href="/tag/#{{t | downcase | replace:" ","-" }}">@{{ t | downcase }}</a></h4>

<ul>
{% for post in posts %}
  {% if post.tags contains t %}
  <li style="list-style-type:circle" >
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="date">{{ post.date | date: "%B %-d, %Y"  }}</span> 
  </li>
  {% endif %}
{% endfor %}
</ul>
</div>

---

{% endfor %}
