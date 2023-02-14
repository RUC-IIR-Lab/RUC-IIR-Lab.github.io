---
title: "IIR Lab - Jun Xu"
layout: default
excerpt: "IIR Lab: Jun Xu"
permalink: /team/junxu
---

<div style="height: 260px">

{% for member in site.data.teacher1 %}
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="" height="250" id="hp"/>
{% endfor %}
<h1><strong> 徐君</strong> </h1>
<h3>中国人民大学高瓴人工智能学院教授</h3>
<h4>研究方向：智能信息检索、大数据分析</h4>
<h4>联系方式: junxu@ruc.edu.cn</h4>
<h4>通信地址：北京市海淀区中关村大街59号中国人民大学信息楼 100872</h4>
<a href = "http://scholar.google.com/citations?user=su14mcEAAAAJ&hl=en">谷歌学术主页</a>&nbsp;&nbsp;&nbsp;<a href = "http://dblp.uni-trier.de/pers/hd/x/Xu_0001:Jun">DBLP</a>&nbsp;&nbsp;&nbsp;<a href="http://dl.acm.org/author_page.cfm?id=81423592460">ACM 主页</a>&nbsp;&nbsp;&nbsp;<a href="{{ site.url }}{{ site.baseurl }}/team/junxu_en.html">English Version</a>
</div>


## 简介

徐君曾就职于微软亚洲研究院、华为诺亚方舟实验室（香港）和中国科学院计算技术研究所，于2018年9月加入中国人民大学工作至今。在国内外学术会议或期刊上共发表论文100余篇，其中CCF-A类论文39篇，SCI收录14篇，近5年以主要作者身份发表论文30篇。谷歌学术统计论文总共被引用超7000次（近5年超4300次）、单篇最高引用超1000次、13篇论文引用达到100次、H-指数为35。论文合计SCI他引1255次，部分工作被欧美学者写入多本教科书、专著/手册，在课程中讲授。获发明专利授权12项，其中美国专利9项、PCT国际专利申请2项(已在多国授权)。
获ACM SIGIR 2019 Test of Time Award Honorable Mention、CIKM 2017 Best Full Paper Runner-up、CCIR 2022、AIRS 2010和ICMLC 2005最佳论文奖，获北京市自然科学奖二等奖（排名第2）。主持国家重点研发和国家自然科学基金面上项目。

## 教育背景

* 2001年 - 2006年 南开大学 博士
* 1997年 - 2001年 南开大学 本科

## 工作经历

* 2018年 - 至今 中国人民大学教授、博导，中国人民大学杰出学者特聘教授
* 2014年 - 2018年 中国科学院计算技术研究所 研究员、博导；中国科学院大学 岗位教授
* 2012年 - 2014年 华为（香港）诺亚方舟实验室 资深研究员
* 2006年 - 2012年 微软亚洲研究院 副研究员

## 学生要求
学生能力培养目标：

(1) 科学素养培养：理解基本科学观点和科学探究过程，认识科学技术对人类生活工作所产生的影响；

(2) 专业能力培养：培养学生的科学研究能力（论文阅读、工作调研、问题分析、方法设计、实验分析、论文写作等）、系统研发能力（编程、系统设计、项目管理），结合学生的特长和兴趣为学生制定不同的培养计划；

欢迎各位有意向攻读硕士或博士学位的同学报考！

## 科研项目
* 国家重点研发计划：面向多元化纠纷化解的智能法律助理和类案分析系统关键技术研究；主持
* 国家自然科学基金面上项目：基于强化学习的信息检索排序模型研究；主持
* 北京智源人工智能研究院智能信息检索与挖掘方向项目：交互式信息检索；主持
* 中国人民大学新教师启动项目：面向网络搜索的强化排序学习模型研究；主持
* 企业合作：主持多项企业委托项目，合作伙伴包括华为、阿里、腾讯、快手等
* 开源系统：大数据分析系统EasyML https://github.com/ICT-BDA/EasyML，创始人

## 学术成果精选


### 专著

Jun Xu, Xiangnan He and Hang Li. "**Deep Learning for Matching in Search and Recommendation**", Now Publishers, 2020. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/fntir20-DL4Match.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)
<br>
<a href="https://www.nowpublishers.com/article/Details/INR-076"><img src="{{ site.url }}{{ site.baseurl }}/images/DMRS.jpg" width="200" class="panel_cover_photo" /></a>
<br>

 Hang Li and Jun Xu. "**Semantic Matching in Search**", Now Publishers, 2014. (<a href="{{ site.url }}{{ site.baseurl }}/downloads/SemanticMatchingInSearch_2014.pdf">pdf</a>, <a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035">link</a>)
<br>
<a href="http://www.nowpublishers.com/articles/foundations-and-trends-in-information-retrieval/INR-035"><img src="{{ site.url }}{{ site.baseurl }}/images/SMSearch.jpg" width="200" class="panel_cover_photo" /></a>
<br>

### 论文

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