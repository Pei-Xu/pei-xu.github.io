---
permalink: /SocialVAE
title: "SocialVAE: Human Trajectory Prediction using Timewise Latents"
excerpt: ""
author_profile: false
redirect_from: 
 - /socialvae
 - /SOCIALVAE
--- 

<style>
    article.page {width:100%}
</style>


# SocialVAE: Human Trajectory Prediction using Timewise Latents

<p class="author">
<span>Pei Xu<sup>1,3</sup></span>,
<span>Jean-Bernard Hayet<sup>2</sup></span>,
<span>Ioannis Karamouzas<sup>1</sup></span>
</p>

<p class="affiliation">
<span><sup>1</sup> Clemson University</span>,
<span><sup>2</sup> CIMAT</span>,
<span><sup>3</sup> Roblox</span>
</p>

In _the 17th European Conference on Computer Vision_, 2022.

<div class="m10"></div>
<div class="teaser">
<p><img src="projects/SocialVAE/teaser.png" /></p>
<div class="m10"></div>
<p><img src="projects/SocialVAE/overview.png" /></p>
</div>

<div class="m10"></div>
## Abstract
<div class="abstract">
<img src="projects/SocialVAE/ECCV-logo3.png" style="width:200px;float:right;max-width:100%;padding:0 20px 10px 20px" />
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
{% raw %}<pre class="bibtex">
@inproceedings{socialvae2022,
    author={Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis},
    title={{SocialVAE}: Human Trajectory Prediction using Timewise Latents},
    booktitle={European Conference on Computer Vision},
    pages={511-528},
    year={2022},
    organization={Springer},
    doi={10.1007/978-3-031-19772-7_30}
}
</pre>{% endraw %}
