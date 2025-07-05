---
layout: archive
title: "Robust 2D Indoor Localization through Laser SLAM and Visual SLAM Fusion"
permalink: /publications/ChanSMC18/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Ping-Tsang Wu, and Li-Chen Fu.  
<i>IEEE International Conference on System, Man, and Cybernetics (**SMC**)</i>, pages 1263-1268, 2018.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ChanSMC18');">bibtex</a>]
  [[pdf](https://shchan13.github.io/files/ChanSMC18.pdf)]
  [[publisher](https://ieeexplore.ieee.org/abstract/document/8616217/)]
  <div id="bibtex-ChanSMC18" style="display:none">
  <pre>@inproceedings{ChanSMC18,
    author    = {Shao-Hung Chan and Ping-Tsang Wu and Li-Chen Fu},
    title     = {Robust 2D Indoor Localization through Laser SLAM and Visual SLAM Fusion},
    booktitle = {IEEE International Conference on System, Man, and Cybernetics (SMC)},
    pages     = {1263--1268},
    year      = {2018}
  }</pre>
  </div>

## Abstract

An approach of robust localization for mobile robot working in indoor is proposed in this paper. A novel method for laser SLAM and visual SLAM fusion is introduced to provide robust localization. This architecture can be applied to a situation where any two kinds of laser-based SLAM and monocular camera-based SLAM can be fused together instead of being limited to single specific SLAM algorithm. While laser-based SLAM and monocular camera-based SLAM have their own strengths and drawbacks, the integration of these two kinds of SLAM algorithm can then promote the algorithmic effectiveness. Instead of using feature matching methods to achieve fusion procedure, trajectories matching is proposed with an attempt to achieve the generalization over all different kinds of SLAM algorithms, since localization is a natural function associated with any SLAM algorithm. It turns out that the hereby proposed approach is very lightweight during the run time, and the calculation can run in real-time without unnecessary computation waste. The experimental results show the localization error in terms of the real distance can be less than 5%. Furthermore, through the experiment the proposed system can be shown able to improve the localization when the sensors are not very powerful.