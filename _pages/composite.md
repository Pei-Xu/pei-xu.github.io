---
permalink: /CompositeMotion
title: "Composite Motion Learning with Task Control"
excerpt: ""
author_profile: false
redirect_from: 
 - /compositemotion
 - /COMPOSITEMOTION
 - /composite
 - /Composite
 - /COMPOSITE
--- 


# Composite Motion Learning with Task Control

<p class="author">
Pei Xu<sup>1, 2</sup>, Xiumin Shang<sup>3</sup>, Victor Zordan<sup>2</sup>, Ioannis Karamouzas<sup>1,4</sup>
</p>

<p class="affiliation">
<sup>1</sup> Clemson University,  <sup>2</sup> Roblox,  <sup>2</sup> University of California, Merced,  <sup>4</sup> University of California, Riverside
</p>

In _ACM Transactions on Graphics (Proceedings of SIGGRAPH 2023)_

<div class="m10"></div>
<div class="teaser">
<p><img src="projects/CompositeMotion/teaser_tennis.png" /></p>
<p><img src="projects/CompositeMotion/teaser_juggling.png" /></p>
<p><img src="projects/CompositeMotion/teaser_aiming.png" /></p>
</div>

<div class="m10"></div>
## Abstract
<div class="abstract">
We present a deep learning method for composite and task-driven motion control for physically simulated characters. In contrast to existing data-driven approaches using reinforcement learning that imitate full-body motions, we learn decoupled motions for specific body parts from multiple reference motions simultaneously and directly by leveraging the use of multiple discriminators in a GAN-like setup. In this process, there is no need of any manual work to produce composite reference motions for learning. Instead, the control policy explores by itself how the composite motions can be combined automatically. We further account for multiple task-specific rewards and train a single, multi-objective control policy. To this end, we propose a novel framework for multi-objective learning that adaptively balances the learning of disparate motions from multiple sources and multiple goal-directed control objectives. In addition, as composite motions are typically augmentations of simpler behaviors, we introduce a sample-efficient method for training composite control policies in an incremental manner, where we reuse a pre-trained policy as the meta policy and train a cooperative policy that adapts the meta one for new composite tasks. We show the applicability of our approach on a variety of challenging multi-objective tasks involving both composite motion imitation and multiple goal-directed control.
</div>

<div class="m10"></div>
<a class="paper-link" href="https://arxiv.org/abs/2305.03286" title="Paper"></a>
<a class="code-link" href="https://github.com/xupei0610/CompositeMotion" title="Code"></a>

<div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/mcRAxwoTh3E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="max-width:400px;margin-top:20px">
<iframe width="400" height="200" src="https://www.youtube.com/embed/VBZ2sDxvZQE?si=ZwYPpeqJAgEI0Ja4&amp;start=148"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<div class="m10"></div>
## Poster
<a href="projects/CompositeMotion/poster.pdf"><img src="projects/CompositeMotion/poster.png" style="width:560px;max-width:100%"></a>

<div class="m10"></div>
## Bibtex
<pre class="bibtex">
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
</pre>



