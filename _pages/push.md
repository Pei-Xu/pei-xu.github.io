---
permalink: /push
title: "Push-and-Step: From RL-Based Balance Recovery to Physical Simulation of Dense Crowds"
excerpt: ""
author_profile: false
redirect_from: 
 - /PUSH
--- 

# Push-and-Step: From RL-Based Balance Recovery to Physical Simulation of Dense Crowds
{: #title}


<span>Alexis Jensen</span>, <span>Pei Xu</span>, <span>Charles Pontonnier</span>, <span>Julien Pettré</span>, <span>Ioannis Karamouzas</span>
{: .authors}

<span>Stanford University</span>
{: .affiliations}

In _IEEE/CVF Conference on Computer Vision and Pattern Recognition_, 2026.

<!-- ![teaser](projects/gmr/teaser1.png)
{: .teasers} -->

## Abstract
![ICRA 2026](projects/push/cvpr2026.png){: style="float:right;width:300px;max-width:100%;padding:20px 0 10px 20px;clear:both"}
We present a physics-based method for simulating full-body agents that recover balance by stepping or applying contact forces after being perturbed in dense crowds. While traditional 2D crowd simulations focus on navigation and social interactions in moderately dense settings, interactions in highly dense environments are predominantly physical, leading to push propagation, falls, and potential hazards. Existing models cannot capture how forces are transmitted through the body at the limb level. To address this, we use physics-based anthropomorphic simulations combined with a two-stage deep reinforcement learning framework. In the first stage, a policy is pre-trained using reference motion data and general balance rewards, enabling agents to handle a wide range of perturbations. In the second stage, an adaptive phase refines the policy to allow socially aware interactions, using hand contacts for stabilization guided by an online heuristic targeting neighbors’ shoulders based on mechanical efficiency and collision risk. Ablation studies validate the training framework and reward components, and simulations reproduce trends observed in empirical studies of push propagation. Our method scales to large populations, offering new opportunities to study safety and collective behavior in dense crowds. 


<!-- [](#){: .paper-link title="Paper"} -->
<!-- [](#){: .video-link title="Video"} -->
<!-- [](#){: .code-link title="Code"} -->
<!-- [](#){: .external-link title="Project Page"} -->
<!-- {: .links} -->

<!-- ## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="#" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div> -->

## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{gmr,
  title={Push-and-Step: From RL-Based Balance Recovery to Physical Simulation of Dense Crowds},
  author= {Alexis Jensen and Pei Xu and Charles Pontonnier and Julien Pettré and Ioannis Karamouzas},
  year= {2026},
  booktitle= {Proceedings of the Computer Vision and Pattern Recognition Conference}
}
</pre>{% endraw %}
