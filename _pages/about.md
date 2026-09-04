---
permalink: /
layout: home
title: false
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-section home-hero" id="about">
  <img class="home-hero__avatar" src="/images/profile.png" alt="Raphael Hwang">
  <div class="home-hero__bio">
    <h1>Raphael (Suk Min) Hwang</h1>
    <p>
      I am an undergraduate research intern at the Laboratory of Artificial Intelligence and Robotics at Sungkyunkwan University. My research focuses on 3D mapping and SLAM, particularly using Gaussian Splatting to represent dynamic environments. Currently, I'm working on continual learning methods that let these representations incorporate new observations over time without catastrophic forgetting.
    </p>
    <div class="home-hero__links">
      <a href="mailto:raph03@g.skku.edu"><i class="fas fa-envelope"></i> raph03@g.skku.edu</a>
      <a href="https://linkedin.com/in/raphaelhwang"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a href="https://github.com/flyingKangaroo1"><i class="fab fa-github"></i> GitHub</a>
    </div>
  </div>
</section>

<hr class="section-divider">

<section class="home-section" id="education" markdown="1">

## Education

**Sungkyunkwan University** · Suwon, South Korea · Expected March 2027  
B.Eng. in Mechanical Engineering & Computer Science and Engineering

</section>

<hr class="section-divider">

<section class="home-section" id="experience" markdown="1">

## Experience

**Research Intern** · LAIR Lab, Sungkyunkwan University · 2025 – Present

- Co-developed a range-adaptive scale initialization method for LiDAR Gaussian Splatting SLAM, scaling each Gaussian proportional to its range to compensate for LiDAR's fixed angular resolution, improving surface coverage at far range on sparse scan sequences
- Implemented a surface-reconstruction evaluation pipeline and benchmarked state-of-the-art SLAM methods (PIN-SLAM, Splat-LOAM, Voxblox, N3-Mapping) on real-world LiDAR datasets (Newer College, Oxford Spires)

**Leader, Autonomous Driving Team** · HEVEN Club, Sungkyunkwan University · 2024 – 2025

- Designed and implemented full-stack autonomous vehicle system (perception, planning, control) in ROS, C++, and Python
- Led team to 1st Place (2024) and 3rd Place (2025) at the national Autonomous Driving Robot Race

</section>

<hr class="section-divider">

<section class="home-section" id="publications">
<h2>Publications</h2>

{% for post in site.publications reversed %}
{% include pub-card.html %}
{% endfor %}

</section>

<hr class="section-divider">

<section class="home-section" id="projects">
<h2>Projects</h2>

{% assign sorted_projects = site.projects | sort: 'order' %}
{% for post in sorted_projects %}
{% include project-card.html %}
{% endfor %}

</section>

<hr class="section-divider">

<section class="home-section" id="honors" markdown="1">

## Honors & Awards

- **National Science & Technology Scholarship** (2025–2026), Ministry of Science and ICT - awarded to the
  top-ranked student in major during the first two years of study, full-tuition scholarship through graduation
- **Merit Scholarship** (2021–2025) - awarded to the top 4% of candidates
- **SKKU Chung Yong-ji Scholarship** (2026)
- **Entegris Foundation Scholarship** (2022)

</section>

<hr class="section-divider">

<section class="home-section" id="teaching" markdown="1">

## Teaching & Service

- **Teaching Assistant**, C Programming - DASF004
- **Instructor**, Republic of Korea Air Force MAICON Military AI Contest (2025) - trained officers and cadets on autonomous driving systems
- **Exhibitor**, SOLiDVUE at CES 2025 - demonstrated LiDAR sensor technology
- **SG Maple** (Global Mentoring & Assisting Exchange Students), SKKU
- **Interpreter**, Army Military Research Institute (2022–2024)

</section>
