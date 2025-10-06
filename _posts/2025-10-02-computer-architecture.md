---
layout: post
---

<ul>
  {% for item in site.computer-architecture %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>