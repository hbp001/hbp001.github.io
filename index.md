---
layout: default
title: Home
---

# My Paper

---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

<br>

[View My GitHub Profile](https://github.com/hbp001)