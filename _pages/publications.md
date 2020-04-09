---
title: "DCLab - Publications"
layout: gridlay
excerpt: "DCLab -- Publications."
sitemap: false
permalink: /publications/
---

# Publications

## Highlights

(For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.ch/citations?user=TqxYWZsAAAAJ), [ResearcherID](https://www.researcherid.com/rid/D-7763-2012))

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
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="40%" style="float: left" />
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


## Full List

- Kaitlyn Webster, Chong Chen, and Kyle Beardsley, "[Conflict, Peace, and the Evolution of  Women's Empowerment](https://doi.org/10.1017/S0020818319000055)," *International Organization*, Vol. 73, No. 2, 2019, pp. 255-289.   

- Stephen Chaudoin, Helen V. Milner, and Xun Pang, "[International Systems and Domestic Politics: Linking Complex Interactions with Empirical Models in International Relations
](https://doi.org/10.1017/S0020818314000356)," *International Organization*, Vol. 69, No. 2, 2015, pp. 275-309. 


