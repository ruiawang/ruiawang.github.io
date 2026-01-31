---
layout: default
---
<!---->
## welcome to my site!
I'm a software engineer at [Google](https://about.google/company-info/), working on infrastructure for high-performance computing and AI/ML clusters.
Previously, I was a data scientist at [KraftHeinz](https://www.kraftheinz.com/) implementing and deploying machine learning models in manufacturing plants.

## posts
<ul class="post-list">
    {% for post in site.posts %}
    <li><a class="{{ post.title }}" href="{{ post.url }}">{{ post.title }}</a> <span class="post-date">({{ post.date | date_to_string: "ordinal", "US" }})</span></li>
    {% endfor %}
</ul>