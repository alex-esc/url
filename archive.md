---
layout: default
title: Archive
---


# Search

Press `f3` on desktop or tap `find in page` on mobile to search for keywords on any page listed above.

# Link bookmarks

When I find something cool to read later later I will add it to my [link box](linkbox.md).

# My own short links

{% for post in site.tags.shortlink %}

<div>
  
    »
  <span class='post-title'>
    <a href="{{ site.path }}{{ post.url }}">{{ post.title }}</a>
  </span>
</div>

{% endfor %}