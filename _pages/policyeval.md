---
permalink: /PolicyEval
title: "Too Stiff, Too Strong, Too Smart: Evaluating Fundamental Problems with Motion Control Policies"
excerpt: ""
author_profile: false
redirect_from: 
 - /policyeval
 - /POLICYEVAL
--- 

 

# Too Stiff, Too Strong, Too Smart: Evaluating Fundamental Problems with Motion Control Policies

<p class="author">
<span>Kaixiang Xie<sup>1</sup></span>,
<span>Pei Xu<sup>2</sup></span>,
<span>Sheldon Andrews<sup>3,4</sup></span>,
<span>Victor Zordan<sup>4,2</sup></span>,
<span>Paul G. Kry<sup>1</sup></span>
</p>

<p class="affiliation">
<span><sup>1</sup> McGill University</span>,
<span><sup>2</sup> Clemson University</span>,
<span><sup>3</sup> École de technologie supérieure</span>,
<span><sup>4</sup> Roblox</span>
</p>

In _PACM on Computer Graphics and Interactive Techniques_<br />_(Proceedings of ACM SIGGRAPH/Eurographics Symposium on Computer Animation, 2023)_


<div class="m10"></div>
## Abstract
<div class="abstract">
<img src="projects/PolicyEval/teaser.png" style="width:500px;float:right;max-width:100%;padding:0 20px 10px 20px" />
Deep reinforcement learning (DRL) methods have demonstrated impressive results for skilled motion synthesis of physically based characters, and while these methods perform well in terms of tracking reference motions or achieving complex tasks, several concerns arise when evaluating the naturalness of the motion. In this paper, we conduct a preliminary study of specific quantitative metrics for measuring the naturalness of motion produced by DRL control policies beyond their visual appearance. Namely, we propose to study the stiffness of the control policy, in anticipation that it will influence how the character behaves in the presence of external perturbation. Second, we establish two baselines for strength that allow evaluating the use of joint torques in comparison to human performance. Third, we propose the study of variability to reveal the unnatural precision of control policies and how they compare to real human motion. In sum, we aim to establish repeatable measures to assess the naturalness of control policies produced by DRL methods, and we present a set of comparisons from state-of-the-art systems. Finally, we propose simple modifications to improve realism on these axes.
</div>

<div class="m10"></div>
<a class="paper-link" href="https://doi.org/10.1145/3606935" title="Paper"></a>

<div class="m10"></div>
## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{Xie-2023-PolicyEval,
    author = {Xie, Kaixiang and Xu, Pei and Andrews, Sheldon and Zordan, Victor B and Kry, Paul G},
    title = {Too Stiff, Too Strong, Too Smart: Evaluating Fundamental Problems with Motion Control Policies},
    journal = {Proceedings of the ACM on Computer Graphics and Interactive Techniques},
    publisher = {ACM New York, NY, USA},
    year = {2023},
    volume = {6},
    number = {3},
    pages = {1--17},
    doi = {10.1145/3606935}
}
</pre>{% endraw %}
