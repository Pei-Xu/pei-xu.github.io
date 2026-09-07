---
permalink: /VLK
title: "VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes"
excerpt: ""
author_profile: false
redirect_from:
 - /vlk
---

# VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes
{: #title}

<span>Yen-Jen Wang<sup>*,1,2</sup></span>,
<span>Jiaman Li<sup>*,‡,1</sup></span>,
<span>Sirui Chen<sup>§,1,3</sup></span>,
<span>Takara E. Truong<sup>§,1,3</sup></span>,
<span>Pei Xu<sup>§,1</sup></span>,
<span>Pieter Abbeel<sup>†,1,2</sup></span>,
<span>Rocky Duan<sup>†,1</sup></span>,
<span>Koushil Sreenath<sup>†,1,2</sup></span>,
<span>Angjoo Kanazawa<sup>†,1,2</sup></span>,
<span>Carmelo Sferrazza<sup>†,1</sup></span>,
<span>Guanya Shi<sup>†,1,4</sup></span>,
<span>C. Karen Liu<sup>†,1,3</sup></span>
{: .authors}

<span><sup>1</sup>Amazon FAR</span>,
<span><sup>2</sup>University of California, Berkeley</span>,
<span><sup>3</sup>Stanford University</span>,
<span><sup>4</sup>Carnegie Mellon University</span>
{: .affiliations}

<span><sup>*</sup>Co-first authors. <sup>‡</sup>Project lead. <sup>§</sup>Equal contribution. <sup>†</sup>Amazon FAR Team Co-Lead.</span>
{: .affiliations}

In _Conference on Robot Learning_, 2026.

![VLK teaser](/projects/VLK/teaser.png)
{: .teasers}

## Abstract
![CoRL](/projects/VLK/corl_logo.png){: style="float:right;width:180px;max-width:100%;padding:20px 0 10px 20px;clear:both"}
Perception-based humanoid loco-manipulation requires connecting egocentric observations and task instructions to whole-body motion. Learning this mapping requires synchronized egocentric images, language commands, and robot-compatible kinematic trajectories, yet no existing data source provides this complete tuple at scale. We address this bottleneck by generating vision-language-kinematics (VLK) supervision synthetically in reconstructed scenes. Our pipeline leverages 3D Gaussian Splatting to reconstruct metric-scale indoor environments, synthesizes navigation and object-interaction trajectories using privileged scene information, and renders paired egocentric observations after the fact. We produce 48,000 paired trajectories with no human intervention and train a VLK policy that predicts short-horizon whole-body kinematic trajectories. A whole-body tracker converts these predictions into actions on the physical humanoid. We evaluate on the physical Unitree G1 performing navigation and single-object transport, demonstrating that synthesized interactions in reconstructed scenes provide effective supervision for sim-to-real perception-based humanoid loco-manipulation.

[](https://arxiv.org/abs/2606.30645){: .paper-link title="Paper"}
[](https://youtu.be/ZB6k_iMJP7M){: .video-link title="Video"}
[](https://vision-language-kinematics.github.io/){: .external-link title="Project Page"}
{: .links}

## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZB6k_iMJP7M" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{wang2026vlk,
  title={VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes},
  author={Wang, Yen-Jen and Li, Jiaman and Chen, Sirui and Truong, Takara E. and Xu, Pei and Abbeel, Pieter and Duan, Rocky and Sreenath, Koushil and Kanazawa, Angjoo and Sferrazza, Carmelo and Shi, Guanya and Liu, C. Karen},
  booktitle={Conference on Robot Learning},
  year={2026}
}
</pre>{% endraw %}
