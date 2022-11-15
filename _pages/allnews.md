---
title: "News"
layout: textlay
excerpt: "IIR Lab at RUC."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
* ***{{ article.date }}***
  * {{ article.headline | markdownify}}
{% endfor %}
