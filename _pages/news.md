---
title: "News Archive - QSMol"
layout: textlay
excerpt: "News Archive - QSMol"
sitemap: false
permalink: /news.html
---

# News

{% for article in site.data.news %}
<p>**{{ article.date }}** <br> {{ article.headline | markdownify | remove: '<p>' | remove: '</p>' }}</p>
{% endfor %}
