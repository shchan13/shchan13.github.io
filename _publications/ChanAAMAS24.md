---
layout: archive
title: "Anytime Multi-Agent Path Finding using Operation Parallelism in Large Neighborhood Search"
permalink: /publications/ChanAAMAS24/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Zhe Chen, Dian-Lun Lin, Yue Zhang, Daniel Harabor, Sven Koenig, Tsung-Wei Huang, Thomy Phan.  
<i>AAAI Conference on Artificial Intelligence (**AAAI**)</i>, pages 9313-9322, 2022.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ChanAAMAS24');">bibtex</a>]
[[pdf](https://shchan13.github.io/files/ChanAAMAS24.pdf)]
[[publisher](https://ojs.aaai.org/index.php/AAAI/article/view/21162)]
<div id="bibtex-ChanAAMAS24" style="display:none">
<pre>@inproceedings{ChanAAMAS24,
  author    = {Shao-Hung Chan and Zhe Chen and Dian-Lun Lin and Yue Zhang and Daniel Harabor and Sven Koenig and Tsung-Wei Huang and Thomy Phan},
  title     = {Anytime Multi-Agent Path Finding using Operation Parallelism in Large Neighborhood Search},
  booktitle = {Proceedings of the International Joint Conference on Autonomous Agents and Multiagent Systems (AAMAS)},
  year      = {2024}
}
</pre></div>

## Abstract

Multi-Agent Path Finding (MAPF) is the problem of finding a set of collision-free paths for multiple agents in a shared environment while improving the solution quality. The state-of-the-art anytime MAPF algorithm is based on Large Neighborhood Search (MAPF-LNS), which is a combinatorial search algorithm that iteratively destroys and repairs a subset of collision-free paths. In this paper, we propose Destroy-Repair Operation Parallelism for MAPF-LNS (DROP-LNS), a parallel framework that performs multiple destroy and repair operations concurrently to explore more regions of the search space and improve the solution quality. Unlike MAPF-LNS, DROP-LNS is able to exploit multiple threads during the search. The results show that DROP-LNS outperforms the state-of-the-art anytime MAPF algorithms, namely MAPF-LNS and LaCAM*, with respect to solution quality when terminated at the same runtime.
