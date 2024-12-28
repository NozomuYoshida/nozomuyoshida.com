---
layout: default
title: まめしばブログ🐕
---

<h1>まめしばブログ</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
