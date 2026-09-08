---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 1
---

<div class="float-right" style="margin-top: -3.5rem;">
  <a href="{{ '/assets/pdf/jira_publications.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" title="Download Publications PDF">
    <i class="fa-solid fa-file-pdf fa-2xl"></i>
  </a>
</div>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
