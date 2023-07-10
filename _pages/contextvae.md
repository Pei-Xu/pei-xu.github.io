---
permalink: /contextvae
title: "Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction"
excerpt: ""
author_profile: false
--- 


# Context-Aware Timewise VAEs for Real-Time Vehicle Trajectory Prediction
Pei Xu (1), Jean-Bernard Hayet (2), Ioannis Karamouzas (1, 3)

(1) Clemson University (2) CIMAT (3) University of California, Riverside

## Abstract
Real-time, accurate prediction of human steering behaviors has wide applications, from developing intelligent traffic systems to deploying autonomous driving systems in both real and simulated worlds. In this paper, we present ContextVAE, a context-aware approach for multi-modal vehicle trajectory prediction. Built upon the backbone architecture of a timewise variational autoencoder, ContextVAE observation encoding employs a dual attention mechanism that accounts for the environmental context and the dynamic agents' states, in a unified way. By utilizing features extracted from semantic maps during agent state encoding, our approach takes into account both the social features exhibited by agents on the scene and the physical environment constraints to generate map-compliant and socially-aware trajectories. We perform extensive testing on the nuScenes prediction challenge~\cite{nuscenes}, Lyft Level 5 dataset~\cite{lyft} and Waymo Open Motion Dataset~\cite{waymo} to show the effectiveness of our approach and its state-of-the-art performance. In all tested datasets, ContextVAE models are fast to train and provide high-quality multi-modal predictions in real-time.


[[Paper]](https://arxiv.org/abs/2302.10873)

<iframe width="560" height="315" src="https://www.youtube.com/embed/wg6laeYpnW8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

