---
title: 'Search API Moving Forward'
date: 2019-06-13
layout: default
author: "@Relequestual"
excerpt_separator: <!--more-->
excerpt_link: # an optional link to different page when clicking the excerpt
www_link: # a simple web address related to the post, e.g. https://www.ga4gh.org
www_links_formatted:  # one or multiple complete links
#  - '<a href="https://www.biorxiv.org" target="_blank">[biorXiv]</a>'
pdf_file_name: # the name of a PDF (no path) somewhere in "assets", which will be auto-linked
categories: # please adjust
  - search_api
  - news
tags: # please adjust
  - SearchAPI
  - roadmap
---

## {{ page.title }}

The _Search API_ project is working on a strategy to provide a release to replace the previous Matchmaker API and adding this functionality to other collaborating resources.

The project team is developping a spin-off project to facilitate a more limited but immediate use case of Case Discovery with a faster v1.0 release. Primary drivers include the _Matchmaker Exchange API (MME)_ group.

<!--more-->

The initial version of the Search API was developed over the course of last year, and demonstrated at the 2018 Basel plenary, but only covered a limited use case with consideration to expand later. In order to really fulfil the dream of a generalised search API for the "Internet of Genomics", there was a need to go back to a broader set of driver projects for a more indepth requirements elicitation phase.

Compared to this vision of an "Internet of Genomics" search environment, the MME group, and others, have demonstrated their need for _Single Sided Hypothesis Matching_, going back since before the 2016 Pleanry meeting in Vancouver. Recently, the Matchmaker Exchange group has expressed an _immediate need_ for a more flexible API than what they currently use, which would facilitate higher specificity and greater power to their users, while also being more interoperable across format evolution.

As a result of discussion among the GA4GH and Discovery Workstream leadership, it was agreed that a possible course forward would be to create a spin-off "Case Discovery API", which would aim to be complete much sooner than was feasable for a more generalised Search API

After further discussion with the Search API and MME group, it was agreed [[1]](https://docs.google.com/document/d/1sG--PPVlVWb1-_ZN7cHta79uU9tU2y-17U11PYzvMu8/edit#heading=h.v84nyj8m2qny) (2019-05-15) [[2]](https://docs.google.com/document/d/1sG--PPVlVWb1-_ZN7cHta79uU9tU2y-17U11PYzvMu8/edit#heading=h.qe0m2goag1ch) (2019-05-29) that a new API to facilitate a limited remit (case discovery) should still provide a benefit, ultimately looking to allow the end users of a system to construct the question they want to ask, as opposed to relying on unknown matching algorithms (like with MME V1). It is expected that the Case Discovery API will have close ties with the Search API, keeping in good communication throughout the development of both.

The Case Discovery API has been submitted for project approval to the GA4GH. In the submission, the aim is to have several live implementations and the specification be for the approval process around December 2019.

If you wish to be involved in the Case Discovery API, please contact Rishi Nag: [rishi.nag@ga4gh.org](mailto:rishi.nag@ga4gh.org).
(The project will use the same mailing list / google group for now.)

Project [Github](https://github.com/ga4gh-discovery/ga4gh-case-discovery)
