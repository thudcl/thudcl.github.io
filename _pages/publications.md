---
title: "DCLab - Publications"
layout: gridlay
excerpt: "DCLab -- Publications."
sitemap: false
permalink: /publications/
---

# Publications

## Highlights

**For a full list see [below](#full-list)**

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

- Kaitlyn Webster, Priscilla Torres, Chong Chen, and Kyle Beardsley,  "[Ethnic and Gender Hierarchies in the Crucible of War](https://doi.org/10.1093/isq/sqaa031)," *International Studies Quarterly*, Online first, 2020, pp. 1-13.

- Chong Chen and Kyle Beardsley, "[Once and Future Peacemakers: Continuity of Third-party Involvement in Civil War Peace Processes](https://doi.org/10.1080/13533312.2020.1768074)," *International Peacekeeping*, Vol. 27, No. 4, 2020, pp.1-27. 

- Feng Liu, "[The Recalibrating of Chinese Assertiveness: China’s Responses to the Indo–Pacific Challenge](https://doi.org/10.1093/ia/iiz226),” *International Affairs*, Vol. 96, No. 1, 2020, pp. 9-27.

- Feng Liu and Ruonan Liu, “[China, the United States, and Order Transition in East Asia: An Economy-Security Nexus
Approach](https://doi.org/10.1080/09512748.2018.1526205),” *The Pacific Review*, Vol. 32, No. 6, 2019, pp. 972-995.

- Kaitlyn Webster, Chong Chen, and Kyle Beardsley, "[Conflict, Peace, and the Evolution of  Women's Empowerment](https://doi.org/10.1017/S0020818319000055)," *International Organization*, Vol. 73, No. 2, 2019, pp. 255-289. 

- Xun Pang and Shuai Wang, "[The International Political Significance of Chinese and US Foreign Aid: As Seen in United Nations
General Assembly Voting](https://doi.org/10.1080/02529203.2018.1414391)," *Social Sciences in China*, Vol.39, No.1, pp.5-33, 2018.

- Chong Chen, "[Territorial Dispute Initiation by Weaker States](https://doi.org/10.1093/cjip/poy009)," *The Chinese Journal of International Politics*, Vol. 11, No. 3, 2018, pp. 339-372. 

- Haixia Qi, "[Disputing Chinese Views on Power](https://doi.org/10.1093/cjip/pox005)," *The Chinese Journal of International Politics*, Vol. 10, No. 2, 2017, pp. 211–239.

- Qingqian He, "[Issue cross-pressures and time of voting decision](https://doi.org/10.1016/j.electstud.2016.08.017)," *Electoral Studies*, Vol. 44, 2016, pp. 362-373.

- Stephen Chaudoin, Helen V. Milner, and Xun Pang, "[International Systems and Domestic Politics: Linking Complex Interactions with Empirical Models in International Relations
](https://doi.org/10.1017/S0020818314000356)," *International Organization*, Vol. 69, No. 2, 2015, pp. 275-309. 

- Xun Pang, "[Varying Responses to Common Shocks and Complex Cross-Sectional Dependence: Dynamic Multilevel Modeling with Multifactor Error Structures for Time-Series Cross-Sectional Data](https://doi.org/10.1093/pan/mpu008),” *Political Analysis*, Vol. 22, Issue 4, 2014, pp.464-496.

- Xuetong Yan and Haixia Qi, "[Football Game Rather Than Boxing Match: China–US Intensifying Rivalry Does not Amount to Cold War](https://doi.org/10.1093/cjip/pos007)," *Chinese Journal of International Politics*, Vol.5, No, 2, 2012, pp. 105–127. 

- Xun Pang, Barry Friedman, Andrew D. Martin, and Kevin M. Quinn, "[Endogenous Jurisprudential Regimes](https://doi.org/10.1093/pan/mps024),” *Political Analysis*, Vol. 20, Issue 4, 2012, pp. 417-436.

- Xun Pang, "[Modeling Heterogeneity and Serial Correlation in Binary TSCS Data: A Bayesian Multilevel Model with AR(p) Errors](https://doi.org/10.1093/pan/mpq019),” *Political Analysis*, Vol. 18, Issue 4, 2010, pp. 470-498.

### Publications in Chinese

- Xun Pang and Chong Chen, "The Hirschman Effect of International Finance," *World Economics and Politics* (世界经济与政治), No. 6, 2020, pp. 132-155.

- Chong Chen and Xun Pang, "Predicting the Timing and Location of Terrorist Attacks in Africa in the Age of Big Data: Combing GIS and Split Population Duration Models,"  *Foreign Affairs Review* (外交评论), No. 2, 2020, pp. 121-154.

- Qingqian He and Daniel Naurin, "Brexit and Redistribution of EU Power: A Social Network Analysis Based on Survey Data," *Chinese Journal of European Studies*(欧洲研究)，No. 1, 2020, pp.27-54.

- Xuefeng Sun and Xikun Zhang, "China and US Strategic Choices and China's Relations with Its Neighbors," *Contemporary International Relations* (现代国际关系), Vol.29, No. 5, 2019, pp. 36-46.

- Xun Pang Ziye Liu, "China-US Relations In Massive Machine-Coded Event Data: Influence of Reciprocity, Domestic Politics,
and Russia ," *World Economic and Politics* (世界经济与政治), No.5, pp.53-79, 2019.

- Chong Chen, ”Rethinking Opportunity, Greed, Grievance and Internal Conflict: A Spatio-Temporal Analysis of African Political Violence," *World Economics and Politics* (世界经济与政治), No. 8, 2018, pp. 94-127.

- Haixia Qi, "Big Data and Innovation of International Relations Theory," *Social Science in China*(中国社会科学), No.6, 2018, pp.160-170.

- Qingqian He, "Cultural Resistance or Cultural Backlash? The Comparison of Causal Effects of the Rise of Populist Radical Right in Western Europe," *World Economics and Politics* (世界经济与政治)，NO.12, 2017, pp.103-131.    

- Haixia Qi and Hao Qi, "Alliance Signals, Audience Costs and Maritime Disputes of China-Japan and  China-Philippines," *World Economics and Politics* (世界经济与政治), Vol.8, 2017, pp.106-130.

- Xun Pang and Shuai Wang, “The International Political Implications of Chinese and American Foreign Aid: The Case of Voting in the United Nations General Assembly," *Social Sciences in China* (中国社会科学), No.3, pp.181-203, 2017.




