---
layout: default
title: UW-Madison Portal Specifics
parent: Symbiota Fundamentals
nav_order: 2
---

# UW-Madison Portal Specifics

The University of Wisconsin-Madison Natural History Museums Integrated Specimens Portal was built using Symbiota core version Symbiota-Light, and customized to accommodate some peculiarities inherent to its multidisciplinary caracter.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Scope

The University of Wisconsin-Madison Natural History Museums Council includes collections hosted in five different museums on campus, within different disciplines:

Museum | General Discipline
-------|-------------------
Anthropology | Department of Anthropology
Botany | Wisconsin State Herbarium
Entomology | Wisconsin Insect Research Collection
Geology | University of Wisconsin Geology Museum
Zoology | University of Wisconsin Zoological Museum

A summary of the subcollections and different datasets that are published in other sources is found [here](https://arbolitoloco.github.io/uw2020/docs/uw-biodiversity-data-mgmt/).

Customizations to the Symbiota's core were made to:

- Accommodate non-biological specimens (Anthropology and Geology)
- Update front-end styles (user interface) to match UW styles guidelines and accessibility standards

## Code

A brief list of code that has been customized in the back- and front-end:

- Support for non-biological taxonomic trees (tables `taxonunits`, `taxa`, `taxaenumtree`)
- Additional field added on the Advanced Search Method (field `objectRemarks`)
- Vernacular names support in Quick Search
- UW-Madison CSS styles
- Responsive styles
- Additional pages 