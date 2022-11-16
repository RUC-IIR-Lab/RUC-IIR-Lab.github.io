---
title: "IIR Lab - Publications"
layout: gridlay
excerpt: "IIR Lab -- Publications."
sitemap: false
permalink: /publications/
---


<!-- # Publications -->
# 论文列表

### 2022年:

{% for publi in site.data.publist_2022 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }}, </em> 
  <strong> {{ publi.book }} </strong>.
  [<a href="{{ publi.url }}">PDF</a>]

{% endfor %}

### 2021年：

{% for publi in site.data.publist_2021 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }}, </em> 
  <strong> {{ publi.book }} </strong>.
  [<a href="{{ publi.url }}">PDF</a>]

{% endfor %}

### 2020年：

{% for publi in site.data.publist_2020 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }}, </em> 
  <strong> {{ publi.book }} </strong>.
  [<a href="{{ publi.url }}">PDF</a>]

{% endfor %}

<!-- ## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a> -->


