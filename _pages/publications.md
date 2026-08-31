---
layout: page
permalink: /publications/
title: Publication
description: Publications and arXiv preprints from our lab.
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

## Publications

<div class="publications">

{% bibliography --template simple_bib --query @*[status!=preprint] %}

</div>

## arXiv

<div class="publications">

{% bibliography --template simple_bib --query @*[status=preprint] %}

</div>
