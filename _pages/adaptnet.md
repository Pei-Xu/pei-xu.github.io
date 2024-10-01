---
permalink: /AdaptNet
title: "AdaptNet: Policy Adaptation for Physics-Based Character Control"
excerpt: ""
author_profile: false
redirect_from: 
 - /adapt
--- 


# AdaptNet: Policy Adaptation for Physics-Based Character Control
{: #title}

<span>Pei Xu<sup>1,2</sup></span>,
<span>Kaixiang Xie<sup>3</sup></span>,
<span>Sheldon Andrews<sup>4,2</sup></span>,
<span>Paul G. Kry<sup>3</sup></span>,
<span>Michael Neff<sup>5</sup></span>,
<span>Morgan McGuire<sup>2,6</sup></span>,
<span>Ioannis Karamouzas<sup>7</sup></span>,
<span>Victor Zordan<sup>2,1</sup></span>
{: .authors}

<span><sup>1</sup> Clemson University</span>,
<span><sup>2</sup> Roblox</span>,
<span><sup>3</sup> McGill University</span>,
<span><sup>4</sup> École de Technologie Supérieure</span>,
<span><sup>5</sup> University of California, Davis</span>,
<span><sup>6</sup> University of Waterloo</span>,
<span><sup>7</sup> University of California, Riverside</span>
{: .affiliations}

In _ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2023)_

![](projects/AdaptNet/latent.png){: style="margin-bottom:20px"}\\
![](projects/AdaptNet/teaser.png)
{: .teasers}

## Abstract
<!-- [](projects/AdaptNet/sa2023_logo.png){: style="width:200px;float:right;max-width:100%;padding:0 0 10px 20px"} -->
![](projects/AdaptNet/cover.png){: style="width:300px;float:right;max-width:100%;padding:0 0 10px 20px"}
Motivated by humans' ability to adapt skills in the learning of new ones, this paper presents AdaptNet, an approach for modifying the latent space of existing policies to allow new behaviors to be quickly learned from like tasks in comparison to learning from scratch. Building on top of a given reinforcement learning  controller, AdaptNet uses a two-tier hierarchy that augments the original state embedding to support modest changes in a behavior and further modifies the policy network layers to make more substantive changes. The technique is shown to be effective for adapting existing physics-based controllers to a wide range of new styles for locomotion, new task targets, changes in character morphology and extensive changes in environment. Furthermore, it exhibits significant increase in learning efficiency, as indicated by greatly reduced training times when compared to training from scratch or using other approaches that modify existing policies.

[](http://arxiv.org/abs/2310.00239){: .paper-link title="Paper"}
[](https://github.com/xupei0610/AdaptNet){: .code-link title="Code"}
{: .links}

## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/WxmJSCNFb28" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Bibtex
{% raw %}<pre class="bibtex">
@article{adaptnet,
    author = {Xu, Pei and Xie, Kaixiang and Andrews, Sheldon and Kry, Paul G and Neff, Michael and McGuire, Morgan and Karamouzas, Ioannis and Zordan, Victor},
    title = {{AdaptNet}: Policy Adaptation for Physics-Based Character Control},
    journal = {ACM Transactions on Graphics},
    publisher = {ACM New York, NY, USA},
    year = {2023},
    volume = {42},
    number = {6},
    doi = {10.1145/3618375}
}
</pre>{% endraw %}



