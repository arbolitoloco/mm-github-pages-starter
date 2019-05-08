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

## Interface

The UW portal has been extensively customized, to adhere to the University's design guidelines, improve usability, implement responsiveness to different screen sizes, and to promote accessibility.

However, the main structure of Symbiota has, in general, not been altered. Because the portal was developed to be an unified screenshot of several different databases, specimens and taxa are not being actively maintained through this interface. This means that administration tools that are useful in that portal are reduced to a few essentials. To simplify admin navigation, those tools have been collected in an extra page, available only for logged-in users, called "Site Tools". You should find those tools right next to the regular "Sitemap" link on the admin bar.

To change the content within the additional pages, please find the following archives:

- header.php (Header with menus)
- index.php (Home page)
- about.php (Footer)
- help.php (How to use this portal)
- map-search-info.php (Map search instructions)
- museums.php (Museums & Collections)
- sitetools.php (Admin Tools)
- trees.php (Biological and Non-biological trees)

The additional pages include disclaimers, general information, and guidance for users. As an admin, it is also your responsibility to change/update the content in those pages as necessary.