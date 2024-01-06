---
permalink: /
title: "About Me"
excerpt: "Summary"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently working as a Research Fellow in Operations Analytics at the Institute for Intelligent Systems Research and Innovation (IISRI) at Deakin University, in Australia. My research is focused on decision support systems, optimisation, and machine learning. I am passionate about using these tools to solve complex problems related to transportation networks, and my goal is to create innovative solutions that can help human decision-makers make better decisions. In the future, I am excited to explore new frontiers in decision support systems, particularly in the area of complex transportation systems, decision support systems and human performance enhancement.

# My Work and Research  
Throughout my academic and research journey, I have experienced a constant evolution in my focus, showcasing my adaptability and unwavering commitment to expanding the frontiers of knowledge.

**Doctor of Philosophy (Engineering), Deakin University:**  
My initial research focused on developing decision support systems for complex transportation networks, emphasising optimisation and machine learning techniques. This foundational experience has enriched my understanding of data-driven solutions.

**Current Research Endeavors:**  
In my recent research, I delved into multifaceted domains that encompass biomechanical analysis and computer vision, prompting me to fuse decision support systems with machine learning and deep learning.

**Sports Analytics:**  
I am currently working on some side projects that use computer vision to extract useful information from sports data. This helps me improve coaching strategies and assess player performance. As the Head Coach for the Victorian U22 team, I use data-driven techniques to develop training programs, plan games strategically, and manage player performance effectively.

**Future Exploration:**  
As I move forward in my academic and professional journey, I am motivated by my passion for exploring the cutting-edge of artificial intelligence in the fields of sports analytics, coaching science, and human performance enhancement. My research path is a reflection of my commitment to unlocking human potential through data-driven innovations.

# My Extracurricular Activity  
I am involved in extracurricular activities that go beyond academics. These activities allow me to channel my passion for sports and coaching into initiatives that have a positive impact.

**Active Player & Treasurer - Geelong Mudlarks Ultimate Frisbee Club:**  
As the treasurer of the Geelong Mudlarks Ultimate Frisbee Club, I am responsible for managing the club's finances. This role has helped me develop my administrative skills and strengthened my commitment to the Ultimate Frisbee community. Being an active player, I have played a crucial role in the club's success, which includes three consecutive championship victories in 2018, 2021, and 2022. This showcases our unwavering dedication to teamwork and high-level performance.

**Head Coach - Victorian U22 Team (2023):**  
I am excited to share that I have been selected as the Head Coach for the Victorian U22 team in 2023. As Head Coach, my responsibilities include developing comprehensive training programs, devising strategic game plans, managing player performance, and fostering a cohesive team environment. This leadership role reflects my passion for sports coaching and my commitment to enhancing human performance.

**Ulti-mates Coach:**  
I was an Ulti-mates Coach, and my primary objective is to promote the values of sportsmanship, inclusiveness, and the joy of playing Ultimate Frisbee among primary and secondary school children. My coaching approach is focused on instilling a passion for sports and teamwork in the younger generation.

**Ellipsis Coaching Scholarship:**  
I was awarded the prestigious Ellipsis Coaching Scholarship, which has helped me develop my coaching skills and connect with top-notch Ultimate Frisbee coaches. This scholarship reflects my commitment to continuous improvement in coaching and mentoring.

**Ultimate Australia Level 2 - Development Coach:**  
I have successfully completed the UA Level 2 - Development Coach course, further enhancing my coaching capabilities and qualifications.

# Blog Posts  
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

