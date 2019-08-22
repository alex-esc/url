---
layout: default
title: Link Box
---

# Link Box

Here are some cool links, articles & blogs I found and want to share with the world.

<ul>
  {% for post in site.tags.linkbox %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
	  <div class="post-date">{{ post.date | date: "%b %-d, %Y" }}</div>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

