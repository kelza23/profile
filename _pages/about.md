---
permalink: /
title: "Summary"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Fellow in Operations Analytics at the Institute for Intelligent Systems Research and Innovation (IISRI), Deakin University, Australia. I hold a PhD in engineering from Deakin University, and I specialize in developing optimisation algorithms and machine learning models for solving real-world problems. My passion is to drive innovation using Artificial Intelligence (AI) in complex transportation networks and human performance enhancement. I am interested in exploring opportunities for collaboration to further these areas of interest.

My Work and Research
======
As an engineering professional specialising in operations analytics, my role at IISRI, Deakin University, focuses on optimising complex transportation networks. My Doctor of Philosophy (Engineering) from Deakin University involved significant research in enhancing Integrated Operation Centres (IOCs) and developing advanced optimisation algorithms and machine learning models. Earlier, my professional path includes a role as a Student Engineer at the City of Greater Geelong, where I honed significant problem-solving skills. As a seasoned presenter, I have shared my findings at various national and international conferences.

Blog Posts
======
  <ul>{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}</ul>