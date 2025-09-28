---
permalink: /Basketball
title: "Learning to Ball: Composing Policies for Long-Horizon Basketball Moves"
excerpt: ""
author_profile: false
redirect_from: 
 - /basketball
 - /LearningToBall
 - /learningtoball
 - /Learning2Ball
 - /learning2ball
 - /LTB
 - /L2B
 - /LtB
 - /ltb
 - /l2b
--- 


# Learning to Ball: Composing Policies for Long-Horizon Basketball Moves
{: #title}

<span>Pei Xu<sup>1</sup></span>,
<span>Zhen Wu<sup>1</sup></span>,
<span>Ruocheng Wang<sup>1</sup></span>,
<span>Vishnu Sarukkai<sup>1</sup></span>,
<span>Kayvon Fatahalian<sup>1</sup></span>,
<span>Ioannis Karamouzas<sup>2</sup></span>,
<span>Victor Zordan<sup>3,4</sup></span>,
<span>C. Karen Liu<sup>1</sup></span>
{: .authors}

<span><sup>1</sup> Stanford University</span>, 
<span><sup>2</sup> University of California, Riverside</span>, 
<span><sup>3</sup> Roblox</span>, 
<span><sup>4</sup> Clemson University</span>
{: .affiliations}

In _ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2025)_

![](projects/Basketball/teaser.png)
{: .teasers}

## Abstract
<!-- ![](projects/Basketball/tog.cover.jpg){: style="width:300px;float:right;max-width:100%;padding:0 0 10px 20px"} -->
![](projects/Basketball/SA25_Logo_BlueH.png){: style="width:200px;float:right;max-width:100%;padding:0 0 10px 20px"} 
Learning a control policy for a multi-phase, long-horizon task, such as basketball maneuvers, remains challenging for reinforcement learning approaches due to the need for seamless policy composition and transitions between skills. A long-horizon task typically consists of distinct subtasks with well-defined goals, separated by transitional subtasks with unclear goals but critical to the success of the entire task. Existing methods like the mixture of experts and skill chaining struggle with tasks where individual policies do not share significant commonly explored states or lack well-defined initial and terminal states between different phases. In this paper, we introduce a novel policy integration framework to enable the composition of drastically different motor skills in multi-phase long-horizon tasks with ill-defined intermediate states. Based on that, we further introduce a high-level soft router to enable seamless and robust transitions between the subtasks. We evaluate our framework on a set of fundamental basketball skills and challenging transitions. Policies trained by our approach can effectively control the simulated character to interact with the ball and accomplish the long-horizon task specified by real-time user commands, without relying on ball trajectory references.

[](https://arxiv.org/abs/2305.03286){: .paper-link title="Paper"}
[](https://github.com/xupei0610/basketball){: .code-link title="Code"}
{: .links}


## Video
<div style="max-width:560px;margin-bottom:20px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/2RBFIjjmR2I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

[](https://bilibili.com){: .bilibili-link title="Bilibili"}

## Method

![](projects/Basketball/policy_learning.png){: style="max-width:1000px;margin-bottom:10px"}

Primitive Policy Learning from unstructued data collected from disparate sources without needing any reference of ball trajectories.

![](projects/Basketball/policy_transition.png){: style="max-width:1000px;margin-top:20px;margin-bottom:10px"}

Policy Transition Learning to support multi-phase long-horizon basketball-playing tasks involving diverse transitions with ill-defined intermediate states.

![](projects/Basketball/policy_composition.png){: style="max-width:600px;margin-top:20px;margin-bottom:10px"}

Policy Composition to enable seamless and robust transitions between subtasks.


<style>
.video_gallery {float:left;overflow:hidden;width:320px;max-width:100%;margin:10px}
</style>

## Primitive Policies
<div class="video_gallery">
<label for="primitive-dribble">Dribble</label>
<video id="primitive-dribble" width="320" controls>
  <source src="projects/Basketball/dribble.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-shoot">Shoot</label>
<video id="primitive-shoot" width="320" controls>
  <source src="projects/Basketball/shoot.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-rebound">Rebound</label>
<video id="primitive-rebound" width="320" controls>
  <source src="projects/Basketball/rebound.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-catch_pass">Catch & Pass</label>
<video id="primitive-catch_pass" width="320" controls>
  <source src="projects/Basketball/catch_pass.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-defend">Locomotion + Defend</label>
<video id="primitive-defend" width="320" controls>
  <source src="projects/Basketball/defend.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div style="clear:both"></div>

## Policy Transitions
<div class="video_gallery">
<label for="transition-dribble2shoot">Shoot off Dribble</label>
<video id="transition-dribble2shoot" width="320" controls>
  <source src="projects/Basketball/d2s.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-catch+pass">Pass & Catch</label>
<video id="primitive-catch+pass" width="320" controls>
  <source src="projects/Basketball/c+p.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="transition-catch2shoot">Shoot off Catch</label>
<video id="transition-catch2shoot" width="320" controls>
  <source src="projects/Basketball/c2s.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-dribble2pass">Pass off Dribble</label>
<video id="primitive-dribble2pass" width="320" controls>
  <source src="projects/Basketball/d2p.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="transition-catch2dribble">Catch to Dribble</label>
<video id="transition-catch2dribble" width="320" controls>
  <source src="projects/Basketball/c2d.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="transition-rebound2dribble">Rebound to Dribble</label>
<video id="transition-rebound2dribble" width="320" controls>
  <source src="projects/Basketball/r2d.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div style="clear:both"></div>


## Multi-Agent Interactive Control
<div class="video_gallery">
<video id="interact-control" width="320" controls>
  <source src="projects/Basketball/interact.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div style="clear:both"></div>


## Bibtex
{% raw %}<pre class="bibtex">
@article{basketball,
    author = {Xu, Pei and Wu, Zhen and Wang, Ruocheng and Sarukkai, Vishnu and Fatahalian, Kayvon and Karamouzas, Ioannis and Zordan, Victor and Liu, C. Karen},
    title = {Learning to Ball: Composing Policies for Long-Horizon Basketball Moves},
    journal = {ACM Transactions on Graphics},
    publisher = {ACM New York, NY, USA},
    year = {2024},
    volume = {44},
    number = {6},
    doi = {10.1145/3763367}
}
</pre>{% endraw %}
