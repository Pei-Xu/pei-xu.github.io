---
permalink: /contextvae
title: "Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction"
excerpt: ""
author_profile: false
--- 


# Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction

<p class="author">
Pei Xu<sup>1</sup>, Jean-Bernard Hayet<sup>2</sup>, Ioannis Karamouzas<sup>1,3</sup>
</p>

<p class="affiliation">
<sup>1</sup> Clemson University,  <sup>2</sup> CIMAT,  <sup>3</sup> University of California, Riverside
</p>


In _IEEE Robotics and Automation Letters_

<div class="teaser">
<img src="projects/contextvae/teaser.png" />
</div>

## Abstract
Real-time, accurate prediction of human steering behaviors has wide applications, from developing intelligent traffic systems to deploying autonomous driving systems in both real and simulated worlds. In this paper, we present ContextVAE, a context-aware approach for multi-modal vehicle trajectory prediction. Built upon the backbone architecture of a timewise variational autoencoder, ContextVAE observation encoding employs a dual attention mechanism that accounts for the environmental context and the dynamic agents' states, in a unified way. By utilizing features extracted from semantic maps during agent state encoding, our approach takes into account both the social features exhibited by agents on the scene and the physical environment constraints to generate map-compliant and socially-aware trajectories. We perform extensive testing on the nuScenes prediction challenge, Lyft Level 5 dataset and Waymo Open Motion Dataset to show the effectiveness of our approach and its state-of-the-art performance. In all tested datasets, ContextVAE models are fast to train and provide high-quality multi-modal predictions in real-time.


<a class="paper-link" href="https://arxiv.org/abs/2302.10873">Paper</a>
<a class="code-link" href="https://github.com/xupei0610/contextvae">Code</a>

<div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<div class="m10"></div>
## Bibtex
<pre class="bibtex">
@article{contextvae2023,
  title={Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction},
  author={Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis},
  journal={arXiv preprint arXiv:2302.10873},
  year={2023}
}
</pre>

