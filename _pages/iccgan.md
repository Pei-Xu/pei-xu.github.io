---
permalink: /ICCGAN
title: "A GAN-Like Approach for Physics-Based Imitation Learning and Interactive Character Control"
excerpt: ""
author_profile: false
redirect_from: 
 - /iccgan
--- 


# A GAN-Like Approach for Physics-Based Imitation Learning and Interactive Character Control

<p class="author">
<span>Pei Xu<sup>1</sup></span>,
<span>Ioannis Karamouzas<sup>1</sup></span>
</p>

<p class="affiliation">
<span><sup>1</sup> Clemson University</span>
</p>

In _PACM on Computer Graphics and Interactive Techniques_<br />_(Proceedings of ACM SIGGRAPH/Eurographics Symposium on Computer Animation, 2021)_

<div class="m10"></div>
<div class="teaser">
<p><img src="projects/ICCGAN/teaser_fight.png" /></p>
<p><img src="projects/ICCGAN/teaser_jump.png" /></p>
<p><img src="projects/ICCGAN/teaser_recover.png" /></p>
</div>

<div class="m10"></div>
## Abstract
<div class="abstract">
<img src="projects/ICCGAN/cover.png" style="width:300px;float:right;max-width:100%;padding:0 20px 10px 20px" />
We present a simple and intuitive approach for interactive control of physically simulated characters. Our work builds upon generative adversarial networks (GAN) and reinforcement learning, and introduces an imitation learning framework where an ensemble of classifiers and an imitation policy are trained in tandem given pre-processed reference clips. The classifiers are trained to discriminate the reference motion from the motion generated by the imitation policy, while the policy is rewarded for fooling the discriminators. Using our GAN-based approach, multiple motor control policies can be trained separately to imitate different behaviors. In runtime, our system can respond to external control signal provided by the user and interactively switch between different policies. Compared to existing methods, our proposed approach has the following attractive properties: 1) achieves state-of-the-art imitation performance without manually designing and fine tuning a reward function; 2) directly controls the character without having to track any target reference pose explicitly or implicitly through a phase state; and 3) supports interactive policy switching without requiring any motion generation or motion matching mechanism. We highlight the applicability of our approach in a range of imitation and interactive control tasks, while also demonstrating its ability to withstand external perturbations as well as to recover balance. Overall, our approach generates high-fidelity motion, has low runtime cost, and can be easily integrated into interactive applications and games.
</div>


<div class="m10"></div>
<a class="paper-link" href="https://arxiv.org/abs/2105.10066" title="Paper"></a>
<a class="code-link" href="https://github.com/xupei0610/CompositeMotion" title="Code"></a>

<div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/VHMyvDD3B_o" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="max-width:560px;margin-top:20px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPzpCarkm74" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<div class="m10"></div>
## Bibtex
{% raw %}<pre class="bibtex">
@article{iccgan,
    author = {Xu, Pei and Karamouzas, Ioannis},
    title = {A {GAN}-Like Approach for Physics-Based Imitation Learning and Interactive Character Control},
    journal = {Proceedings of the ACM on Computer Graphics and Interactive Techniques},
    publisher = {ACM New York, NY, USA},
    year = {2021},
    volume = {4},
    number = {3},
    pages = {1--22},
    doi = {10.1145/3480148}
}
</pre>{% endraw %}

