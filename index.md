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

Welcome to the homepage for the GA4GH Discovery Work Stream. We build standards for federated, secured networks of data and services, forming an “Internet of Genomics”, and asking meaningful questions across it.

The Discovery Work Stream is lead by Marc Fiume and Michael Baudis. For details on how this Work Stream operates please read the [Discovery Work Stream Organizational Structure & Vision document](https://docs.google.com/document/d/1WFjZ9yBx8Vxn97QORRNQN7O3DBnhpwEUX2mK7f2C4EA/edit?ts=59ed3535#).

This group meets at a high-level monthly. [Meeting minutes are available to view here](https://docs.google.com/document/d/1zrMC60S8GgyUaTdJtw9abDNeBqqtl1tw_znoichZm7A/edit?usp=sharing). In addition, the sub-groups listed below meet on their own schedules. Participation in these groups require participants to adhere to the [GA4GH Standards for Professional Conduct](https://www.ga4gh.org/docs/GA4GH-Standards-for-Professional-Conduct_22-Jan-2018.pdf).

For more information on GA4GH, please visit the [GA4GH Website](https://ga4gh.org).

### Products

Product development in GA4GH follows a process outlined in a [GA4GH Product Approval Process Guide, in draft](https://docs.google.com/document/d/1UUJSnsPw32W5r1jaJ0vI11X0LLLygpAC9TNosjSge_w/edit#heading=h.tyqycskyykwh). Products developed by the work stream undergo an initial investigation phase, followed by a formal Proposed Product Phase, in which most of the work is done, followed by an formal Approval Phase during which the products gain GA4GH Approval. The formal steps require the approval of the Work Stream leads.

The following products are currently under development for this Work Stream. 

##### Beacon API

<a href="http://beacon-project.io" target="_blank"><img style="float: right; width: 40px;" src="{{ '/assets/img/logo_beacon.png' | relative_url }}" />

A _Beacon_ is a federated, web-accessible service that can be queried for information about a specific genomic variant, e.g. a single nucleotide polymorphism (SNP/SNV) or a copy number variation (CNV), and reports about its existence in the queried resources. Future versions of the Beacon protocol will support different usage scenarios and offer the opportunity to link to the matched data using e.g. a [_handover_](https://beacon-project.io/roadmap/handover.html) scenario.

The Beacon API specification is now coordinated through the [ELIXIR Beacon project](http://beacon-project.io) and accessible there or directly trough its [repository](https://github.com/ga4gh-beacon/specification). 

##### Discovery Search API

The Discovery Search API aims at developing a component based approach towards the implementation of interfaces for genomic data and related information, for instance for global, federated data sharing through the querying, and subsequent optional processing of the results in a cloud environment. The in-development specification for the _Search API_ can be [accessed here](https://github.com/ga4gh-discovery/ga4gh-discovery-search-api).

##### Discovery Networks API

<a href="http://beacon-network.org" target="_blank"><img style="float: left; width: 161px;" src="{{ '/assets/img/BeaconNetwork.png' | relative_url }}" /></a>

The BeaconNetwork was the first successful implementation of an open, federated API for world-wide querying of genome resources. Current and future developments target especially the integration of user authentication for different access levels, extensions to the query language as provided through the emerging Beacon API and the evaluation of different topologies, especially with respect to security concerns.

<a href="http://beacon-project.io/network.html" target="_blank"><img style="float: right; width: 130px;" src="{{ '/assets/img/logo_beacon-network.png' | relative_url }}" />

Other aspects of the "networks" development address the identification of genomics resources ant their offered data content. The ELIXIR Beacon project focusses on the development of a Beacon network across [ELIXIR](https://www.elixir-europe.org) nodes, utilising the ELIXIR AAI.

##### SchemaBlocks

SchemaBlocks represents a cross work stream, cross driver project attempt to document object standards and prototypes, as well as common data formats and semantics. While products and implementation may be completely based on SchemaBlocks models, this project does not attempt to develop a rigid, complete schema but rather to provide the object vocabulary and semantics for a large range of developments.

The SchemaBlocks site can be accessed though the permanent link [schemablocks.org](http://schemablocks.org).


