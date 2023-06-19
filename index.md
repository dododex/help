---
layout: faq
title: Dododex Help
permalink: /
hideHeading: true
---

<br><br>
> Need some help using Dododex, the companion app for ARK: Survival Evolved? Here are some frequently asked questions.

## Using Dododex

{% for page in site.pages %}
  {% if page.category == 'using-dododex' %}
- [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}

## Dododex Pro

{% for page in site.pages %}
  {% if page.category == 'dododex-pro' %}
- [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}

## Dododex Bugs

{% for page in site.pages %}
  {% if page.category == 'bugs' %}
- [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}

## ARK Survival Evolved Guides

{% for page in site.pages %}
  {% if page.category == 'guides' %}
- [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}