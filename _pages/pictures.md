---
title: "IIR Lab - Pictures"
layout: piclay
excerpt: "IIR Lab -- Pictures"
permalink: /pictures/
---


# Gallery

(右键点击“查看图片”可以浏览大图)
<!-- (Right-click *'view image'* to see a larger image.) -->

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_TJ %}

{% assign even_odd = number_printed | modulo: 3 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 3 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

<!-- {% if even_odd == 3 %}
</div>
{% endif %} -->

<p> &nbsp; </p>

