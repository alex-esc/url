---
layout: default
title: Archive
---


# Search

Press `f3` on desktop or tap `find in page` on mobile to search for keywords on any page listed above.

[All content in one page](all.md).





# Short links in reverse chronological oder

{% for post in site.tags.shortlink %}

<div>
  
    »
  <span class='post-title'>
    <a href="{{ site.path }}{{ post.url }}">{{ post.title }}</a>
	( {{ post.excerpt }} )
  </span>
</div>

{% endfor %}