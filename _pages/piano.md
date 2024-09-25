---
permalink: /ForElise
title: "FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance"
excerpt: ""
author_profile: false
redirect_from: 
 - /piano
 - /elise
--- 

<style>
article.page {width:100%}
</style>

# FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance



<div class="m10"></div>
## Abstract
<div class="abstract">
<img src="projects/ForElise/teaser.png" style="width:500px;float:right;max-width:100%;padding:0 0 10px 20px;clear:both" />
<img src="projects/Guitar/sa2024_logo.png" style="float:right;width:200px;max-width:100%;padding:0 0 10px 20px;clear:both" />
Piano playing requires agile, precise, and coordinated hand control that stretches the limits of dexterity. Hand motion models with the sophistication to accurately recreate piano playing have a wide range of applications in character animation, embodied AI, biomechanics, and VR/AR. In this paper, we construct a first-of-its-kind large-scale dataset that contains approximately 10 hours of 3D hand motion and audio from 15 elite-level pianists playing 153 pieces of classical music. To capture natural performances, we designed a markerless setup in which motions are reconstructed from multi-view videos using state-of-the-art pose estimation models. The motion data is further refined via inverse kinematics using the high-resolution MIDI key-pressing data obtained from sensors in a specialized Yamaha Disklavier piano. Leveraging the collected dataset, we developed a pipeline that \revision{generalizes and accurately simulates}{can synthesize physically-plausible} hand motions for musical scores outside of the dataset. Our approach employs a combination of imitation learning and reinforcement learning to obtain policies for physics-based bimanual control involving the interaction between hands and piano keys. To solve the sampling efficiency problem with the large motion dataset, we use a diffusion model to generate natural reference motions, which provide high-level trajectory and fingering (finger order and placement) information. However, the generated reference motion alone does not provide sufficient accuracy for piano performance modeling. We then further augmented the data by using musical similarity to retrieve similar motions from the captured dataset to boost the precision of the RL policy. With the proposed method, our model generates natural, dexterous motions that generalize to music from outside the training dataset.
</div>

<div class="m10"></div>
<a class="external-link" href="#" title="Project Page"></a>
<a class="paper-link" href="#" title="Paper"></a>


<!-- <div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div> -->

<div class="m10" style="clear:both"></div>
## Bibtex
{% raw %}<pre class="bibtex">
@article{guitar,
    author = {Wang, Ruocheng and Xu, Pei and Shi, Haochen and Schumann, Elizabeth and Liu, C. Karen},
    title = {F\"urElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance},
    booktitle = {SIGGRAPH Asia 2024 Conference Papers (SA Conference Papers '24)},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    year = {2024},
    doi = {10.1145/3680528.3687703}
}
</pre>{% endraw %}