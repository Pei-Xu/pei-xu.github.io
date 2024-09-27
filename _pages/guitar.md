---
permalink: /guitar
title: "Synchronize Dual Hands for Physics-Based Dexterous Guitar Playing"
excerpt: ""
author_profile: false
--- 


<style>
article.page {width:100%}
</style>


# Synchronize Dual Hands for Physics-Based Dexterous Guitar Playing

<p class="author">
<span>Pei Xu</span>,
<span>Ruocheng Wang</span>
</p>

<p class="affiliation">
<span>Stanford University</span>
</p>

In _SIGGRAPH Asia_, 2024.


<div class="m10"></div>
<div class="teaser">
<p><img src="projects/Guitar/teaser.png" /></p>
</div>


<div class="m10"></div>
## Abstract
<div class="abstract">
<img src="projects/Guitar/sa2024_logo.png" style="width:200px;float:right;max-width:100%;padding:10px 0 10px 20px" />
We present a novel approach to synthesize dexterous motions for physically simulated hands in tasks that require coordination between the control of two hands with high temporal precision. Instead of directly learning a joint policy to control two hands, our approach performs bimanual control through cooperative learning where each hand is treated as an individual agent. The individual policies for each hand are first trained separately, and then synchronized through latent space manipulation in a centralized environment to serve as a joint policy for two-hand control. By doing so, we avoid directly performing policy learning in the joint state-action space of two hands with higher dimensions, greatly improving the overall training efficiency. We demonstrate the effectiveness of our proposed approach in the challenging guitar-playing task. The virtual guitarist trained by our approach can synthesize motions from unstructured reference data of general guitar-playing practice motions, and accurately play diverse rhythms with complex chord pressing and string picking patterns based on the input guitar tabs that do not exist in the references. Along with this paper, we provide the motion capture data that we collected as the reference for policy training.
</div>

<div class="m10"></div>
<a class="paper-link" href="https://arxiv.org/abs/2409.16629" title="Paper"></a>
<a class="code-link" href="https://github.com/xupei0610/guitar" title="Code"></a>
<a class="dataset-link" href="https://github.com/xupei0610/guitar/dataset" title="Dataset"></a>

<div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/watch?v=r_y0P2pIeF8&list=PLLfEynalFz6j0X5Kiut0U3GLRxt3Oz_oa" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>


<style>
.video_gallery {float:left;overflow:hidden;width:320px;max-width:100%;margin:10px}
</style>
<div style="margin:20px -10px 0 -10px">
<div class="video_gallery">
Prelude I in C Major
<iframe width="320" height="180" src="https://www.youtube.com/embed/OoSN9WpI5wk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Spring Festival Overture
<iframe width="320" height="180" src="https://www.youtube.com/embed/le2_SwLMmnQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Johnny B. Goodie
<iframe width="320" height="180" src="https://www.youtube.com/embed/55tC6jTcua4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
House of the Rising Sun
<iframe width="320" height="180" src="https://www.youtube.com/embed/S2R-r8BWKto" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Don't Cry
<iframe width="320" height="180" src="https://www.youtube.com/embed/sw8ll2zTD0s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Beethoven Virus
<iframe width="320" height="180" src="https://www.youtube.com/embed/34_xZc7A-YA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Wipe Out
<iframe width="320" height="180" src="https://www.youtube.com/embed/iFamfwkGO4w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Snow (Hey Oh)
<iframe width="320" height="180" src="https://www.youtube.com/embed/c-YCn_fEZ1w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Hotel California
<iframe width="320" height="180" src="https://www.youtube.com/embed/eO1pd2JQOm4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Master of Puppets
<iframe width="320" height="180" src="https://www.youtube.com/embed/hTMpH5uSHSA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Summer
<iframe width="320" height="180" src="https://www.youtube.com/embed/urH6ytYCIPo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Super Mario Bro. Theme
<iframe width="320" height="180" src="https://www.youtube.com/embed/ZpiIJwF6L0k" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Corcovado
<iframe width="320" height="180" src="https://www.youtube.com/embed/7pB68y2M_Ig" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Sonata in F Major, MS84 No.14
<iframe width="320" height="180" src="https://www.youtube.com/embed/Z3drhzTgcwM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Turkish March
<iframe width="320" height="180" src="https://www.youtube.com/embed/XhDlA09xYa4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Capriccio Op.59 No.16
<iframe width="320" height="180" src="https://www.youtube.com/embed/0om9aGdgGCE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Canon in D Major
<iframe width="320" height="180" src="https://www.youtube.com/embed/rVDTDn_pAws" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Flight of the Bumblebee
<iframe width="320" height="180" src="https://www.youtube.com/embed/5d5-HgULC2s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="video_gallery">
Come As You Are
<iframe width="320" height="180" src="https://www.youtube.com/embed/8OM_0wfIumA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
</div>




<div class="m10" style="clear:both"></div>
## Bibtex
{% raw %}<pre class="bibtex">
@article{guitar,
    author = {Xu, Pei and Wang, Ruocheng},
    title = {Synchronize Dual Hands for Physics-Based Dexterous Guitar Playing},
    booktitle = {SIGGRAPH Asia 2024 Conference Papers (SA Conference Papers '24)},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    year = {2024},
    doi = {10.1145/3680528.3687692}
}
</pre>{% endraw %}
