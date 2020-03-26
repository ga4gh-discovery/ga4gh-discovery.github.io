---
title: GA4GH Discovery Work Stream
layout: default
date: 2018-12-13
permalink: /index.html
author: mbaudis
category:
  - about
---

## {{page.title}}

The [GA4GH Discovery Work Stream](http://ga4gh-discovery.github.io) builds and coordinates standards for federated, secured networks of data and services, to form an “Internet of Genomics” for enabling data discovery and retrieval in health research and clinical genomics.

The Discovery Work Stream is lead by Marc Fiume and Michael Baudis. For details on how this Work Stream operates please read the [Discovery Work Stream Organizational Structure & Vision document](https://docs.google.com/document/d/1WFjZ9yBx8Vxn97QORRNQN7O3DBnhpwEUX2mK7f2C4EA/edit?ts=59ed3535#).

This group meets at a high-level monthly. In addition, the sub-groups listed below meet on their own schedules. Participation in these groups is open but requires adherence to the [GA4GH Standards for Professional Conduct](https://www.ga4gh.org/docs/GA4GH-Standards-for-Professional-Conduct_22-Jan-2018.pdf).

### Products

Product development in GA4GH follows a process outlined in a [GA4GH Product Approval Process Guide, in draft](https://docs.google.com/document/d/1UUJSnsPw32W5r1jaJ0vI11X0LLLygpAC9TNosjSge_w/edit#heading=h.tyqycskyykwh). Products developed by the work stream undergo an initial investigation phase, followed by a formal Proposed Product Phase, in which most of the work is done, followed by an formal Approval Phase during which the products gain GA4GH Approval. The formal steps require the approval of the Work Stream leads.

The following products are currently under development for this Work Stream. 

##### Beacon API

<a href="http://beacon-project.io" target="_blank"><img style="float: right; width: 40px; clear: none" src="{{ '/assets/img/logo_beacon.png' | relative_url }}" /></a>A _Beacon_ is a federated, web-accessible service that can be queried for information about a specific genomic variant, e.g. a single nucleotide polymorphism (SNP/SNV) or a copy number variation (CNV), and reports about its existence in the queried resources. Current versions of the Beacon protocol support different usage scenarios and offer the opportunity to link to the matched data using e.g. a [_handover_](https://beacon-project.io/roadmap/handover.html) protocol.

The Beacon API specification is a [__GA4GH approved standard__](https://www.ga4gh.org/genomic-data-toolkit/). It is being developed through the [ELIXIR Beacon project](http://beacon-project.io) and accessible there or directly trough its [repository](https://github.com/ga4gh-beacon/specification).

* Responsible Discovery co-chair: [Michael Baudis](https://info.baudisgroup.org/group/Michael_Baudis/)
* Product leads:
    - Jordi Rambla
    - Tony Brooks
    - Juha Törnroos
    - Gary Saunders (ELIXIR project coordinator)

##### Search

[Search](https://github.com/ga4gh-discovery/ga4gh-discovery-search) is an upcoming standard for searching of biomedical data with support for federation across organizational boundaries.

Contacts:

* Responsible Discovery co-chair: [Marc Fiume](/people/Marc-Fiume/)
* Product leads
    - [Miro Cupak](/people/Miro-Cupak/)
    - Aaron Kemp

##### Networks

Networks group works on a collection of standards enabling discovery of services. This currently includes 2 [__GA4GH approved standards__](https://www.ga4gh.org/genomic-data-toolkit/):

- [Service Registry](https://github.com/ga4gh-discovery/ga4gh-service-registry) - API specification for services providing information about other GA4GH services, primarily for the purpose of organizing services into networks or groups and service discovery across organizational boundaries.
- [Service Info](https://github.com/ga4gh-discovery/ga4gh-service-info) - API specification for services to advertise information about themselves.


Contacts:

* Responsible Discovery co-chair: [Marc Fiume](/people/Marc-Fiume/)
* Product leads
    - [Miro Cupak](/people/Miro-Cupak/)

##### {S}[B] SchemaBlocks

<img style="float: left; margin: 20px 20px 10px 0px; width: 60px; clear: none;" src="{{ "http://schemablocks.org/assets/img/logo-schemablocks-120x120-no-logo.png" | relative_url}}" />SchemaBlocks represents a __cross work stream, cross driver project__ initiative to document object standards and prototypes, as well as common data formats and semantics used throughout the GA4GH ecosystem. While products and implementation may be completely based on SchemaBlocks models, this project does not attempt to develop a rigid, complete schema but rather to provide the object vocabulary and semantics for a large range of developments.

More information about the _SchemaBlocks_ project as well as the current schema can be found on the project's site at [schemablocks.org](http://schemablocks.org).

* Responsible Discovery co-chair: [Michael Baudis](https://info.baudisgroup.org/group/Michael_Baudis/)
* Product leads:
    - Melanie Courtot
    - Michael Baudis


