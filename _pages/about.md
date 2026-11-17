---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<img src="./images/yukai_JMPphoto.jpg" alt="Yukai Huang's Profile Picture" width="200" height="300" style="float: left; margin-right: 10px;">

I am Yukai Huang, an Assistant Professor in the Information Systems and Operations Management department at Suffolk University.

I received my Ph.D. in Supply Chain, Operations, and Technology from the Olin Business School at Washington University in St. Louis, where I was fortunate to be advised by Professor Jacob Feldman.

My research interests lie in revenue management, dynamic resource allocation, online assortment optimization, and approximate algorithms. My work focuses on developing innovative frameworks that address complex challenges in these areas, with the aim of advancing both theoretical understanding and practical applications.

I also hold a Master's degree in Statistics and Operations Research from the University of North Carolina, Chapel Hill, and a Bachelor's degree in Applied Mathematics from Shanghai Jiaotong University.

Please feel free to explore my website to learn more about my research and teaching. I am always open to discussions and collaborations, so don't hesitate to reach out!

## Research

<ul>
{% assign research_order = "publication,under_review,working_paper" | split: "," %}
{% for status in research_order %}
  {% assign papers = site.portfolio | where: "research_status", status %}
  {% for paper in papers %}
    <li>
      {{ paper.title | escape }}.
      {{ paper.status_label | escape }}
      {% if paper.preprint_url %}
        <a href="{{ paper.preprint_url | escape }}">{{ paper.preprint_label | escape }}</a>
      {% endif %}
    </li>
  {% endfor %}
{% endfor %}
</ul>

## Teaching

<ul>
{% for course in site.teaching reversed %}
  <li><a href="{{ course.url | relative_url }}">{{ course.title | escape }}</a></li>
{% endfor %}
</ul>

## Service

I serve as a reviewer for *Manufacturing & Service Operations Management* (MSOM), *Production and Operations Management*, and *Operations Research*.

