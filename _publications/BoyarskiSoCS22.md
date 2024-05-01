---
layout: archive
title: "On Merging Agents in Multi-Agent Pathfinding Algorithms"
permalink: /publications/BoyarskiSoCS22/
author_profile: true
---

{% include base_path %}

**Best Student Paper Award of SOCS 2022**  
Eli Boyarski, **Shao-Hung Chan**, Dor Atzmon, Ariel Felner and Sven Koenig.  
<i>International Symposium on Combinatorial Search (**SoCS**)</i>, pages 11-19, 2022.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-BoyarskiSoCS22');">bibtex</a>]
[[pdf](https://shchan13.github.io/files/BoyarskiSoCS22.pdf)]
[[publisher](https://ojs.aaai.org/index.php/SOCS/article/view/21747)]
<div id="bibtex-BoyarskiSoCS22" style="display:none">
<pre>@inproceedings{BoyarskiSoCS22,
  author    = {Eli Boyarski and Shao-Hung Chan and Dor Atzmon and Ariel Felner and Sven Koenig},
  title     = {On Merging Agents in Multi-Agent Pathfinding Algorithms},
  booktitle = {Proceedings of the International Symposium on Combinatorial Search (SoCS)},
  pages     = {11--19},
  year      = {2022}
}
</pre></div>

## Abstract
In Multi-Agent Pathfinding (MAPF), the task is to find non-colliding paths for a set of agents. This paper focuses on search-based MAPF algorithms from the Conflict-Based Framework, which is introduced here. A common technique in such algorithms is to merge a group of dependent agents into a meta-agent and plan non-colliding paths for the meta-agent using a low-level MAPF sub-solver. We analyze the patterns that emerge when agents are merged in an arbitrary order. We then introduce policies for choosing which agents or meta-agents to merge to achieve improved efficiency in three algorithms: Independence Detection (ID) and Improved Conflict-Based Search (ICBS), which are optimal, and Priority-Based Search (PBS), which is a fast suboptimal algorithm. Experimental results show a significant improvement in efficiency.