---
title: Research
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research

Here are our projects.

{% comment %}

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

{% endcomment %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
