---
title: "Miro Cupak"
layout: default
excerpt_separator: <!--more-->
image_file: mcupak.jpg
category:
  - people
tags:
  - contributors
  - developers
  - Discovery
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; width: 80px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

Lead, GA4GH Discovery Networks

Co-lead, GA4GH Discovery Search

VP Engineering, DNAstack

<!--more-->

web [mirocupak.com](https://mirocupak.com/), [dnastack.com](http://dnastack.com)
