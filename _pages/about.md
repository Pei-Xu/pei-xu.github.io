---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I will work as a research assistant professor at Clemson University since August. My research interests includes artificial intelligence, computer graphics, and computer vision with a focus on motion planning and reinforcement learning for physically-based character control and agent navigation.
I am also interested in applying computer science techniques to other disciplines, like bioengineering and environmental science.

I received my Ph.D. in computer science from Clemson University under the supervision of Prof. Ioannis Karamouzas. Prior to that, I received an MS from University of Minnesota at Twin Cities in electrical engineering.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='projects/contextvae/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction](contextvae)

**Pei Xu**, Jean-Bernard Hayet, Ioannis Karamouzas

_IEEE Robotics and Automation Letters_

[[Project]](contextvae) [[Paper]](https://arxiv.org/abs/2302.10873)  [[Video]](https://youtu.be/wg6laeYpnW8)
</div>
</div>
