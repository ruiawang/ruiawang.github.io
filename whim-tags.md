---
layout: default
title: whim tags
permalink: /whims/tags/index.html
---
<nav>
    <a href="/whims">Whims</a>
</nav>
<ul>
    {% for tag in site.whim_tags %}
    <li><a href="/whims/tags/{{ tag.slug }}">{{ tag.slug }}</a>: {{ tag.description }}</li>
    {% endfor %}
</ul>