---
layout: default
title: tags
permalink: /whims/tags/index.html
---
<ul>
    {% for tag in site.whim_tags %}
    <li><a href="/whims/tags/{{ tag.slug }}">{{ tag.slug }}</a>: {{ tag.description }}</li>
    {% endfor %}
</ul>