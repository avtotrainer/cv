---
layout: default
title: "CV"
---

<h1>ᲑᲚᲝᲒᲘ</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>