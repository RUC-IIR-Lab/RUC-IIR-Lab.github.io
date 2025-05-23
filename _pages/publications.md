---
title: "IIR Lab - Publications"
layout: gridlay
excerpt: "IIR Lab -- Publications."
sitemap: false
permalink: /publications/
---

下面分别展示了已经发表的[专著](#专著)、[论文](#论文列表)和[学术报告](#学术报告)。

<!-- # Publications -->
# 教科书
文继荣，徐君。 "**人工智能与Python程序设计（新编21世纪人工智能系列教材）**", 中国人民大学出版社, 2024. 
<br>
<a href=""><img src="{{ site.url }}{{ site.baseurl }}/images/python.png" width="200" class="panel_cover_photo" /></a>
<br>

# 专著
Jun Xu, Xiangnan He and Hang Li. "**Deep Learning for Matching in Search and Recommendation**", Now Publishers, 2020. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/fntir20-DL4Match.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)

（中文译本）徐君, 何向南, 李航. "**深度匹配学习：面向搜索与推荐**", 人民邮电出版社, 2023. 

<br>
<a href="https://www.nowpublishers.com/article/Details/INR-076"><img src="{{ site.url }}{{ site.baseurl }}/images/DMRS.jpg" width="200" class="panel_cover_photo" /></a>
<a href=""><img src="{{ site.url }}{{ site.baseurl }}/images/match_zh.png" width="200" class="panel_cover_photo" /></a>
<br>


 Hang Li and Jun Xu. "**Semantic Matching in Search**", Now Publishers, 2014. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/SemanticMatchingInSearch_2014.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)
<br>
<a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035"><img src="{{ site.url }}{{ site.baseurl }}/images/SMSearch.jpg" width="200" class="panel_cover_photo" /></a>
<br>

# 论文

### 2024:

{% for publi in site.data.publist_2024 %}

  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.{% if publi.url != 'pad' %} [<a href="{{ publi.url }}">PDF</a>] {% endif %} {% if publi.url == 'pad' %}[Just Accepted] {% endif %}
  

{% endfor %}

### 2023:

{% for publi in site.data.publist_2023 %}

  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.{% if publi.url != 'pad' %} [<a href="{{ publi.url }}">PDF</a>] {% endif %} {% if publi.url == 'pad' %}[Just Accepted] {% endif %}
  

{% endfor %}

### 2022:

{% for publi in site.data.publist_2022 %}

  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.
  [<a href="{{ publi.url }}">PDF</a>]

{% endfor %}

### 2021：

{% for publi in site.data.publist_2021 %}

  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.
  [<a href="{{ publi.url }}">PDF</a>]

{% endfor %}

### 2020：

{% for publi in site.data.publist_2020 %}

  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.
  [<a href="{{ publi.url }}">PDF</a>]

{% endfor %}

### 2019：

{% for publi in site.data.publist_2019 %}

  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.
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
