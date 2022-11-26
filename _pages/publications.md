---
title: "IIR Lab - Publications"
layout: gridlay
excerpt: "IIR Lab -- Publications."
sitemap: false
permalink: /publications/
---

下面分别展示了已经发表的[专著](#专著)、[论文](#论文列表)和[学术报告](#学术报告)。

<!-- # Publications -->
# 专著

"**Deep Learning for Matching in Search and Recommendation**" by Jun Xu, Xiangnan He and Hang Li, Now Publishers, 2020. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/fntir20-DL4Match.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)
<br>
<a href="https://www.nowpublishers.com/article/Details/INR-076"><img src="{{ site.url }}{{ site.baseurl }}/images/DMRS.jpg" width="200" class="panel_cover_photo" /></a>
<br>

"**Semantic Matching in Search**" by Hang Li and Jun Xu, Now Publishers, 2014. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/SemanticMatchingInSearch_2014.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)
<br>
<a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035"><img src="{{ site.url }}{{ site.baseurl }}/images/SMSearch.jpg" width="200" class="panel_cover_photo" /></a>
<br>

# 论文

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



# 学术报告

{% for publi in site.data.talks %}

  "{{ publi.title }}" <br />
  <em> {{ publi.authors}} </em>, 
  {{ publi.content }}. 
  {% if publi.links != 'placeholder' %} ({{publi.links}}).{% endif %}

{% endfor %}
