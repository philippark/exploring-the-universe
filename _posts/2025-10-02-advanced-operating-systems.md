---
layout: post
---

<ul>
  {% for item in site.advanced-operating-systems %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>