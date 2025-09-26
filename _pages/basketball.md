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
<!-- ![](projects/Basketball/3609020.cover.jpg){: style="width:300px;float:right;max-width:100%;padding:0 0 10px 20px"} -->
![](projects/Basketball/SA25_Logo_BlueH.png){: style="width:200px;float:right;max-width:100%;padding:0 0 10px 20px"} 
Learning a control policy for a multi-phase, long-horizon task, such as basketball maneuvers, remains challenging for reinforcement learning approaches due to the need for seamless policy composition and transitions between skills. A long-horizon task typically consists of distinct subtasks with well-defined goals, separated by transitional subtasks with unclear goals but critical to the success of the entire task. Existing methods like the mixture of experts and skill chaining struggle with tasks where individual policies do not share significant commonly explored states or lack well-defined initial and terminal states between different phases. In this paper, we introduce a novel policy integration framework to enable the composition of drastically different motor skills in multi-phase long-horizon tasks with ill-defined intermediate states. Based on that, we further introduce a high-level soft router to enable seamless and robust transitions between the subtasks. We evaluate our framework on a set of fundamental basketball skills and challenging transitions. Policies trained by our approach can effectively control the simulated character to interact with the ball and accomplish the long-horizon task specified by real-time user commands, without relying on ball trajectory references.

[](https://arxiv.org/abs/2305.03286){: .paper-link title="Paper"}
[](https://github.com/xupei0610/basketball){: .code-link title="Code"}
{: .links}


## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/2RBFIjjmR2I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Method


<style>
.video_gallery {float:left;overflow:hidden;width:320px;max-width:100%;margin:10px}
</style>

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
  <source src="projects/Basketball/dribble.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-pass">Pass</label>
<video id="primitive-pass" width="320" controls>
  <source src="projects/Basketball/dribble.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-catch">Catch</label>
<video id="primitive-catch" width="320" controls>
  <source src="projects/Basketball/dribble.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-rebound">Rebound</label>
<video id="primitive-rebound" width="320" controls>
  <source src="projects/Basketball/dribble.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
<div class="video_gallery">
<label for="primitive-defend">Locomotion + Defend</label>
<video id="primitive-defend" width="320" controls>
  <source src="projects/Basketball/dribble.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>

## Primitive Policies

## Policy Transitions

## Multi-Agent Interactive Control


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

