---
title: "IIR Lab - Team"
layout: gridlay
excerpt: "IIR Lab: Team members"
sitemap: false
permalink: /team/
---

# 人员介绍

## 教师

{% for member in site.data.teacher1 %}
<div class="box2" style="overflow: hidden; margin-bottom: 30px;">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" style="float: left; width: 150px; height: 200px; object-fit: cover; object-position: top; margin-right: 20px;" />
<div style="overflow: hidden;">
<h4><strong>{{ member.name }}</strong></h4>
<h5>{{ member.position }}</h5>
{{ member.info }}<br>
email: {{ member.email }}<br>
{{ member.intro }}<br>
<h6>更多信息: {{ member.google_scholar }}、{{ member.homepage }}</h6>
</div>
</div>
{% endfor %}
{% for member in site.data.teacher2 %}
<div class="box2" style="overflow: hidden; margin-bottom: 30px;">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" style="float: left; width: 150px; height: 200px; object-fit: cover; object-position: top; margin-right: 20px;" />
<div style="overflow: hidden;">
<h4><strong>{{ member.name }}</strong></h4>
<h5>{{ member.position }}</h5>
{{ member.info }}<br>
email: {{ member.email }}<br>
{{ member.intro }}<br>
<h6>更多信息: {{ member.google_scholar }}、{{ member.homepage }}</h6>
</div>
</div>
{% endfor %}

**期待勤奋、踏实、认真的同学了解和加入本课题组，我们长期欢迎各位同学申请博士研究生、硕士研究生和博士后。**

点击["联系我们"]({{ site.url }}{{ site.baseurl }}/contact) 了解更多 **!**

## 博士生

{% assign number_printed = 0 %}
{% for member in site.data.team_members_phd %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6" style="overflow: hidden; margin-bottom: 20px;">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" style="float: left; width: 90px; height: 100px; object-fit: cover; object-position: top; margin-right: 12px;" />
<div style="overflow: hidden;">
<h4 style="margin-top:0;">{{ member.name }}</h4>
{% if member.placeholder != 1 %}
<i>研究方向：{{ member.info }}<br>email：{{ member.email }}<br>homepage：{{ member.homepage }}</i>
{% else %}
<i>{{ member.info }}</i>
{% endif %}
</div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## 硕士生

{% assign number_printed = 0 %}
{% for member in site.data.team_members_msc %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6" style="overflow: hidden; margin-bottom: 20px;">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" style="float: left; width: 90px; height: 100px; object-fit: cover; object-position: top; margin-right: 12px;" />
<div style="overflow: hidden;">
<h4 style="margin-top:0;">{{ member.name }}</h4>
{% if member.placeholder != 1 %}
<i>研究方向：{{ member.info }}<br>email：{{ member.email }}<br>homepage：{{ member.homepage }}</i>
{% else %}
<i>{{ member.info }}</i>
{% endif %}
</div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## 毕业去向

指导（包括联合指导）毕业的学生及去向：

### 毕业博士

{% for member in site.data.alumni_phd %}
* {{ member.name }}（{{ member.quxiang }}）
{% endfor %}

### 毕业硕士

{% for member in site.data.alumni_msc %}
* {{ member.name }}（{{ member.quxiang }}）
{% endfor %}
