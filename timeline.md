---
layout: default
title: Timeline
---
<h1>Timeline</h1>
<h4>Was bisher geschah.</h4>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
