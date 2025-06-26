---
permalink: /
title: 
excerpt: 
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

<div id='about-me' markdown="1">

I am a postdoctoral researcher at [The Movement Lab](https://tml.stanford.edu/) of Stanford University, working with Prof. [C. Karen Liu](https://tml.stanford.edu/people/karen-liu). My research interests include artificial intelligence, computer graphics, and computer vision with a focus on motion planning and reinforcement learning for physics-based character control and embodied agent.
I am also interested in applying computer science techniques to other disciplines, like material science, bioengineering and biomedical engineering.

Before joining Stanford University, I was a research assistant professor at Clemson University, working at the Big Data Analytics Lab with Prof. [Feng Luo](https://people.computing.clemson.edu/~luofeng/).
I received my Ph.D. in computer science from Clemson University under the supervision of Prof. [Ioannis Karamouzas](https://people.computing.clemson.edu/~ioannis/). Prior to that, I received an M.S. in electrical engineering from University of Minnesota at Twin Cities.

</div>


# Publications

## 2025
{: .paper-list-year}
<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*ICCV 2025*{:.badge} ![](projects/hoifhli/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [Human-Object Interaction from Human-Level Instructions](hoifhli)
{: .paper-list-title #hoifhli}

<span>Zhen Wu</span>, <span>Jiaman Li</span>, <span>**Pei Xu**</span>, <span>C. Karen Liu</span>
{: .authors}

In _ICCV_, 2025.

[](https://arxiv.org/pdf/2406.17840){: .paper-link title="Paper"}
[](https://www.youtube.com/watch?v=ztTsMeIgIGk){: .video-link title="Video"}
[](https://hoifhli.github.io/){: .external-link title="Project Page"}
</div>
</div>



## 2024
{: .paper-list-year}

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*SIGGRAPH Asia 2024*{:.badge} ![](projects/Guitar/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [Synchronize Dual Hands for Physics-Based Dexterous Guitar Playing](guitar)
{: .paper-list-title #Guitar}

<span>**Pei Xu**</span>, <span>Ruocheng Wang</span>
{: .authors}

In _SIGGRAPH Asia_, 2024.

[](https://arxiv.org/abs/2409.16629){: .paper-link title="Paper"}
[](https://youtu.be/watch?v=r_y0P2pIeF8&list=PLLfEynalFz6j0X5Kiut0U3GLRxt3Oz_oa){: .video-link title="Video"}
[](https://github.com/xupei0610/guitar){: .code-link title="Code"}
[](https://github.com/xupei0610/guitar/tree/main/dataset){: .dataset-link title="Dataset"}
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*SIGGRAPH Asia 2024*{:.badge} ![](projects/ForElise/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance](ForElise)
{: .paper-list-title #ForElise}

<span>Ruocheng Wang\*</span>, <span>**Pei Xu**\*</span>, <span>Haochen Shi</span>, <span>Elizabeth Schumann</span>, <span>C. Karen Liu</span>
{: .authors}

In _SIGGRAPH Asia_, 2024.

[](https://arxiv.org/abs/2410.05791){: .paper-link title="Paper"}
[](https://for-elise.github.io){: .external-link title="Project Page"}
</div>
</div>



## 2023
{: .paper-list-year}

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*SIGGRAPH Asia 2023*{:.badge} ![](projects/AdaptNet/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [AdaptNet: Policy Adaptation for Physics-Based Character Control](AdaptNet)
{: .paper-list-title #AdaptNet}

<span>**Pei Xu**</span>, <span>Kaixiang Xie</span>, <span>Sheldon Andrews</span>, <span>Paul G. Kry</span>, <span>Michael Neff</span>, <span>Morgan McGuire</span>, <span>Ioannis Karamouzas</span>, <span>Victor Zordan</span>
{: .authors}

_ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2023)_.

[](http://arxiv.org/abs/2310.00239){: .paper-link title="Paper"}
[](https://youtu.be/WxmJSCNFb28){: .video-link title="Video"}
[](https://github.com/xupei0610/AdaptNet){: .code-link title="Code"}
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*RA-L & ICRA 2024*{:.badge} ![](projects/ContextVAE/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction](ContextVAE)
{: .paper-list-title #ContextVAE}

**Pei Xu**, Jean-Bernard Hayet, Ioannis Karamouzas
{: .authors}

_IEEE Robotics and Automation Letters_.\\
Also in _IEEE International Conference on Robotics and Automation_, 2024.

[](https://arxiv.org/abs/2302.10873){: .paper-link title="Paper"}
[](https://youtu.be/wg6laeYpnW8){: .video-link title="Video"}
[](https://github.com/xupei0610/ContextVAE){: .code-link title="Code"}
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*SIGGRAPH 2023*{:.badge} ![](projects/CompositeMotion/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [Composite Motion Learning with Task Control](CompositeMotion)
{: .paper-list-title #CompositeMotion}

**Pei Xu**, Xiumin Shang, Victor Zordan, Ioannis Karamouzas
{: .authors}

_ACM Transactions on Graphics (Proceedings of SIGGRAPH 2023)_. *In technical papers trailer.*{:.paper-list-highlight}

[](https://arxiv.org/abs/2305.03286){: .paper-link title="Paper"}
[](https://youtu.be/mcRAxwoTh3E){: .video-link title="Video"}
[](https://github.com/xupei0610/CompositeMotion){: .code-link title="Code"}
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*SCA 2023*{:.badge} ![](projects/PolicyEval/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [Too Stiff, Too Strong, Too Smart: Evaluating Fundamental Problems with Motion Control Policies](PolicyEval)
{: .paper-list-title #PolicyEval}

Kaixiang Xie, **Pei Xu**, Sheldon Andrews, Victor Zordan, Paul G. Kry
{: .authors}

_PACM on Computer Graphics and Interactive Techniques_.\\
In _ACM SIGGRAPH/Eurographics Symposium on Computer Animation_, 2023.

[](https://doi.org/10.1145/3606935){: .paper-link title="Paper"}
[](http://kaixiangxie.de/projects/policy-eval){: .external-link title="Project Page"}
</div>
</div>


## 2022
{: .paper-list-year}

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*ECCV 2022*{:.badge} ![](projects/SocialVAE/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [SocialVAE: Human Trajectory Prediction using Timewise Latents](SocialVAE)
{: .paper-list-title #SocialVAE}

**Pei Xu**, Jean-Bernard Hayet, Ioannis Karamouzas
{: .authors}

In _the 17th European Conference on Computer Vision_, 2022.

[](https://arxiv.org/abs/2203.08207){: .paper-link title="Paper"}
[](https://youtu.be/nXrreTmXktM){: .video-link title="Video"}
[](https://github.com/xupei0610/SocialVAE){: .code-link title="Code"}
</div>
</div>


## 2021
{: .paper-list-year}

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*MIG 2021*{:.badge} ![](projects/PFPN/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network](PFPN)
{: .paper-list-title #PFPN}

**Pei Xu**, Ioannis Karamouzas
{: .authors}

In _ACM SIGGRAPH Conference on Motion, Interaction and Games_, 2021. *Best paper nomination.*{:.paper-list-highlight}\\
Also in _NeurIPS Deep Reinforcement Learning workshop_, 2021.

[](https://arxiv.org/abs/2003.06959){: .paper-link title="Paper"}
[](https://www.youtube.com/YTtdnq0WpWo){: .video-link title="Video"}
[](https://github.com/xupei0610/PFPN){: .code-link title="Code"}
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*IROS 2021*{:.badge} ![](projects/KDMA/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [Human Inspired Multi-Agent Navigation using Knowledge Distillation](KDMA)
{: .paper-list-title #KDMA}

**Pei Xu**, Ioannis Karamouzas
{: .authors}

In _IEEE/RSJ International Conference on Intelligent Robots and Systems_, 2021.

[](https://arxiv.org/abs/2103.10000){: .paper-link title="Paper"}
[](https://youtu.be/tMctyEw8kRI){: .video-link title="Video"}
[](https://github.com/xupei0610/KDMA){: .code-link title="Code"}
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image' markdown="1">
*SCA 2021*{:.badge} ![](projects/ICCGAN/thumb.png)
</div>
<div class='paper-box-text' markdown="1">
### [A GAN-Like Approach for Physics-Based Imitation Learning and Interactive Character Control](ICCGAN)
{: .paper-list-title #ICCGAN}

**Pei Xu**, Ioannis Karamouzas
{: .authors}

_PACM on Computer Graphics and Interactive Techniques_. *Cover article.*{:.paper-list-highlight}\\
In _ACM SIGGRAPH/Eurographics Symposium on Computer Animation_, 2021.

[](https://arxiv.org/abs/2105.10066){: .paper-link title="Paper"}
[](https://youtu.be/VHMyvDD3B_o){: .video-link title="Video"}
[](https://github.com/xupei0610/CompositeMotion){: .code-link title="Code"}
</div>
</div>

## <span class="paper-list-year">Bioengineering & Biomedical Engineering</span>
- ``JCI Insight`` [Explainable Deep Learning and Biomechanical Modeling for TMJ Disorder Morphological Risk Factors](https://doi.org/10.1172/jci.insight.178578), Shuchun Sun\*, **Pei Xu**\*, Nathan Buchweitz\*, Cherice N Hill, Farhad Ahmadi, Marshall B Wilson, Angela Mei, Xin She, Benedikt Sagl, Elizabeth H Slate, Janice S Lee, Yongren Wu, Hai Yao, 2024.
- ``Osteoarthritis and Cartilage Open`` [Mask R-CNN Provides Efficient and Accurate Measurement of Chondrocyte Viability in the Label-Free Assessment of Articular Cartilage](https://doi.org/10.1016/j.ocarto.2023.100415), Hongming Fan, **Pei Xu**, Xun Chen, Yang Li, Zhao Zhang, Jennifer Hsu, Michael Le, Emily Ye, Bruce Gao, Harry Demos, Hai Yao, Tong Ye, 2023.
- ``SPIE BiOS`` [Automated Chondrocyte Viability Analysis of Articular Cartilage based on Deep Learning Segmentation and Classification of Two-Photon Microscopic Images](https://doi.org/10.1117/12.2609880), Hongming Fan, **Pei Xu**, Michael Le, Jennifer Hsu, Xun Chen, Yang Li, Zhao Zhang, Bruce Gao, Shane Woolf, Tong Ye, 2022.

## <span class="paper-list-year">Material Science</span>
- ``Composites Part B: Engineering`` [Physically Constrained 3D Diffusion for Inverse Design of Fiber-reinforced Polymer Composite Materials](https://doi.org/10.1016/j.compositesb.2025.112515), **Pei Xu**\*, Yunpeng Wu\*, Alireza Zarei, Shahriar Ahmed, Srikanth Pilla, Gang Li, Feng Luo, 2025.


## <span class="paper-list-year">Prior Work</span>
- ``MIG 2019`` [Low Dimensional Motor Skill Learning Using Coactivation](https://doi.org/10.1145/3359566.3360071), Avinash Ranganath, **Pei Xu**, Ioannis Karamouzas, Victor Zordan. [](https://www.youtube.com/watch?v=8U8YsmiANNA&ab_channel=HubertP.H.Shum){: .video-link title="Video"}
- [Gesture-based Human-robot Interaction for Field Programmable Autonomous Underwater Robots](https://arxiv.org/abs/1709.08945), **Pei Xu**, 2017.
- [A Real-Time Hand Gesture Recognition and Human-Computer Interaction System](https://arxiv.org/abs/1704.07296), **Pei Xu**, 2017. [](https://youtu.be/4n9F7iJJ2TY){: .video-link title="Video"}
