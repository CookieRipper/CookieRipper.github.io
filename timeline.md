---
layout: default
title: Timeline
---
<h1>Timeline</h1>
<b>Was bisher geschah.</b>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <b>{{ post.date }}</b>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
