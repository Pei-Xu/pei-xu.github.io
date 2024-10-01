---
permalink: /ContextVAE
title: "Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction"
excerpt: ""
author_profile: false
--- 


# Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction
{: #title}

<span>Pei Xu<sup>1</sup></span>,
<span>Jean-Bernard Hayet<sup>2</sup></span>,
<span>Ioannis Karamouzas<sup>1,3</sup></span>
{: .authors}

<span><sup>1</sup> Clemson University</span>,
<span><sup>2</sup> CIMAT</span>,
<span><sup>3</sup> University of California, Riverside</span>
{: .affiliations}


In _IEEE Robotics and Automation Letters_.\\
Also in _IEEE International Conference on Robotics and Automation_, 2024.

![](projects/ContextVAE/teaser.png)
{: .teasers}

## Abstract
![ICRA 2024](projects/ContextVAE/ICRA2024_logo_quick_links.png){: style="width:200px;float:right;max-width:100%;padding:0 0 10px 20px"}
Real-time, accurate prediction of human steering behaviors has wide applications, from developing intelligent traffic systems to deploying autonomous driving systems in both real and simulated worlds. In this paper, we present ContextVAE, a context-aware approach for multi-modal vehicle trajectory prediction. Built upon the backbone architecture of a timewise variational autoencoder, ContextVAE observation encoding employs a dual attention mechanism that accounts for the environmental context and the dynamic agents' states, in a unified way. By utilizing features extracted from semantic maps during agent state encoding, our approach takes into account both the social features exhibited by agents on the scene and the physical environment constraints to generate map-compliant and socially-aware trajectories. We perform extensive testing on the nuScenes prediction challenge, Lyft Level 5 dataset and Waymo Open Motion Dataset to show the effectiveness of our approach and its state-of-the-art performance. In all tested datasets, ContextVAE models are fast to train and provide high-quality multi-modal predictions in real-time.

[](https://arxiv.org/abs/2302.10873){: .paper-link title="Paper"}
[](https://github.com/xupei0610/contextvae){: .code-link title="Code"}
{: .links}

## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="max-width:560px;margin-top:20px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/5MOCsSQ9dbU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Bibtex
{% raw %}<pre class="bibtex">
@article{contextvae2023,
  title={Context-Aware Timewise {VAE}s for Real-Time Vehicle Trajectory Prediction},
  author={Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis},
  journal={IEEE Robotics and Automation Letters},
  year={2023},
  volume={8},
  number={9},
  pages={5440-5447},
  doi={10.1109/LRA.2023.3295990}
}
</pre>{% endraw %}

