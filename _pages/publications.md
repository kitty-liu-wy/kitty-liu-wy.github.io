---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<p> 
This page lists my research output. Please email me if you would like a copy of anything that isn't already linked!
</p>

<ul>
    <li><a href="#articles"><b>peer-reviewed journal articles</b></a></li>
    <li><a href="#proceedings"><b>conference proceedings</b></a></li>
    <li><a href="#corpora"><b>corpus materials</b></a></li>
    <li><a href="#reviewed_presentations"><b>peer-reviewed presentations</b></a></li>
    <li><a href="#invited_talks"><b>invited talks</b></a></li>
    <li><a href="#theses"><b>theses</b></a></li>
</ul>


<div class="publications">


<h3 id="articles" style="margin-top: 4.5rem; margin-bottom: -1rem;">
  peer-reviewed articles
</h3>
<!-- adding in the following manually codes in a divider under the heading
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;"> 
-->
{% bibliography -f articles %}

<h3 id="proceedings" style="margin-top: 4.5rem; margin-bottom: -1rem;">
    conference proceedings
</h3>
{% bibliography -f proceedings %}

<h3 id="corpora" style="margin-top: 4.5rem; margin-bottom: -1rem;">
    corpus materials
</h3>
{% bibliography -f corpora %}

<h3 id="reviewed_presentations" style="margin-top: 4.5rem; margin-bottom: -1rem;">
    peer-reviewed presentations
</h3>
  {% bibliography -f reviewed_presentations %}

  <h3 id="invited_talks" style="margin-top: 4.5rem; margin-bottom: -1rem;">
    invited talks
</h3>
{% bibliography -f invited_talks %}

<h3 id="theses" style="margin-top: 4.5rem; margin-bottom: -1rem;">
    theses
</h3>
{% bibliography -f theses %}

</div>
