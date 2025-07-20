---
title: "Dong Lab - Publications"
layout: gridlay
excerpt: "Dong Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications ([Google Scholar](https://scholar.google.com/citations?user=TF4dKPoAAAAJ&hl=en))

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
