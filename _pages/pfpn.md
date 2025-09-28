---
permalink: /PFPN
title: "PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network"
excerpt: ""
author_profile: false
redirect_from: 
 - /pfpn
--- 

# PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network
{: #title}

<span>Pei Xu</span>,
<span>Ioannis Karamouzas</span>
{: .authors}

<span>Clemson University</span>
{: .affiliations}

In _ACM SIGGRAPH Conference on Motion, Interaction and Games_, 2021.\\
Also _NeurIPS Deep Reinforcement Learning Workshop_, 2021.

![](projects/PFPN/teaser.png)
{: .teasers}

## Abstract
![](projects/PFPN/nips.thumbnail.png){: style="width:160px;float:right;max-width:100%;padding:0 0 10px 20px;clear:both"}
<!-- ![](projects/PFPN/mig2021_small.png){: style="float:right;max-width:100%;padding:0 20px 10px 20px;clear:both"}
![](projects/PFPN/neurips_small.png){: style="float:right;max-width:100%;padding:0 20px 10px 20px;clear:both"} -->
Data-driven methods for physics-based character control using reinforcement learning have been successfully applied to generate high-quality motions. However, existing approaches typically rely on Gaussian distributions to represent the action policy, which can prematurely commit to suboptimal actions when solving high-dimensional continuous control problems for highly-articulated characters. In this paper, to improve the learning performance of physics-based character controllers, we propose a framework that considers a particle-based action policy as a substitute for Gaussian policies. We exploit particle filtering to dynamically explore and discretize the action space, and track the posterior policy represented as a mixture distribution. The resulting policy can replace the unimodal Gaussian policy which has been the staple for character control problems, without changing the underlying model architecture of the reinforcement learning algorithm used to perform policy optimization. We demonstrate the applicability of our approach on various motion capture imitation tasks. Baselines using our particle-based policies achieve better imitation performance and speed of convergence as compared to corresponding implementations using Gaussians, and are more robust to external perturbations during character control.


[](https://arxiv.org/abs/2003.06959){: .paper-link title="Paper}
[](https://github.com/xupei0610/PFPN){: .code-link title="Code"}
{: .links}


## Video
<div style="max-width:560px;margin-bottom:20px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/YTtdnq0WpWo?si=d_DzqASFmIkTdmQ2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="max-width:560px;margin-bottom:20px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Usbpl6jefCY?si=ypAxV7tSxa0OAD2Z" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

[](https://www.bilibili.com/video/BV1Xe411D7hg/){: .bilibili-link title="Bilibili"}



## Poster
[![](projects/PFPN/poster.png){: style="max-width:100%"}](projects/PFPN/nips.poster.pdf)


## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{pfpn,
    author = {Xu, Pei and Karamouzas, Ioannis},
    title = {{PFPN}: Continuous Control of Physically Simulated Characters Using Particle Filtering Policy Network},
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
</pre>{% endraw %}
