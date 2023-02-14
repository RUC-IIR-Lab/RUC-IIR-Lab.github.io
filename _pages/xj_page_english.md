---
title: "IIR Lab - Jun Xu"
layout: default
excerpt: "IIR Lab: Jun Xu"
permalink: /team/junxu_en
---

<div style="height: 260px">

{% for member in site.data.teacher1 %}
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="" height="250" id="hp"/>
{% endfor %}
<h1><strong> Jun Xu</strong> </h1>
<h3>Position: Professor at Gaoling School of Artificial Intelligence, Renmin University of China</h3>
<h4>Rearch Interests：intelligent information retrieval and big data analysis</h4>
<h4>Email: junxu@ruc.edu.cn</h4>
<h4>Address: No. 59 Zhongguancun Street, Haidian District Beijing, 100872, China</h4>
<a href = "http://scholar.google.com/citations?user=su14mcEAAAAJ&hl=en">Google Scholar</a>&nbsp;&nbsp;&nbsp;<a href = "http://dblp.uni-trier.de/pers/hd/x/Xu_0001:Jun">DBLP</a>&nbsp;&nbsp;&nbsp;<a href="http://dl.acm.org/author_page.cfm?id=81423592460">ACM</a>&nbsp;&nbsp;&nbsp;<a href="{{ site.url }}{{ site.baseurl }}/team/junxu.html">中文主页</a>
</div>

## Short Bio

Jun Xu is a Professor at Gaoling School of Artificial Intelligence, Renmin University of China. He received his B.E. and Ph.D. in Computer Science from Nankai University, in 2001 and 2006, respectively. He worked as an associate researcher, researcher, and professor at Microsoft Research Asia, Huawei Noah's Ark Lab, and Institute of Computing Technology, Chinese Academy of Sciences. He joined Renmin University of China in Sep. 2018. His research interests focus on applying machine learning to information retrieval and recommendation. He has published more than 80 papers and 2 monographs at top international journals and conferences, including TKDE, TOIS, JMLR, FnTIR, SIGIR, CIKM, ACL, EMNLP etc. His work on information retrieval has received the Test of Time Award Honorable mention of ACM SIGIR 2019, Best Paper Runner-up of ACM CIKM 2017, and Best Paper Award of AIRS 2010. He has served or is serving top international conferences as Senior PC members, including SIGIR, ACML, CIKM, AAAI, and top international journal of JASIST as an editorial board member, and ACM TIST as an associate editor. He has given tutorials at top conferences like SIGIR, WSDM, TheWebConf (WWW) on the topic of deep learning for semantic matching in search and recommendation.

## Education


* Ph. D. in Computer Science, College of Information Science and Technology, Nankai University Tianjin, China, 2001 - 2006
* B. S. in Computer Science, College of Information Science and Technology, Nankai University Tianjin, China, 1997 - 2001

## Work Experience

* Professor, School of Information, Renmin University of China Beijing, China, 2018 -
* Researcher & Professor, Institute of Computing Technology, Chinese Academy of Sciences Beijing, China, 2014 - 2018
* Researcher and Senior Researcher, Noah's Ark Lab, Huawei Technologies Hong Kong SAR, China, 2012 - 2014
* Associate Researcher, Microsoft Research Asia (MSRA) Beijing, China, 2006 – 2012

## Research Interests

His research interests span the areas of intelligent information retrieval, recommender systems, and big data analysis. He has specific interests in reinforcement learning to rank, deep learning for semantic matching and relevance ranking, and casual inference in IR.


## Selected Publications


### Book

Jun Xu, Xiangnan He and Hang Li. "**Deep Learning for Matching in Search and Recommendation**", Now Publishers, 2020. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/fntir20-DL4Match.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)
<br>
<a href="https://www.nowpublishers.com/article/Details/INR-076"><img src="{{ site.url }}{{ site.baseurl }}/images/DMRS.jpg" width="200" class="panel_cover_photo" /></a>
<br>

 Hang Li and Jun Xu. "**Semantic Matching in Search**", Now Publishers, 2014. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/SemanticMatchingInSearch_2014.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)
<br>
<a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035"><img src="{{ site.url }}{{ site.baseurl }}/images/SMSearch.jpg" width="200" class="panel_cover_photo" /></a>
<br>

### Paper

#### 2023:

{% for publi in site.data.selected_pub_junxu %}

{% if publi.year == 2023 %}
  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.
  [<a href="{{ publi.url }}">PDF</a>]
{% endif %}

{% endfor %}


#### 2022:

{% for publi in site.data.selected_pub_junxu %}

{% if publi.year == 2022 %}
  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.
  [<a href="{{ publi.url }}">PDF</a>]
{% endif %}

{% endfor %}


#### 2021:

{% for publi in site.data.selected_pub_junxu %}

{% if publi.year == 2021 %}
  {{ publi.authors }}. {{ publi.title }}. <em>{{ publi.book }}</em>.
  [<a href="{{ publi.url }}">PDF</a>]
{% endif %}

{% endfor %}