---
title: "News"
layout: textlay
excerpt: "Dong Lab at UC Davis."
sitemap: false
permalink: /allnews.html
---

<h1>News</h1>

{% for article in site.data.news %}
<p class="news-date">{{ article.date }}</p>
<p class="news-headline">{{ article.headline }}</p>
{% endfor %}
