---
layout: page
permalink: /Publications/
title: Publications
description:
nav: true
nav_order: 2
sortby: true        # true: Sort by types | false: Sort by years
years: [2024, 2023, 2022, 2021, 2020, 2019]
sections:
  - bibquery: "@preprint"
    text: "Preprint articles"
  - bibquery: "@article"
    text: "Journal articles"
  - bibquery: "@book|@incollection"
    text: "Books and Book chapters"
  - bibquery: "@inproceedings"
    text: "Conference"
  - bibquery: "@misc|@thesis"
    text: "Thesis"
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

{% bibliography %}

</div>
