---
layout: archive
title: "Multi-Robot Geometric Task-and-Motion Planning for Collaborative Manipulation Tasks"
permalink: /publications/ZhangAR23/
author_profile: true
---

{% include base_path %}

Hejia Zhang, **Shao-Hung Chan**, Jie Zhong,  Jiaoyang Li, Peter Kolapo, Sven Koenig, Zach Agioutantis, Steven Schafrik, and Stefanos Nikolaidis.  
<i>Autonomous Robots</i>, volume 47, pages 1537-1558, 2023.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ZhangAR23');">bibtex</a>]
[[pdf](https://shchan13.github.io/files/ZhangAR23.pdf)]
[[publisher](https://doi.org/10.1007/s10514-023-10148-y)]
<div id="bibtex-ZhangAR23" style="display:none">
<pre>@article{ZhangAR23,
  author    = {Hejia Zhang and Shao-Hung Chan and Jie Zhong and Jiaoyang Li and Peter Kolapo and Sven Koenig and Zach Agioutantis and Steven Schafrik and Stefanos Nikolaidis.},
  title     = {Multi-robot geometric task-and-motion planning for collaborative manipulation tasks},
  journal   = {Autonomous Robots},
  year      = {2023},
  volume    = {47},
  pages     = {1537--1558},
  doi       = {10.1007/s10514-023-10148-y},
}
</pre></div>

## Abstract

We address multi-robot geometric task-and-motion planning (MR-GTAMP) problems in synchronous, monotone setups. The goal of the MR-GTAMP problem is to move objects with multiple robots to goal regions in the presence of other movable objects. We focus on collaborative manipulation tasks where the robots have to adopt intelligent collaboration strategies to be successful and effective, i.e., decide which robot should move which objects to which positions, and perform collaborative actions, such as handovers. To endow robots with these collaboration capabilities, we propose to first collect occlusion and reachability information for each robot by calling motion-planning algorithms. We then propose a method that uses the collected information to build a graph structure which captures the precedence of the manipulations of different objects and supports the implementation of a mixed-integer program to guide the search for highly effective collaborative task-and-motion plans. The search process for collaborative task-and-motion plans is based on a Monte-Carlo Tree Search (MCTS) exploration strategy to achieve exploration-exploitation balance. We evaluate our framework in two challenging MR-GTAMP domains and show that it outperforms two state-of-the-art baselines with respect to the planning time, the resulting plan length and the number of objects moved. We also show that our framework can be applied to underground mining operations where a robotic arm needs to coordinate with an autonomous roof bolter. We demonstrate plan execution in two roof-bolting scenarios both in simulation and on robots.
