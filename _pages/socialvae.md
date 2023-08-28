---
permalink: /SocialVAE
title: "PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network"
excerpt: ""
author_profile: false
redirect_from: 
 - /socialvae
 - /SOCIALVAE
--- 


# PFPN: Continuous Control of Physically Simulated Characters using Particle Filtering Policy Network

<p class="author">
Pei Xu<sup>1</sup>, Ioannis Karamouzas<sup>1</sup>
</p>

<p class="affiliation">
<sup>1</sup> Clemson University
</p>

In _ACM SIGGRAPH Conference on Motion, Interaction and Games_, 2021.<br />
Also _NeurIPS Deep Reinforcement Learning Workshop_, 2021.

<div class="m10"></div>
<div class="teaser">

| Predictions | Heatmap | Attention |
|-------------|---------|-----------|
| ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_1.png) | ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_1_heatmap.png) | ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_1_att.png) |
| ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_2.png) | ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_2_heatmap.png) | ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_2_att.png) |
| ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_3.png) | ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_3_heatmap.png) | ![](https://github.com/xupei0610/SocialVAE/gallery/scenario_nba_3_att.png) |

</div>

<div class="m10"></div>
## Abstract
<div class="abstract">
Predicting pedestrian movement is critical for human behavior analysis and also for safe and efficient human-agent interactions. However, despite significant advancements, it is still challenging for existing approaches to capture the uncertainty and multimodality of human navigation decision making. In this paper, we propose SocialVAE, a novel approach for human trajectory prediction. The core of SocialVAE is a timewise variational autoencoder architecture that exploits stochastic recurrent neural networks to perform prediction, combined with a social attention mechanism and backward posterior approximation to allow for better extraction of pedestrian navigation strategies. We show that SocialVAE improves current state-of-the-art performance on several pedestrian trajectory prediction benchmarks, including the ETH/UCY benchmark, the Stanford Drone Dataset and SportVU NBA movement dataset.
</div>


<div class="m10"></div>
<a href="https://arxiv.org/abs/2203.08207" class="paper-link" title="Paper"></a>
<a href="https://github.com/xupei0610/SocialVAE" class="code-link" title="Code"></a>


<div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/nXrreTmXktM?si=c66LWojq8FxsGBDN" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<div class="m10"></div>
## Poster
<a href="projects/SocialVAE/poster.pdf"><img src="projects/SocialVAE/poster.png" style="max-width:100%"></a>



<div class="m10"></div>
## Bibtex
<pre class="bibtex">
@inproceedings{socialvae2022,
    author={Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis},
    title={SocialVAE: Human Trajectory Prediction using Timewise Latents},
    booktitle={European Conference on Computer Vision},
    pages={511-528},
    year={2022}
}
</pre>
