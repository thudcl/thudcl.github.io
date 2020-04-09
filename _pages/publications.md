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

### Publications in English

- Kaitlyn Webster, **Chong Chen**, and Kyle Beardsley, "[Conflict, Peace, and the Evolution of  Women's Empowerment](https://doi.org/10.1017/S0020818319000055)," *International Organization*, Vol. 73, No. 2, 2019, pp. 255-289.   

- Stephen Chaudoin, Helen V. Milner, and **Xun Pang**, "[International Systems and Domestic Politics: Linking Complex Interactions with Empirical Models in International Relations
](https://doi.org/10.1017/S0020818314000356)," *International Organization*, Vol. 69, No. 2, 2015, pp. 275-309. 

- **Xun Pang**, "[Varying Responses to Common Shocks and Complex Cross-Sectional Dependence: Dynamic Multilevel Modeling with Multifactor Error Structures for Time-Series Cross-Sectional Data](https://doi.org/10.1093/pan/mpu008),” *Political Analysis*, Vol. 22, Issue 4, 2014, pp.464-496.

- **Xun Pang**, Barry Friedman, Andrew D. Martin, and Kevin M. Quinn, "[Endogenous Jurisprudential Regimes](https://doi.org/10.1093/pan/mps024),” *Political Analysis*, Vol. 20, Issue 4, 2012, pp. 417-436.

- **Xun Pang**, "[Modeling Heterogeneity and Serial Correlation in Binary TSCS Data: A Bayesian Multilevel Model with AR(p) Errors](https://doi.org/10.1093/pan/mpq019),” *Political Analysis*, Vol. 18, Issue 4, 2010, pp. 470-498.

### Publications in Chinese

- Chong Chen and Xun Pang,  "Predicting the Timing and Location of Terrorist Attacks in Africa in the Age of Big Data: Combing GIS and Split Population Duration Models,"  *Foreign Affairs Review* (外交评论), No. 2, 2020, pp. 82-115.

- Xun Pang Ziye Liu, "China-US Relations In Massive Machine-Coded Event Data: Influence of Reciprocity, Domestic Politics,
and Russia ," *World Economic and Politics* (世界经济与政治), No.5, pp.53-79, 2019.

- Chong Chen, ”Rethinking Opportunity, Greed, Grievance and Internal Conflict: A Spatio-Temporal Analysis of African Political Violence," *World Economics and Politics* (世界经济与政治), No. 8, 2018, pp. 94-127.

- Xun Pang and Shuai Wang, “The International Political Implications of Chinese and American Foreign Aid: The Case of Voting in the United Nations General Assembly," *Social Sciences in China* (中国社会科学), No.3, pp.181-203, 2017.


