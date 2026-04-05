---
layout: archive
title: "Operation Parallelism in Large Neighborhood Search for Anytime Multi-Agent Path Finding"
permalink: /publications/ChanMRS25/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Zhe Chen, Dian-Lun Lin, Yue Zhang, Daniel Harabor, Sven Koenig, Tsung-Wei Huang, and Thomy Phan.  
<i>IEEE International Symposium on Multi-Robot and Multi-Agent Systems (**MRS**)</i>, pages 1-7, 2025.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ChanMRS25');">bibtex</a>]
[[pdf](https://shchan13.github.io/files/ChanMRS25.pdf)]
[[publisher](https://ojs.aaai.org/index.php/SOCS/article/view/35975)]
<div id="bibtex-ChanMRS25" style="display:none">
<pre>@inproceedings{ChanMRS25,
  author    = {Shao-Hung Chan and Zhe Chen and Dian-Lun Lin and Yue Zhang and Daniel Harabor and Sven Koenig and Tsung-Wei Huang and Thomy Phan},
  title     = {Operation Parallelism in Large Neighborhood Search for Anytime Multi-Agent Path Finding},
  booktitle = {2025 IEEE International Symposium on Multi-Robot and Multi-Agent Systems (MRS)},
  pages     = {1--7},
  year      = {2025}
}
</pre></div>

## Abstract

Multi-Agent Path Finding (MAPF) is the problem of finding a set of collision-free paths for multiple agents in a shared environment while minimizing the sum of travel time. Since solving the MAPF problem optimally is NP-hard, anytime algorithms based on Large Neighborhood Search (LNS) are promising for finding good-quality solutions in a scalable manner by iteratively destroying and repairing paths. We propose Destroy-Repair Operation Parallelism for LNS (DROPLNS), a parallel framework that performs multiple destroy and repair operations concurrently to explore more regions of the search space within a limited time budget. Unlike classic MAPF approaches, DROP-LNS can leverage multi-threading hardware to enhance solution quality. We also formulate two variants of parallelism and conduct experimental evaluations. The empirical results show that DROP-LNS significantly outperforms the leading MAPF-LNS and LaCAM*, as well as other parallelism variants.
