---
permalink: /HOIFHLI
title: "Human-Object Interaction from Human-Level Instructions"
excerpt: ""
author_profile: false
redirect_from: 
 - /hihi
 - /hoifhli
--- 

# Human-Object Interaction from Human-Level Instructions
{: #title}

<span>Zhen Wu</span>,
<span>Jiaman Li</span>,
<span>Pei Xu</span>,
<span>C. Karen Liu</span>
{: .authors}

<span>Stanford University</span>
{: .affiliations}

In _IEEE/CVF International Conference on Computer Vision_, 2025.

![teaser](projects/hoifhli/teaser1.png)
{: .teasers}

## Abstract
![ICCV 2025](projects/hoifhli/iccv2025_logo.png){: style="float:right;width:200px;max-width:100%;padding:20px 0 10px 20px;clear:both"}
Intelligent agents must autonomously interact with the environments to perform daily tasks based on human-level instructions. They need a foundational understanding of the world to accurately interpret these instructions, along with precise low-level movement and interaction skills to execute the derived actions. In this work, we propose the first complete system for synthesizing physically plausible, long-horizon human-object interactions for object manipulation in contextual environments, driven by human-level instructions. We leverage large language models (LLMs) to interpret the input instructions into detailed execution plans. Unlike prior work, our system is capable of generating detailed finger-object interactions, in seamless coordination with full-body movements. We also train a policy to track generated motions in physics simulation via reinforcement learning (RL) to ensure physical plausibility of the motion. Our experiments demonstrate the effectiveness of our system in synthesizing realistic interactions with diverse objects in complex environments, highlighting its potential for real-world applications.


[](https://arxiv.org/pdf/2406.17840){: .paper-link title="Paper"}
[](https://hoifhli.github.io){: .external-link title="Project Page"}
{: .links}

## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/ztTsMeIgIGk?si=Vn8C8pZ_vN1B69C7" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{hoifhli,
  title={Human-Object Interaction from Human-Level Instructions},
  author={Wu, Zhen and Li, Jiaman and Xu, Pei and Liu, C. Karen},
  booktitle={2025 IEEE/CVF International Conference on Computer Vision (ICCV)},
  pages={1--11},
  year={2025}
}
</pre>{% endraw %}
