---
layout: tag
tag: politik
permalink: /tags/politik/
---

<ul>
  {% for post in site.tags[page.tag] %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
