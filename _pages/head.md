---
permalink: /HEAD
title: "Hand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching"
excerpt: ""
author_profile: false
redirect_from: 
 - /head
--- 

# Hand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching
{: #title}

<span>Sirui Chen\*</span>,
<span>Yufei Ye\*</span>,
<span>Zi-Ang Cao\*</span>,
<span>Jennifer Lew</span>,
<span>**Pei Xu**</span>,
<span>C. Karen Liu</span>
{: .authors}

<span>Stanford University</span>
{: .affiliations}

In _9th Annual Conference on Robot Learning_, 2025.


![](projects/HEAD/overview.png){: style="margin-bottom:10px"}\\
![](projects/HEAD/overview2.png)

## Abstract
![teaser](projects/HEAD/teaser.png){: style="width:300px;float:right;max-width:100%;padding:0 0 10px 20px;clear:both"}
![SIGGRAPH Asia 2024](projects/HEAD/corl25_logo.png){: style="float:right;width:120px;max-width:100%;padding:20px 0 10px 20px;clear:both"}
We propose Hand-Eye Autonomous Delivery (HEAD), a framework that learns navigation, locomotion, and reaching skills for humanoids, directly from human motion and vision perception data. We take a modular approach where the high-level planner commands the target position and orientation of the hands and eyes of the humanoid, delivered by the low-level policy that controls the whole-body movements. Specifically, the low-level whole-body controller learns to track the three points (eyes, left hand, and right hand) from existing large-scale human motion capture data while high-level policy learns from human data collected by Aria glasses. Our modular approach decouples the ego-centric vision perception from physical actions, promoting efficient learning and scalability to novel scenes. We evaluate our method both in simulation and in the real-world, demonstrating humanoid's capabilities to navigate and reach in complex environments designed for humans.


[](https://www.arxiv.org/abs/2508.03068){: .paper-link title="Paper"}
<!-- [](https://stanford-tml.github.io/HEAD){: .external-link title="Project Page"} -->
{: .links}

<!-- ## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/vchQ-FxH56w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div> -->

## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{head,
  title={Hand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching},
  author={Chen, Sirui and Ye, Yufei and Cao, Zi-Ang and Lew, Jennifer and Xu, Pei and Liu, C. Karen},
  booktitle={9th Annual Conference on Robot Learning},
  year={2025}
}
</pre>{% endraw %}
