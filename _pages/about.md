---
permalink: /
title: "Home Page"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am currently a PhD student in Computer Science at Zhejiang University under the supervision of [Prof. Yi Yang](https://scholar.google.com/citations?user=RMSuNFwAAAAJ&hl=zh-CN&oi=ao). Prior to that, I obtained the B.Sc Degree in Geographical Information Science from Zhejiang University in 2023.

**Email:** zechuan [at] zju.edu.cn




## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




