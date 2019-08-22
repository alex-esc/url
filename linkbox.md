---
layout: default
title: Link Box
---

{% for tags in site.tags %}
  <h3>{{ tags[linkbox] }}</h3>
  <ul>
    {% for post in tags[linkbox] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
	  {{ post.excerpt }}
    {% endfor %}
  </ul>
{% endfor %}