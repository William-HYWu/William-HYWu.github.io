---
permalink: /
title: "Haoyang Wu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm Haoyang Wu, a junior CS major student at the University of Michigan. I'm also pursuing a dual degree in Mechanical Engineering at Shanghai Jiao Tong University (SJTU), expected to graduate in 2027.

Previously at SJTU, I'm passionate about the medical imaging and worked as a research assistant at the [SIRIUS Lab](https://banyutong.github.io/sirius_lab_website/index.html#research) under the guidance of Prof. [Yutong Ban](https://people.csail.mit.edu/yban/). Currently, I am working to broaden my research experience in computer vision, with a focus on areas such as video representation, 3D/4D vision, and robotic perception.

**I am actively seeking research opportunities of all kinds, including remote collaborations. Please feel free to reach out if you'd like to connect or discuss potential projects!**

# Publications

{% if site.publication_category %}
{% for category in site.publication_category  %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.category != category[0] %}
{% continue %}
{% endif %}
{% include archive-mainpage.html %}
{% endfor %}
{% endfor %}
{% endif %}