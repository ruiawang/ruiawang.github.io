---
layout: default
permalink: /whims/index.html
title: whims
---
<nav>
    <a href="/">Home</a>
</nav>
As opposed to the posts on the rest of my website, which focuses on topics that I have academic interest or whose writing I am willing to show, in a semi-professional manner, this section will be dedicated to less serious topics, and whose writing I can only guarantee to be no worse than ramblings or rants.

## posts
<ul class="post-list">
{% for post in site.whims %}
<li><a class="{{ post.title }}" href="{{ post.url }}">{{ post.title }}</a> <span class="post-date">({{ post.date | date_to_string: "ordinal", "US" }})</span></li>
{% endfor %}
</ul>