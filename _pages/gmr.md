---
permalink: /GMR
title: "Retargeting Matters: General Motion Retargeting for Humanoid Motion Tracking"
excerpt: ""
author_profile: false
redirect_from: 
 - /gmr
--- 

# Retargeting Matters: General Motion Retargeting for Humanoid Motion Tracking
{: #title}


<span>João Pedro Araújo\* </span>, <span>Yanjie Ze\*</span>, <span>Pei Xu\*</span>, <span>Jiajun Wu†</span>, <span>C. Karen Liu†</span>
{: .authors}

<span>Stanford University</span>
{: .affiliations}

In _IEEE International Conference on Robotics and Automation_, 2026.

<!-- ![teaser](projects/gmr/teaser1.png)
{: .teasers} -->

## Abstract
![ICRA 2026](projects/gmr/icra2026_logo.png){: style="float:right;width:300px;max-width:100%;padding:20px 0 10px 20px;clear:both"}
Humanoid motion tracking policies are central to building teleoperation pipelines and hierarchical controllers, yet they face a fundamental challenge: the embodiment gap between humans and humanoid robots. Current approaches address this gap by retargeting human motion data to humanoid embodiments and then training reinforcement learning (RL) policies to imitate these reference trajectories. However, artifacts introduced during retargeting, such as foot sliding, self-penetration, and physically infeasible motion are often left in the reference trajectories for the RL policy to correct. While prior work has demonstrated motion tracking abilities, they often require extensive reward engineering and domain randomization to succeed.
In this paper, we systematically evaluate how retargeting quality affects policy performance when excessive reward tuning is suppressed. To address issues that we identify with existing retargeting methods, we propose a new retargeting method, General Motion Retargeting (GMR). We evaluate GMR alongside two open-source retargeters, PHC and ProtoMotions, as well as with a high-quality closed-source dataset from Unitree. Using BeyondMimic for policy training, we isolate retargeting effects without reward tuning.
Our experiments on a diverse subset of the LAFAN1 dataset reveal that while most motions can be tracked, artifacts in retargeted data significantly reduce policy robustness, particularly for dynamic or long sequences. GMR consistently outperforms existing open-source methods in both tracking performance and faithfulness to the source motion, achieving perceptual fidelity and policy success rates close to the closed-source baseline.


[](https://arxiv.org/abs/2510.02252){: .paper-link title="Paper"}
<!-- [](youtube.com/watch?v=kr3I_g1GLYw&feature=youtu.be){: .video-link title="Video"} -->
[](https://github.com/zhenkirito123/hoifhli_release){: .code-link title="Code"}
[](https://jaraujo98.github.io/retargeting_matters/){: .external-link title="Project Page"}
{: .links}

## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/kr3I_g1GLYw?si=LrcX2DSL1Wt9teVk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{gmr,
  title={Retargeting Matters: General Motion Retargeting for Humanoid Motion Tracking},
  author= {Joao Pedro Araujo and Yanjie Ze and Pei Xu and Jiajun Wu and C. Karen Liu},
  year= {2025},
  journal= {arXiv preprint arXiv:2510.02252}
}
</pre>{% endraw %}
