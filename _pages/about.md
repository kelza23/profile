---
permalink: /
title: "Summary"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Fellow in Operations Analytics at the Institute for Intelligent Systems Research and Innovation (IISRI), Deakin University, Australia. I hold a PhD in engineering from Deakin University, and I specialise in developing optimisation algorithms and machine learning models for solving real-world problems. My passion is to drive innovation using Artificial Intelligence (AI) in complex transportation networks and human performance enhancement. I am interested in exploring opportunities for collaboration to further these areas of interest.

My Work and Research
======
As an engineering professional specialising in operations analytics, my role at IISRI, Deakin University, focuses on optimising complex transportation networks. My Doctor of Philosophy (Engineering) from Deakin University involved significant research in enhancing Integrated Operation Centres (IOCs) and developing advanced optimisation algorithms and machine learning models. Earlier, my professional path includes a role as a Student Engineer at the City of Greater Geelong, where I honed significant problem-solving skills. As a seasoned presenter, I have shared my findings at various national and international conferences.

My Extracurricular Activity
======
I have been promoted to Head Coach for the Victorian U22 team for 2023. My responsibilities include developing training programs, strategic planning for games, managing player performance, and ensuring a cohesive team environment. I am also an Ulti-mates Coach, promoting sportsmanship, inclusiveness, and the joy of Ultimate Frisbee among primary and secondary school children. I have received the Ellipsis Coaching Scholarship to further my coaching career in ultimate frisbee and have completed my UA Level 2 – Development Coach course. Additionally, I am an active player and treasurer of the Geelong Mudlarks Ultimate Frisbee Club and responsible for managing the club's financial operations. I am committed to high-level performance and teamwork, as reflected by my participation in the Australia Ultimate Championship. Notably, our club has achieved three consecutive championship victories in 2018, 2021, and 2022, underscoring our unwavering dedication and consistent success.

Blog Posts
======
{% for post in site.posts %}
  <div class="{{ include.type | default: "list" }}__item">
    <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
      <h2 class="archive__item-title" itemprop="headline">
        <a href="{{ post.url }}" rel="permalink">{{ post.title }}</a>
      </h2>
      <p class="page__date">
        <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
        <time datetime="{{ post.date | default: "1900-01-01" | date_to_xmlschema }}">{{ post.date | default: "1900-01-01" | date: "%B %d, %Y" }}</time>
      </p>
      <p class="archive__item-excerpt" itemprop="description">
        {{ post.excerpt | markdownify | remove: '<p>' | remove: '</p>' }}
        <strong><a href="{{ post.url }}" rel="permalink"> Read more</a></strong>
      </p>
    </article>
  </div>
{% endfor %}

