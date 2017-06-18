---
layout: default
---
Index
-----
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a></br>
      {{ post.date }}
    </li>
  {% endfor %}
</ul>
