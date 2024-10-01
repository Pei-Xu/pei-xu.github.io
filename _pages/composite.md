---
permalink: /CompositeMotion
title: "Composite Motion Learning with Task Control"
excerpt: ""
author_profile: false
redirect_from: 
 - /composite
--- 


# Composite Motion Learning with Task Control
{: #title}

<span>Pei Xu<sup>1,2</sup></span>,
<span>Xiumin Shang<sup>3</sup></span>,
<span>Victor Zordan<sup>2</sup></span>,
<span>Ioannis Karamouzas<sup>1,4</sup></span>
{: .authors}

<span><sup>1</sup> Clemson University</span>, 
<span><sup>2</sup> Roblox</span>, 
<span><sup>3</sup> University of California, Merced</span>, 
<span><sup>4</sup> University of California, Riverside</span>
{: .affiliations}

In _ACM Transactions on Graphics (Proceedings of SIGGRAPH 2023)_

![](projects/CompositeMotion/teaser_tennis.png)\\
![](projects/CompositeMotion/teaser_juggling.png){: style="margin-bottom:10px"}\\
![](projects/CompositeMotion/teaser_aiming.png)
{: .teasers}

## Abstract
![](projects/CompositeMotion/3609020.cover.jpg){: style="width:300px;float:right;max-width:100%;padding:0 0 10px 20px"}
We present a deep learning method for composite and task-driven motion control for physically simulated characters. In contrast to existing data-driven approaches using reinforcement learning that imitate full-body motions, we learn decoupled motions for specific body parts from multiple reference motions simultaneously and directly by leveraging the use of multiple discriminators in a GAN-like setup. In this process, there is no need of any manual work to produce composite reference motions for learning. Instead, the control policy explores by itself how the composite motions can be combined automatically. We further account for multiple task-specific rewards and train a single, multi-objective control policy. To this end, we propose a novel framework for multi-objective learning that adaptively balances the learning of disparate motions from multiple sources and multiple goal-directed control objectives. In addition, as composite motions are typically augmentations of simpler behaviors, we introduce a sample-efficient method for training composite control policies in an incremental manner, where we reuse a pre-trained policy as the meta policy and train a cooperative policy that adapts the meta one for new composite tasks. We show the applicability of our approach on a variety of challenging multi-objective tasks involving both composite motion imitation and multiple goal-directed control.

[](https://arxiv.org/abs/2305.03286){: .paper-link title="Paper"}
[](https://github.com/xupei0610/CompositeMotion){: .code-link title="Code"}
{: .links}


## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/mcRAxwoTh3E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="max-width:400px;margin-top:20px">
<iframe width="400" height="200" src="https://www.youtube.com/embed/VBZ2sDxvZQE?si=ZwYPpeqJAgEI0Ja4&amp;start=148"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>


## Poster
[![](projects/CompositeMotion/poster.png){: style="width:560px;max-width:100%"}](projects/CompositeMotion/poster.pdf)


## Bibtex
{% raw %}<pre class="bibtex">
@article{composite,
    author = {Xu, Pei and Shang, Xiumin and Zordan, Victor and Karamouzas, Ioannis},
    title = {Composite Motion Learning with Task Control},
    journal = {ACM Transactions on Graphics},
    publisher = {ACM New York, NY, USA},
    year = {2023},
    volume = {42},
    number = {4},
    doi = {10.1145/3592447}
}
</pre>{% endraw %}

