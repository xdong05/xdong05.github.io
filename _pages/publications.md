---
title: "Dong Lab - Publications"
layout: gridlay
excerpt: "Dong Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Highlights

**The [full list of publications](#full-list-of-publications) is at the end of the page and on [Google Scholar](https://scholar.google.com/citations?user=TF4dKPoAAAAJ&hl=en).**

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


## Full List of publications

{% assign pubs_with_years = site.data.publist %}

{% comment %}
Extract years and sort publications descending by year
{% endcomment %}
{% assign pubs_sorted = pubs_with_years | sort: "link.display" | reverse %}
{% assign all_years = pubs_sorted | map: "link.display" | map: "split: '('" | map: "last" | map: "replace: ')', ''" | uniq | sort | reverse %}

{% for y in all_years %}
  <h3 style="margin-top: 30px;"><strong>{{ y }}</strong></h3>

  {% for publi in pubs_sorted %}
    {% assign year = publi.link.display | split: '(' | last | replace: ')', '' %}
    {% if year == y %}
      <p>
        <strong>{{ publi.title | remove: '<b>' | remove: '</b>' }}</strong><br />
        <em>{{ publi.authors }}</em><br />
        <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
      </p>
    {% endif %}
  {% endfor %}

{% endfor %}


