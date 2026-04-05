---
layout: archive
title: "Dynamic Agent Grouping ECBS: Scaling Windowed Multi-Agent Path Finding with Completeness Guarantees"
permalink: /publications/ZhangAAAI26/
author_profile: true
---

{% include base_path %}

Tiannan Zhang, Rishi Veerapaneni, **Shao-Hung Chan**, Jiaoyang Li, and Maxim Likhachev.  
<i>AAAI Conference on Artificial Intelligence (**AAAI**)</i>, pages 29911--29920, 2026.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ZhangAAAI26');">bibtex</a>]
[[code](https://github.com/Rishi-V/Windowed-Complete-MAPF)]
[[pdf](https://shchan13.github.io/files/ZhangAAAI26.pdf)]
[[publisher](https://ojs.aaai.org/index.php/AAAI/article/view/40238)]
<div id="bibtex-ZhangAAAI26" style="display:none">
<pre>@inproceedings{ZhangAAAI26,
  author    = {Tiannan Zhang and Rishi Veerapaneni and Shao-Hung Chan and Jiaoyang Li and Maxim Likhachev},
  title     = {Dynamic Agent Grouping ECBS: Scaling Windowed Multi-Agent Path Finding with Completeness Guarantees},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)},
  pages     = {29911--29920},
  year      = {2026}
}
</pre></div>

## Abstract

Multi-Agent Path Finding (MAPF) is the problem of finding a set of collision-free paths for a team of agents. Although several MAPF methods that solve full-horizon MAPF have completeness guarantees, very few MAPF methods that plan partial paths have completeness guarantees. Recent work introduced the Windowed Complete MAPF (WinC-MAPF) framework, which shows how windowed optimal MAPF solvers (e.g., SS-CBS) can use heuristic updates and disjoint agent groups to maintain completeness even when planning partial paths. A core limitation of WinC-MAPF is that it requires optimal MAPF solvers. Our main contribution is to extend WinC-MAPF by showing how we can use a bounded suboptimal solver while maintaining completeness. In particular, we design Dynamic Agent Grouping ECBS (DAG-ECBS) which dynamically creates and plans agent groups while maintaining that each agent group solution is bounded suboptimal. We prove how DAG-ECBS can maintain completeness in the WinC-MAPF framework and can improve scalability compared to windowed ECBS which does not have completeness guarantees. More broadly, our work serves as a blueprint for designing more MAPF methods that can use the WinC-MAPF framework.
