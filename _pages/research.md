---
title: "CVAMO Lab - Research"
layout: textlay
excerpt: "CVAMO Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Our experts are linked to the Faculty of Economics and Business Administration. They have a profound knowledge and insights in business and economics understanding engineering challenges. There are two main activities:

- Extraction and development of executable models incl. cost estimation for TCO elements of complex and dynamic environments, supported by mining techniques, data analytics and AI/machine learning capturing human system interaction/decision making.
- Robust cost-optimal decision making (stochastic optimisation) for manufacturing, intralogistics, supply chains and planning/scheduling under uncertainty.Develop and apply black boc machine (deep) learning tecniques, including machine learning and semantics to include expert knowledge to obtain interpretable outputs;

## Group highlights

(For a full list of publications and patents see [below](#full-list-of-publications) or go to [Google Scholar](https://scholar.google.ch/citations?user=TqxYWZsAAAAJ), [ResearcherID](https://www.researcherid.com/rid/D-7763-2012))

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

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

