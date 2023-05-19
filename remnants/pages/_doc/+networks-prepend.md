---
layout: default
author: mbaudis
category:
  - networks
tags:
  - .prepend
  - .sticky
---

The Networks group meets every other Wednesday (11am ET) on a joint conference call with the Search group. Meeting minutes are available [here](https://docs.google.com/document/d/1p3xcXZeibYEf08i7XgjwSm8J5nNBF0PsMIvs3gWpKlU/edit) (archive [2019](https://docs.google.com/document/d/13K4ce05Vvcz7VU3uZnOPUNhvgtu2u2yeCKVnIJKgQBU/edit), [2018](https://docs.google.com/document/d/1xVXs-isSY_bX6uzUwuAX_L6qW7lKQAf8JZvZuXK6sTg/edit)).

The group works on a collection of standards enabling discovery of services. This currently includes 2 offcially approved standards:

## Service Registry

Service Registry is a service providing information about other GA4GH services, primarily for the purpose of organizing services into networks or groups and service discovery across organizational boundaries. It’s a minimalistic, simple, lightweight, read-only API for listing services and their metadata, as described by [service-info](#service-info).

The specification is available on GitHub: [ga4gh-discovery/ga4gh-service-registry](https://github.com/ga4gh-discovery/ga4gh-service-registry)
 
## Service Info

Service Info an API containing an endpoint for use by other GA4GH services to describe themselves. The API is designed for extension and inclusion in other APIs. Service info is used to describe a single service, while [Service Registry](#service-registry) is used to describe multiple services.

The specification is available on GitHub: [ga4gh-discovery/ga4gh-service-info](https://github.com/ga4gh-discovery/ga4gh-service-info)
