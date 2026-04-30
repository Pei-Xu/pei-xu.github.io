---
permalink: /MUSIC
title: "MUSIC: Learning Muscle-Driven Dexterous Hand Control"
excerpt: ""
author_profile: false
redirect_from: 
 - /piano
 - /PIANO
 - /music
--- 

# MUSIC: Learning Muscle-Driven Dexterous Hand Control
{: #title}

<span>Pei Xu*<sup>1</sup></span>,
<span>Yufei Ye*<sup>1</sup></span>,
<span>Shuchun Sun<sup>2</sup></span>,
<span>Yu Ding<sup>1</sup></span>,
<span>Elizabeth Schumann<sup>1</sup></span>,
<span>C. Karen Liu<sup>1</sup></span>
{: .authors}

<span><sup>1</sup> Stanford University</span>,
<span><sup>2</sup> Clemson University</span>
{: .affiliations}

In _ACM Transactions on Graphics (Proceedings of SIGGRAPH 2026)_


![](projects/MUSIC/teaser.png)
{: .teasers}

## Abstract
<!-- ![TOG](projects/MUSIC/tog.cover.jpg){: style="width:300px;float:right;max-width:100%;padding:0 0 10px 20px"} -->
![SIGGRAPH 2026](projects/MUSIC/siggraph2026_logo.jpg){: style="float:right;width:200px;max-width:100%;padding:20px 0 10px 20px;clear:both"}
We present a data-driven approach for physics-based, muscle-driven dexterous control that enables musculoskeletal hands to perform precise piano playing for novel pieces of music outside the reference dataset. Our approach combines high-frequency muscle-level control with low-frequency latentspace coordination in a hierarchical architecture. At the low level, general single-hand policies are trained via reinforcement learning to generate dynamic muscle-tendon activations while tracking trajectories from a large reference motion dataset. The resulting tracking policies are then distilled into variational autoencoder (VAE) models, yielding smooth and structured latent spaces that abstract away low-level muscle dynamics. For the high level, we train piece-specific policies to operate in this latent space, coordinating bimanual motions based on specific goals, denoted by note events extracted from given musical scores, to synthesize performances beyond the reference data. High-level control is formulated as a decentralized multiagent reinforcement learning problem combined with adversarial learning for motion imitation. In addition, we present an enhanced musculoskeletal hand model that supports fine control of fingers for accurate low-level motion tracking and diverse high-level motion synthesis. We evaluate the control pipeline of our approach on a diverse piano repertoire spanning multiple musical styles and technical demands. Results demonstrate that our approach can synthesize coordinated bimanual motions with accurate key presses, and achieve the state-of-the-art performance of piano playing in physics-based dexterous control, while generalizing to sheet music that is not presented in the reference dataset. We also show that our musculoskeletal hand model demonstrates superior biomechanical stability and tracking precision compared to the existing model, and validate that our musculoskeletal hand model and muscle-driven controller can generate physiologically plausible activation patterns that align with human electromyography (EMG) recordings when subjects perform multiple tasks.


[](https://arxiv.org/abs/2604.23886){: .paper-link title="Paper"}
[](https://github.com/xupei0610/music){: .code-link title="Code"}
{: .links}

## Video
<!-- <div style="max-width:640px">
<video id="primitive-dribble" width="100%" controls>
  <source src="projects/MUSIC/teaser.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div> -->

<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/tt1D36gE8zM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

# Method


![](projects/MUSIC/overview.png){: style="max-width:100%;margin:10px 0"}

The whole system of our framework is trained in three stages.
First, we learn a single-hand tracking policy that outputs high-frequency muscle activations for direct muscle-driven control.
Second, we perform on-policy distillation to obtain a VAE decoder as a low-level servo for muscle control, while taking as input the well-structured latent action.
Lastly, we train a piece-specific high-level controller over the latent to synthesize motions for piano playing.
While the first and third stages are conducted through reinforcement learning, the second stage is performed through supervised training.
Specifically, for high-level controller training in the third stage, we adopt a decentralized multi-agent setting to treat two hands as individual agents associated with independent policies, while taking a shared kinematic observation of two hands for coordinated control.


# Repertoire

<style>
.video_gallery {float:left;overflow:hidden;width:320px;max-width:100%;margin:10px}
</style>
<div style="margin:20px -10px 0 -10px">
<div class="video_gallery">
Bach - English Suite
<iframe width="320" height="180" src="https://www.youtube.com/embed/kXucMf6Ci-4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Bach - French Suite
<iframe width="320" height="180" src="https://www.youtube.com/embed/PEIuJI38wbg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Beethoven - Für Elise
<iframe width="320" height="180" src="https://www.youtube.com/embed/pI_dU7AOyXY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Beethoven - Piano Sonata No. 23
<iframe width="320" height="180" src="https://www.youtube.com/embed/p6KOk6u3sEA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Beethoven - Piano Sonata No. 3
<iframe width="320" height="180" src="https://www.youtube.com/embed/2MVCyjGPBKc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Brahms - Rhapsodie Op. 79
<iframe width="320" height="180" src="https://www.youtube.com/embed/MdlPAcJL7rE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Chopin - Waltz Op. 64
<iframe width="320" height="180" src="https://www.youtube.com/embed/OAPNgfeHN70" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Debussy - Suite Bergamasque Passpied
<iframe width="320" height="180" src="https://www.youtube.com/embed/wlWAwxtnUWc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Grieg - Lyric Pieces Op. 38
<iframe width="320" height="180" src="https://www.youtube.com/embed/zgGmy34bcA4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Joplin - Maple Leaf Rag
<iframe width="320" height="180" src="https://www.youtube.com/embed/siZEVp_DGvw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Mozart - Piano Sonata K. 280 in F Major
<iframe width="320" height="180" src="https://www.youtube.com/embed/OW8t4dQVxeQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Mozart - Piano Sonata K. 545 in A Major
<iframe width="320" height="180" src="https://www.youtube.com/embed/pLTVB4yqWv0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Mussorgsky - Pictures at Exhibition Bydlo
<iframe width="320" height="180" src="https://www.youtube.com/embed/Z2I5M7AwXuY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Scarlatti - Sonata in A Major K. 208
<iframe width="320" height="180" src="https://www.youtube.com/embed/d7V_JnS4Us4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Scriabin - Piano Sonata No. 5
<iframe width="320" height="180" src="https://www.youtube.com/embed/026xLVnlQIA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
</div>

## Bibtex
{% raw %}<pre class="bibtex">
@inproceedings{music,
    author = {Xu, Pei and Ye, Yufei and Sun, Shuchun and Ding, Yu and Schumann, Elizabeth and Liu, C. Karen},
    title = {{MUSIC}: Learning Muscle-Driven Dexterous Hand Control},
    journal = {ACM Transactions on Graphics},
    publisher = {ACM New York, NY, USA},
    year = {2026},
    volume = {45},
    number = {4},
    doi = {10.1145/3811402}
}
</pre>{% endraw %}
