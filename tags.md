---
layout: default
title: tags
---
<ul>
    {% for tag in site.tags %}
    <li><a href="/tags/{{ tag.slug }}">{{ tag.slug }}</a>: {{ tag.description }}</li>
    {% endfor %}
</ul>