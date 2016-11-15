---
layout: default
title: Styleguide
---

# ![logo of pollistics]({{site.baseurl}}/src/img/logo.svg) styleguide

This is the living styleguide of pollistics.

## components

{% for component in site.components %}
* [{{component.title}}]({{site.baseurl}}{{component.id}})
{% endfor %}
