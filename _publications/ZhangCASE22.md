---
layout: archive
title: "A MIP-Based Approach for Multi-Robot Geometric Task-and-Motion Planning"
permalink: /publications/ZhangCASE22/
author_profile: true
---

{% include base_path %}

Hejia Zhang, **Shao-Hung Chan**, Jie Zhong, Jiaoyang Li, Sven Koenig, and Stefanos Nikolaidis.  
<i>IEEE International Conference on Automation Science and Engineering (**CASE**)</i>, pages 2102-2109, 2022.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ZhangCASE22');">bibtex</a>]
[[pdf](https://jiaoyang-li.github.io/files/2022-CASE.pdf)]
[[publisher](https://ieeexplore.ieee.org/document/9926661)]
<div id="bibtex-ZhangCASE22" style="display:none">
<pre>@inproceedings{ZhangCASE22,
  author    = {Hejia Zhang and Shao-Hung Chan and Jie Zhong and Jiaoyang Li and Sven Koenig and Stefanos Nikolaidis},
  title     = {A {MIP}-Based Approach for Multi-Robot Geometric Task-and-Motion Planning},
  booktitle = {Proceedings of the IEEE International Conference on Automation Science and Engineering (CASE)},
  pages     = {2102--2109},
  year      = {2022}
}
</pre></div>

## Abstract

We address multi-robot geometric task-and-motion planning (MR-GTAMP) problems in synchronous, monotone setups. The goal of the MR-GTAMP problem is to move objects with multiple robots to goal regions in the presence of other movable objects. To perform the tasks successfully and effectively, the robots have to adopt intelligent collaboration strategies, i.e., decide which robot should move which objects to which positions, and perform collaborative actions, such as handovers. To endow robots with these collaboration capabilities, we propose to first collect occlusion and reachability information for each robot as well as information about whether two robots can perform a handover action by calling motion-planning algorithms. We then propose a method that uses the collected information to build a graph structure which captures the precedence of the manipulations of different objects and supports the implementation of a mixed-integer program to guide the search for highly effective collaborative task-and-motion plans. The search process for collaborative task-and-motion plans is based on a Monte-Carlo Tree Search (MCTS) exploration strategy to achieve exploration-exploitation balance. We evaluate our framework in two challenging GTAMP domains and show that it can generate high-quality task-and-motion plans with respect to the planning time, the resulting plan length and the number of objects moved compared to two state-of-the-art baselines.
