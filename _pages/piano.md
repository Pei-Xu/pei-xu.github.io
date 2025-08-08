---
permalink: /ForElise
title: "FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance"
excerpt: ""
author_profile: false
redirect_from: 
 - /piano
 - /PIANO
 - /Piano
 - /elise
 - /FürElise
 - /FurElise
 - /forelise
 - /furelise
 - /fürelise
--- 

# FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance
{: #title}

<span>Ruocheng Wang*</span>,
<span>Pei Xu*</span>,
<span>Haochen Shi</span>,
<span>Elizabeth Schumann</span>,
<span>C. Karen Liu</span>
{: .authors}

<span>Stanford University</span>
{: .affiliations}

In _SIGGRAPH Asia_, 2024.


## Abstract
![teaser](projects/ForElise/teaser.png){: style="width:500px;float:right;max-width:100%;padding:0 0 10px 20px;clear:both"}
![SIGGRAPH Asia 2024](projects/Guitar/sa2024_logo.png){: style="float:right;width:200px;max-width:100%;padding:20px 0 10px 20px;clear:both"}
Piano playing requires agile, precise, and coordinated hand control that stretches the limits of dexterity. Hand motion models with the sophistication to accurately recreate piano playing have a wide range of applications in character animation, embodied AI, biomechanics, and VR/AR. In this paper, we construct a first-of-its-kind large-scale dataset that contains approximately 10 hours of 3D hand motion and audio from 15 elite-level pianists playing 153 pieces of classical music. To capture natural performances, we designed a markerless setup in which motions are reconstructed from multi-view videos using state-of-the-art pose estimation models. The motion data is further refined via inverse kinematics using the high-resolution MIDI key-pressing data obtained from sensors in a specialized Yamaha Disklavier piano. Leveraging the collected dataset, we developed a pipeline that can synthesize physically-plausible hand motions for musical scores outside of the dataset. Our approach employs a combination of imitation learning and reinforcement learning to obtain policies for physics-based bimanual control involving the interaction between hands and piano keys. To solve the sampling efficiency problem with the large motion dataset, we use a diffusion model to generate natural reference motions, which provide high-level trajectory and fingering (finger order and placement) information. However, the generated reference motion alone does not provide sufficient accuracy for piano performance modeling. We then further augmented the data by using musical similarity to retrieve similar motions from the captured dataset to boost the precision of the RL policy. With the proposed method, our model generates natural, dexterous motions that generalize to music from outside the training dataset.


[](https://arxiv.org/abs/2410.05791){: .paper-link title="Paper"}
[](https://for-elise.github.io){: .external-link title="Project Page"}
{: .links}

## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/vchQ-FxH56w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{piano,
    author = {Wang, Ruocheng and Xu, Pei and Shi, Haochen and Schumann, Elizabeth and Liu, C. Karen},
    title = {{F\"urElise}: Capturing and Physically Synthesizing Hand Motions of Piano Performance},
    booktitle = {SIGGRAPH Asia 2024 Conference Papers},
    articleno = {77},
    numpages = {11},
    series = {SA '24},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    year = {2024},
    doi = {10.1145/3680528.3687703}
}
</pre>{% endraw %}
