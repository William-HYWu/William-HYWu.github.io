---
layout: academic
title: CV
permalink: /cv/
description: Education, research, and academic experience.
nav: false
nav_order: 4
---

<div class="cv-toolbar">
  <p><a href="mailto:{{ site.data.socials.email }}">{{ site.data.socials.email }}</a></p>
  <a class="download-link" href="{{ '/assets/pdf/Resume_Haoyang_Wu.pdf' | relative_url }}" download>Download PDF ↓</a>
</div>

<section class="cv-section" aria-labelledby="cv-education">
  <h2 id="cv-education">Education</h2>
  <div class="cv-entries">
    <article class="cv-entry">
      <div class="cv-entry-heading"><h3>University of Michigan</h3><span class="cv-date">Aug 2025 – May 2027 (expected)</span></div>
      <p>B.S.E. in Computer Science</p>
      <p class="cv-detail">GPA: 3.97 / 4.0</p>
    </article>
    <article class="cv-entry">
      <div class="cv-entry-heading"><h3>Shanghai Jiao Tong University</h3><span class="cv-date">Aug 2023 – Aug 2027 (expected)</span></div>
      <p>B.E. in Electrical and Computer Engineering</p>
      <p class="cv-detail">GPA: 3.97 / 4.0 · Rank: 1 / 336</p>
    </article>
  </div>
</section>

<section class="cv-section" aria-labelledby="cv-research">
  <h2 id="cv-research">Research experience</h2>
  <div class="cv-entries">
    <article class="cv-entry">
      <div class="cv-entry-heading"><h3>Princeton University</h3><span class="cv-date">Jan 2026 – Present</span></div>
      <p>Research Intern · Z Lab</p>
      <p class="cv-detail">Advised by <a href="https://liuzhuang13.github.io">Prof. Zhuang Liu</a></p>
    </article>
    <article class="cv-entry">
      <div class="cv-entry-heading"><h3>University of Michigan</h3><span class="cv-date">Sep 2025 – Present</span></div>
      <p>Research Intern · <a href="https://arm.robotics.umich.edu">ARM Lab</a></p>
      <p class="cv-detail">Advised by <a href="https://berenson.robotics.umich.edu">Prof. Dmitry Berenson</a></p>
    </article>
    <article class="cv-entry">
      <div class="cv-entry-heading"><h3>Shanghai Jiao Tong University</h3><span class="cv-date">Jan 2024 – Sep 2025</span></div>
      <p>Research Intern · <a href="https://banyutong.github.io/sirius_lab_website/">SIRIUS Lab</a></p>
      <p class="cv-detail">Mentored by <a href="https://people.csail.mit.edu/yban/">Prof. Yutong Ban</a></p>
    </article>
  </div>
</section>

<section class="cv-section" aria-labelledby="cv-publications">
  <h2 id="cv-publications">Publications</h2>
  <div class="cv-publications">
    {% bibliography --template cv-paper --group_by none %}
  </div>
</section>

<section class="cv-section" aria-labelledby="cv-awards">
  <h2 id="cv-awards">Honors &amp; awards</h2>
  <ul class="cv-awards">
    <li><span>Dean’s Honor List</span><span class="cv-date">Jan 2026</span></li>
    <li><span>2024–2025 National Undergraduate Scholarship</span><span class="cv-date">Sep 2025</span></li>
    <li><span>Tang Jun Yuan Scholarship</span><span class="cv-date">Jul 2025</span></li>
    <li><span>Shanghai Jiao Tong University First Class Scholarship</span><span class="cv-date">Dec 2024</span></li>
    <li><span>John Wu and Jane Sun Sunshine Scholarship</span><span class="cv-date">Nov 2024</span></li>
    <li><span>2023–2024 National Undergraduate Scholarship</span><span class="cv-date">Sep 2024</span></li>
  </ul>
</section>

<section class="cv-section" aria-labelledby="cv-teaching">
  <h2 id="cv-teaching">Teaching &amp; advising</h2>
  <div class="cv-entries">
    <article class="cv-entry">
      <div class="cv-entry-heading"><h3>Teaching Assistant</h3><span class="cv-date">2024–2025</span></div>
      <p>Shanghai Jiao Tong University</p>
      <ul class="cv-courses">
        <li>ECE2810J · Advanced Data Structures and Algorithms (2025)</li>
        <li>ECE2800J · Programming and Elementary Data Structures (2025)</li>
        <li>ENGL1000J · Academic Writing I (2024)</li>
      </ul>
    </article>
    <article class="cv-entry">
      <div class="cv-entry-heading"><h3>Academic Advisor</h3><span class="cv-date">2024</span></div>
      <p>UM–SJTU Joint Institute Advising Center</p>
    </article>
  </div>
</section>
