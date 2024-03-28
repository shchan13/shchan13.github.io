---
layout: archive
title: "A Hierarchical Approach to Multi-Agent Path Finding"
permalink: /publications/ZhangHPLAN21/
author_profile: true
---

{% include base_path %}
                  
Han Zhang, Mingze Yao, Ziang Liu, Jiaoyang Li, Lucas Terr, **Shao-Hung Chan**, T. K. Satish Kumar and Sven Koenig.  
<i>ICAPS Workshop on Hierarchical Planning (**HPLAN**)</i>, 2021.  
A [short version](https://ojs.aaai.org/index.php/SOCS/article/view/18586 "Download pdf") appeared at the <i>International Symposium on Combinatorial Search (**SoCS**)</i>, pages 209-211, 2021.  
[[pdf](https://shchan13.github.io/files/ZhangHPLAN21.pdf)]
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ZhangHPLAN21');">bibtex</a>]
<div id="bibtex-ZhangHPLAN21" style="display:none">
<pre>@inproceedings{ZhangHPLAN21,
  author    = {Han Zhang and Mingze Yao and Ziang Liu and Jiaoyang Li and Lucas Terr and Shao-Hung Chan and T. K. Satish Kumar and Sven Koenig},
  title     = {A Hierarchical Approach to Multi-Agent Path Finding},
  booktitle = {ICAPS Workshop on Hierarchical Planning (HPLAN)},
  year      = {2021}
}
</pre></div>

## Abstract
The Multi-Agent Path Finding (MAPF) problem arises in many real-world applications, ranging from automated warehousing to multi-drone delivery. Solving the MAPF problem optimally is NP-hard, and existing optimal and bounded-suboptimal MAPF solvers thus usually do not scale to large MAPF instances. Greedy MAPF solvers scale to large MAPF instances, but their solution qualities are often bad. In this paper, we therefore propose a novel MAPF solver, Hierarchical Multi-Agent Path Planner (HMAPP), which creates a spatial hierarchy by partitioning the environment into multiple regions and decomposes a MAPF instance into smaller MAPF sub-instances for each region. For each sub-instance, it uses a bounded-suboptimal MAPF solver to solve it with good solution quality. Our experimental results show that HMAPP solves as large MAPF instances as greedy MAPF solvers while achieving better solution qualities on various maps.