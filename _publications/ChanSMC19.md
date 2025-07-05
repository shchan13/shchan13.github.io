---
layout: archive
title: "Real-time Obstacle Avoidance using Supervised Recurrent Neural Network with Automatic Data Collection and Labeling"
permalink: /publications/ChanSMC19/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Xiaoyue Xu, Ping-Tsang Wu, Ming-Li Chiang, and Li-Chen Fu.  
<i>IEEE International Conference on System, Man, and Cybernetics (**SMC**)</i>, pages 472-477, 2019.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ChanSMC19');">bibtex</a>]
  [[pdf](https://shchan13.github.io/files/ChanSMC19.pdf)]
  [[publisher](https://ieeexplore.ieee.org/abstract/document/8914281/)]
  <div id="bibtex-ChanSMC19" style="display:none">
  <pre>@inproceedings{ChanSMC19,
    author    = {Shao-Hung Chan and Xiaoyue Xu and Ping-Tsang Wu and Ming-Li Chiang and Li-Chen Fu},
    title     = {Real-time Obstacle Avoidance using Supervised Recurrent Neural Network with Automatic Data Collection and Labeling},
    booktitle = {IEEE International Conference on System, Man, and Cybernetics (SMC)},
    pages     = {472--477},
    year      = {2019}
  }</pre>
  </div>

## Abstract

In this paper, we propose an approach for real-time obstacle avoidance based on a supervised Recurrent Neural Network (RNN). As compared with conventional rule-based methods, fewer hyper parameters are needed to be tuned in the proposed system. On the other hand, as a data-driven system, our approach generates training data autonomously without manual labeling process. One of the main features of the proposed system is data generation, which can provide thousands of training data for supervised learning using simply 2D occupancy grid maps as input. To efficiently generate the path data, we utilize A* algorithm as the initial guide for the autonomous training process of the RNN model. After that, the trained model will perform local path planning to avoid
obstacles, which is tested in practical environments. With the proposed approach, we can effectively reduce the training time
while maintaining satisfactory performance. Simulated experiments show that the proposed system not only exhibits the features of A* algorithm in global aspect for path planning, but also performs obstacle avoidance in local aspect. As a by-product, the simulation results also show that the autonomously trained model can be successfully applied to many different scenarios.
