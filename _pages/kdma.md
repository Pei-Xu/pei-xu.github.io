---
permalink: /KDMA
title: "Human Inspired Multi-Agent Navigation using Knowledge Distillation"
excerpt: ""
author_profile: false
 - /kdma
--- 

# Human Inspired Multi-Agent Navigation using Knowledge Distillation
{: #title}

<span>Pei Xu</span>,
<span>Ioannis Karamouzas</span>
{: .authors}

<span>Clemson University</span>
{: .affiliations}

In _IEEE/RSJ International Conference on Intelligent Robots and Systems_, 2021.


| Reference | Ours | RL w/o KD | ORCA |
|:----------|:-----|:----------|:-----|
|![](projects/KDMA/c6_ref.gif){: data-animated-image}|![](projects/KDMA/c6_ours.gif){: data-animated-image}|![](projects/KDMA/c6_rl.gif){: data-animated-image}|![](projects/KDMA/c6_orca.gif){: data-animated-image}|
|![](projects/KDMA/c12_1_ref.gif){: data-animated-image}|![](projects/KDMA/c12_1_ours.gif){: data-animated-image}|![](projects/KDMA/c12_1_rl.gif){: data-animated-image}|![](projects/KDMA/c12_1_orca.gif){: data-animated-image}|
|![](projects/KDMA/c24_3_ref.gif){: data-animated-image}|![](projects/KDMA/c24_3_ours.gif){: data-animated-image}|![](projects/KDMA/c24_3_rl.gif){: data-animated-image}|![](projects/KDMA/c24_3_orca.gif){: data-animated-image}|
|![](projects/KDMA/c24_4_ref.gif){: data-animated-image}|![](projects/KDMA/c24_4_ours.gif){: data-animated-image}|![](projects/KDMA/c24_4_rl.gif){: data-animated-image}|![](projects/KDMA/c24_4_orca.gif){: data-animated-image}|
{: .teasers}


## Abstract
![System Overview](projects/KDMA/teaser.png){: style="width:560px;float:right;max-width:100%;padding:0 0 20px 20px;clear:both"}
![IROS 2021](projects/KDMA/iros_small.png){: style="float:right;max-width:100%;padding:0 20px 10px 20px;clear:both"}
Despite significant advancements in the field of multi-agent navigation, agents still lack the sophistication and intelligence that humans exhibit in multi-agent settings. In this paper, we propose a framework for learning a human-like general collision avoidance policy for agent-agent interactions in fully decentralized, multi-agent environments. Our approach uses knowledge distillation with reinforcement learning to shape the reward function based on expert policies extracted from human trajectory demonstrations through behavior cloning. We show that agents trained with our approach can take human-like trajectories in collision avoidance and goal-directed steering tasks not provided by the demonstrations, outperforming the experts as well as learning-based agents trained without knowledge distillation.

[](https://arxiv.org/abs/2103.10000){: .paper-link title="Paper"}
[](https://github.com/xupei0610/KDMA){: .code-link title="Code"}
{: .links}

## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/tMctyEw8kRI?si=7Y4unsmk6Q9qDngW" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>


## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{kdma,
    author={Xu, Pei and Karamouzas, Ioannis},
    booktitle={2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
    title={Human-Inspired Multi-Agent Navigation using Knowledge Distillation}, 
    year={2021},
    volume={},
    number={},
    pages={8105-8112},
    doi={10.1109/IROS51168.2021.9636463}
}
</pre>{% endraw %}
