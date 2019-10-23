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


##### Discovery Search API

The Discovery Search API aims at developing a component based approach towards the implementation of interfaces for genomic data and related information, for instance for global, federated data sharing through the querying, and subsequent optional processing of the results in a cloud environment. The in-development specification for the _Search API_ can be [accessed here](https://github.com/ga4gh-discovery/ga4gh-discovery-search-api).

* Responsible Discovery co-chair: [Marc Fiume](https://oicr.on.ca/investigators/marc-fiume/)


##### Discovery Networks

The work of the "networks" group addresses several areas:

* [Tool Registry Service](https://github.com/ga4gh/tool-registry-service-schemas)
* [Service Registry](https://github.com/ga4gh-discovery/ga4gh-service-registry/) (called _Networks_)
* [Beacon Network](https://beacon-network.org/) (search engine on top of the Beacon protocol)

<a href="http://beacon-network.org" target="_blank"><img style="float: left; width: 161px;" src="{{ '/assets/img/BeaconNetwork.png' | relative_url }}" /></a>BeaconNetwork was the first successful implementation of an open, federated API for world-wide querying of genome resources. Current and future developments target especially the integration of user authentication for different access levels, extensions to the query language as provided through the emerging Beacon API and the evaluation of different topologies, especially with respect to security concerns.

<a href="http://beacon-project.io/network.html" target="_blank"><img style="float: right; width: 130px;" src="{{ '/assets/img/logo_beacon-network.png' | relative_url }}" /></a>Other aspects of the "networks" development address the identification of genomics resources ant their offered data content. The ELIXIR Beacon project focusses on the development of a Beacon network across [ELIXIR](https://www.elixir-europe.org) nodes, utilising the ELIXIR AAI.

* Responsible Discovery co-chair: [Marc Fiume](https://oicr.on.ca/investigators/marc-fiume/)
* Project leads
    - Miro Cupak
    - Juha Törnroos (for the ELIXIR networks implementation)

##### {S}[B] SchemaBlocks

<img style="float: left; margin: 20px 20px 10px 0px; width: 60px; clear: none;" src="{{ "http://schemablocks.org/assets/img/logo-schemablocks-120x120-no-logo.png" | relative_url}}" />SchemaBlocks represents a __cross work stream, cross driver project__ initiative to document object standards and prototypes, as well as common data formats and semantics used throughout the GA4GH ecosystem. While products and implementation may be completely based on SchemaBlocks models, this project does not attempt to develop a rigid, complete schema but rather to provide the object vocabulary and semantics for a large range of developments.

More information about the _SchemaBlocks_ project as well as the current schema can be found on the project's site at [schemablocks.org](http://schemablocks.org).

* Responsible Discovery co-chair: [Michael Baudis](https://info.baudisgroup.org/group/Michael_Baudis/)
* Project leads:
    - Jordi Rambla


