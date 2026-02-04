---
layout: home
---

## Latest Blogs

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%d %b %Y" }})</small>
    </li>
  {% endfor %}
</ul>
