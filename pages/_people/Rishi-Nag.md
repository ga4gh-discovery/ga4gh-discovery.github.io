---
title: "Rishi Nag"
layout: default
excerpt_separator: <!--more-->
image_file: rnag.jpg
category:
  - people
  - contact
tags:
  - contacts
  - contributors
  - leads
  - developers
  - admins
  - GA4GH
  - Discovery
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; width: 100px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

Coordinator, GA4GH Discovery Workstream  
Global Alliance for Genomics and Health  
EMBL-EBI, Wellcome Genome Campus  

<!--more-->

email [rishi.nag@ga4gh.org](mailto:rishi.nag@ga4gh.org)  
web [EBI](https://www.ebi.ac.uk/about/people/rishi-nag)  

