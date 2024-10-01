---
permalink: /SocialVAE
title: "SocialVAE: Human Trajectory Prediction using Timewise Latents"
excerpt: ""
author_profile: false
--- 

# SocialVAE: Human Trajectory Prediction using Timewise Latents
{: #title}

<span>Pei Xu<sup>1,3</sup></span>,
<span>Jean-Bernard Hayet<sup>2</sup></span>,
<span>Ioannis Karamouzas<sup>1</sup></span>
{: .authors}

<span><sup>1</sup> Clemson University</span>,
<span><sup>2</sup> CIMAT</span>,
<span><sup>3</sup> Roblox</span>
{: .affiliations}

In _the 17th European Conference on Computer Vision_, 2022.

![](projects/SocialVAE/teaser.png){: style="margin-bottom:10px"}\\
![](projects/SocialVAE/overview.png)
{: .teasers}

## Abstract
![ECCV 2021](projects/SocialVAE/ECCV-logo3.png){: style="width:200px;float:right;max-width:100%;padding:0 0 10px 20px"}
Predicting pedestrian movement is critical for human behavior analysis and also for safe and efficient human-agent interactions. However, despite significant advancements, it is still challenging for existing approaches to capture the uncertainty and multimodality of human navigation decision making. In this paper, we propose SocialVAE, a novel approach for human trajectory prediction. The core of SocialVAE is a timewise variational autoencoder architecture that exploits stochastic recurrent neural networks to perform prediction, combined with a social attention mechanism and backward posterior approximation to allow for better extraction of pedestrian navigation strategies. We show that SocialVAE improves current state-of-the-art performance on several pedestrian trajectory prediction benchmarks, including the ETH/UCY benchmark, the Stanford Drone Dataset and SportVU NBA movement dataset.


[](https://arxiv.org/abs/2203.08207){: .paper-link title="Paper"}
[](https://github.com/xupei0610/SocialVAE){: .code-link title="Code"}
{: .links}


## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/nXrreTmXktM?si=c66LWojq8FxsGBDN" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>


## Poster
[![](projects/SocialVAE/poster.png){: style="max-width:100%"}](projects/SocialVAE/poster.pdf)


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
