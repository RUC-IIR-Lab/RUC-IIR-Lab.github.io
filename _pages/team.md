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

<div class="box2 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="24%" style="float: left" />
  <h4><strong> {{ member.name }}</strong> </h4>
  <h5>{{ member.position }}</h5>
  <i>{{ member.info }}   <br>email: <{{ member.email }}> <br>{{ member.intro }} 


  <h6> 更多信息: {{ member.google_scholar }}、{{ member.homepage }}</h6>

</div>

{% endfor %} 

{% for member in site.data.teacher2 %}

<div class="box2 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="20%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5>{{ member.position }}</h5>
  <i>{{ member.info }}   <br>email: <{{ member.email }}> <br>{{ member.intro }} 


  <h6> 更多信息: {{ member.google_scholar }}、{{ member.homepage }}</h6>

</div>

{% endfor %} 

**期待勤奋、踏实、认真的同学了解和加入本课题组，我们长期欢迎各位同学申请博士研究生、硕士研究生和博士后。**

点击[“联系我们”]({{ site.url }}{{ site.baseurl }}/contact) 了解更多 **!**
<!-- **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/contact) **!** -->

## 博士生

{% assign number_printed = 0 %}
{% for member in site.data.team_members_phd %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {% if member.placeholder != 1 %}
  <i>研究方向：{{ member.info }} <br> email：{{ member.email }} <br> homepage：{{ member.homepage }}</i>
  {% endif %}
  
  {% if member.placeholder == 1 %}
  <i>{{ member.info }}</i>
  {% endif %}
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

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {% if member.placeholder != 1 %}
  <i>研究方向：{{ member.info }} <br> email：{{ member.email }} <br> homepage：{{ member.homepage }}</i>
  {% endif %}
  
  {% if member.placeholder == 1 %}
  <i>{{ member.info }}</i>
  {% endif %}
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





## 毕业生
<div class="row">

<h4>博士生</h4>
{% for member in site.data.alumni_phd %}
{{ member.name }}  ({{ member.quxiang}})
{% endfor %}

<!-- <div class="col-sm-4 clearfix"> -->
<h4>硕士生</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}  ({{ member.quxiang}})
{% endfor %}
<!-- </div> -->


</div>


