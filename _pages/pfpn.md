---
permalink: /PFPN
title: "PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network"
excerpt: ""
author_profile: false
redirect_from: 
 - /pfpn
--- 


# PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network

<p class="author">
Pei Xu<sup>1</sup>, Ioannis Karamouzas<sup>1</sup>
</p>

<p class="affiliation">
<sup>1</sup> Clemson University
</p>

In _ACM SIGGRAPH Conference on Motion, Interaction and Games_, 2021.<br />
Also _NeurIPS Deep Reinforcement Learning Workshop_, 2021.

<div class="m10"></div>
<div class="teaser">
<p><img src="projects/PFPN/teaser.png" /></p>
</div>

<div class="m10"></div>
## Abstract
<div class="abstract">
<img src="projects/PFPN/nips.thumbnail.png" style="width:160px;float:right;max-width:100%;padding:0 20px 10px 20px" />
Data-driven methods for physics-based character control using reinforcement learning have been successfully applied to generate high-quality motions. However, existing approaches typically rely on Gaussian distributions to represent the action policy, which can prematurely commit to suboptimal actions when solving high-dimensional continuous control problems for highly-articulated characters. In this paper, to improve the learning performance of physics-based character controllers, we propose a framework that considers a particle-based action policy as a substitute for Gaussian policies. We exploit particle filtering to dynamically explore and discretize the action space, and track the posterior policy represented as a mixture distribution. The resulting policy can replace the unimodal Gaussian policy which has been the staple for character control problems, without changing the underlying model architecture of the reinforcement learning algorithm used to perform policy optimization. We demonstrate the applicability of our approach on various motion capture imitation tasks. Baselines using our particle-based policies achieve better imitation performance and speed of convergence as compared to corresponding implementations using Gaussians, and are more robust to external perturbations during character control.
</div>


<div class="m10"></div>
<a href="https://arxiv.org/abs/2003.06959" class="paper-link" title="Paper"></a>
<a href="https://github.com/xupei0610/PFPN" class="code-link" title="Code"></a>


<div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/YTtdnq0WpWo?si=d_DzqASFmIkTdmQ2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<div class="m10"></div>
## Poster
<a href="projects/PFPN/nips.poster.pdf"><img src="projects/PFPN/poster.png" style="max-width:100%"></a>



<div class="m10"></div>
## Bibtex
<pre class="bibtex">
@inproceedings{pfpn,
    author = {Xu, Pei and Karamouzas, Ioannis},
    title = {PFPN: Continuous Control of Physically Simulated Characters Using Particle Filtering Policy Network},
    year = {2021},
    isbn = {9781450391313},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    doi = {10.1145/3487983.3488301},
    booktitle = {Motion, Interaction and Games},
    articleno = {7},
    numpages = {12},
    location = {Virtual Event, Switzerland},
    series = {MIG '21}
}
</pre>
