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
<span>Pei Xu<sup>1</sup></span>,
<span>Ruocheng Wang<sup>1</sup></span>
</p>

<p class="affiliation">
<span><sup>1</sup> Stanford University</span>
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
<a class="paper-link" href="#" title="Paper"></a>
<a class="code-link" href="https://github.com/xupei0610/guitar" title="Code"></a>

<div class="m10"></div>
## Video
<div style="max-width:560px">
<iframe width="560" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>


<div class="m10"></div>

<div style="float:left;overflow:hidden;width:320px;max-width:100%;margin:10px">
<iframe width="320" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="float:left;overflow:hidden;width:320px;max-width:100%;margin:10px">
<iframe width="320" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="float:left;overflow:hidden;width:320px;max-width:100%;margin:10px">
<iframe width="320" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="float:left;overflow:hidden;width:320px;max-width:100%;margin:10px">
<iframe width="320" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="float:left;overflow:hidden;width:320px;max-width:100%;margin:10px">
<iframe width="320" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div style="float:left;overflow:hidden;width:320px;max-width:100%;margin:10px">
<iframe width="320" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
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
