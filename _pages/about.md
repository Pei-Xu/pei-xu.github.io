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

<div class="m20"></div>
<div class='anchor' id='about-me'>

<p>I am a postdoctoral researcher at <a href="https://tml.stanford.edu/">The Movement Lab</a> of Stanford University, working with Prof. <a href="https://tml.stanford.edu/people/karen-liu">C. Karen Liu</a>. My research interests include artificial intelligence, computer graphics, and computer vision with a focus on motion planning and reinforcement learning for physics-based character control and agent navigation.
I am also interested in applying computer science techniques to other disciplines, like bioengineering and environmental science. </p>

<p>Before joining Stanford University, I was a research assistant professor at Clemson University, working at the Big Data Analytics Lab with Prof. <a href="https://people.computing.clemson.edu/~luofeng/">Feng Luo</a>.
I received my Ph.D. in computer science from Clemson University under the supervision of Prof. <a href="https://people.computing.clemson.edu/~ioannis/">Ioannis Karamouzas</a>. Prior to that, I received an M.S. in electrical engineering from University of Minnesota at Twin Cities.</p>

</div>

# Publications 

## <span class="paper-list-year">2023</span>

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">SIGGRAPH Asia 2024</div>
<img src='projects/Guitar/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[Synchronize Dual Hands for Physics-Based Dexterous Guitar Playing](guitar)</span>

**Pei Xu**, Ruocheng Wang

In _SIGGRAPH Asia 2024_.

<a href="#" class="paper-link" title="Paper"></a>
<a href="https://youtu.be/watch?v=r_y0P2pIeF8&list=PLLfEynalFz6j0X5Kiut0U3GLRxt3Oz_oa" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/guitar" class="code-link" title="Code"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">SIGGRAPH Asia 2024</div>
<img src='projects/ForElise/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance</span>

Ruocheng Wang*, **Pei Xu***, Haochen Shi, Elizabeth Schumann, C. Karen Liu 

In _SIGGRAPH Asia 2024_.

<!-- <a href="#" class="paper-link" title="Paper"></a>
<a href="#" class="video-link" title="Video"></a>
<a href="#" class="code-link" title="Code"></a> -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">SIGGRAPH Asia 2023</div>
<img src='projects/AdaptNet/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[AdaptNet: Policy Adaptation for Physics-Based Character Control](AdaptNet)</span>

**Pei Xu**, Kaixiang Xie, Sheldon Andrews, Paul G. Kry, Michael Neff, Morgan McGuire, Ioannis Karamouzas, Victor Zordan

_ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2023)_.

<a href="http://arxiv.org/abs/2310.00239" class="paper-link" title="Paper"></a>
<a href="https://youtu.be/WxmJSCNFb28" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/AdaptNet" class="code-link" title="Code"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">RA-L & ICRA 2024</div>
<img src='projects/ContextVAE/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction](ContextVAE)</span>

**Pei Xu**, Jean-Bernard Hayet, Ioannis Karamouzas

_IEEE Robotics and Automation Letters_.<br />
Also in _IEEE International Conference on Robotics and Automation_, 2024.

<a href="https://arxiv.org/abs/2302.10873" class="paper-link" title="Paper"></a>
<a href="https://youtu.be/wg6laeYpnW8" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/ContextVAE" class="code-link" title="Code"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH 2023</div>
<img src='projects/CompositeMotion/thumb.png' alt="sym" width="100%">
</div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[Composite Motion Learning with Task Control](CompositeMotion)</span>

**Pei Xu**, Xiumin Shang, Victor Zordan, Ioannis Karamouzas

_ACM Transactions on Graphics (Proceedings of SIGGRAPH 2023)_. <span class="paper-list-highlight">In technical papers trailer.</span>

<a href="https://arxiv.org/abs/2305.03286" class="paper-link" title="Paper"></a>
<a href="https://youtu.be/mcRAxwoTh3E" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/CompositeMotion" class="code-link" title="Code"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCA 2023</div><img src='projects/PolicyEval/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[Too Stiff, Too Strong, Too Smart: Evaluating Fundamental Problems with Motion Control Policies](PolicyEval)</span>

Kaixiang Xie, **Pei Xu**, Sheldon Andrews, Victor Zordan, Paul G. Kry

_PACM on Computer Graphics and Interactive Techniques_.<br />
In _ACM SIGGRAPH/Eurographics Symposium on Computer Animation_, 2023.

<a href="https://doi.org/10.1145/3606935" class="paper-link" title="Paper"></a>
</div>
</div>


## <span class="paper-list-year">2022</span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='projects/SocialVAE/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[SocialVAE: Human Trajectory Prediction using Timewise Latents](SocialVAE)</span>

**Pei Xu**, Jean-Bernard Hayet, Ioannis Karamouzas

In _the 17th European Conference on Computer Vision_, 2022.

<a href="https://arxiv.org/abs/2203.08207" class="paper-link" title="Paper"></a>
<a href="https://youtu.be/nXrreTmXktM" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/SocialVAE" class="code-link" title="Code"></a>
</div>
</div>


## <span class="paper-list-year">2021</span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MIG 2021</div><img src='projects/PFPN/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network](PFPN)</span>

**Pei Xu**, Ioannis Karamouzas

In _ACM SIGGRAPH Conference on Motion, Interaction and Games_, 2021. <span class="paper-list-highlight">Best paper nomination.</span><br />
Also in _NeurIPS Deep Reinforcement Learning workshop_, 2021.

<a href="https://arxiv.org/abs/2003.06959" class="paper-link" title="Paper"></a>
<a href="https://www.youtube.com/YTtdnq0WpWo" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/PFPN" class="code-link" title="Code"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2021</div><img src='projects/KDMA/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[Human Inspired Multi-Agent Navigation using Knowledge Distillation](KDMA)</span>

**Pei Xu**, Ioannis Karamouzas

In _IEEE/RSJ International Conference on Intelligent Robots and Systems_, 2021.

<a href="https://arxiv.org/abs/2103.10000" class="paper-link" title="Paper"></a>
<a href="https://youtu.be/tMctyEw8kRI" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/KDMA" class="code-link" title="Code"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCA 2021</div><img src='projects/ICCGAN/thumb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="paper-list-title">[A GAN-Like Approach for Physics-Based Imitation Learning and Interactive Character Control](ICCGAN)</span>

**Pei Xu**, Ioannis Karamouzas

_PACM on Computer Graphics and Interactive Techniques_. <span class="paper-list-highlight">Cover article.</span><br />
In _ACM SIGGRAPH/Eurographics Symposium on Computer Animation_, 2021.

<a href="https://arxiv.org/abs/2105.10066" class="paper-link" title="Paper"></a>
<a href="https://youtu.be/VHMyvDD3B_o" class="video-link" title="Video"></a>
<a href="https://github.com/xupei0610/CompositeMotion" class="code-link" title="Code"></a>
</div>
</div>

## <span class="paper-list-year">Bioengineering & Biomedical Engineering</span>
- ``JCI Insight`` [Explainable Deep Learning and Biomechanical Modeling for TMJ Disorder Morphological Risk Factors](https://doi.org/10.1172/jci.insight.178578), Shuchun Sun\*, **Pei Xu**\*, Nathan Buchweitz\*, Cherice N Hill, Farhad Ahmadi, Marshall B Wilson, Angela Mei, Xin She, Benedikt Sagl, Elizabeth H Slate, Janice S Lee, Yongren Wu, Hai Yao, 2024.
- ``Osteoarthritis and Cartilage Open`` [Mask R-CNN Provides Efficient and Accurate Measurement of Chondrocyte Viability in the Label-Free Assessment of Articular Cartilage](https://doi.org/10.1016/j.ocarto.2023.100415), Hongming Fan, **Pei Xu**, Xun Chen, Yang Li, Zhao Zhang, Jennifer Hsu, Michael Le, Emily Ye, Bruce Gao, Harry Demos, Hai Yao, Tong Ye, 2023.
- ``SPIE BiOS`` [Automated Chondrocyte Viability Analysis of Articular Cartilage based on Deep Learning Segmentation and Classification of Two-Photon Microscopic Images](https://doi.org/10.1117/12.2609880), Hongming Fan, **Pei Xu**, Michael Le, Jennifer Hsu, Xun Chen, Yang Li, Zhao Zhang, Bruce Gao, Shane Woolf, Tong Ye, 2022.


## <span class="paper-list-year">Prior Work</span>
- ``MIG 2019`` [Low Dimensional Motor Skill Learning Using Coactivation](https://doi.org/10.1145/3359566.3360071), Avinash Ranganath, **Pei Xu**, Ioannis Karamouzas, Victor Zordan. <a href="https://www.youtube.com/watch?v=8U8YsmiANNA&ab_channel=HubertP.H.Shum" class="video-link" title="Video"></a>
- [Gesture-based Human-robot Interaction for Field Programmable Autonomous Underwater Robots](https://arxiv.org/abs/1709.08945), **Pei Xu**, 2017.
- [A Real-Time Hand Gesture Recognition and Human-Computer Interaction System](https://arxiv.org/abs/1704.07296), **Pei Xu**, 2017. <a href="https://youtu.be/4n9F7iJJ2TY" class="video-link" title="Video"></a>
