---
title: "News"
layout: textlay
excerpt: "Dong Lab at UC Davis."
sitemap: false
permalink: /allnews.html
---

<h1>News</h1>

{% for article in site.data.news %}
<div class="news-item">
<div class="news-date">{{ article.date }}</div>
<div class="news-headline">{{ article.headline }}</div>
</div>
{% endfor %}
