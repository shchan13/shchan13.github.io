---
layout: archive
title: "Nested ECBS for Bounded-Suboptimal Multi-Agent Path Finding"
permalink: /publications/ChanWoMAPF20/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Jiaoyang Li, Daniel Harabor, Peter J. Stuckey, Graeme Gange, Liron Cohen, and Sven Koenig.  
<i>IJCAI Workshop on Multi-Agent Path Finding (**WoMAPF**)</i>, 2020.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ChanWoMAPF20');">bibtex</a>]
[[pdf](https://jiaoyang-li.github.io/files/ChanWoMAPF20.pdf)]
<div id="bibtex-ChanWoMAPF20" style="display:none">
<pre>@inproceedings{ChanWoMAPF20,
  author    = {Shao-Hung Chan and Jiaoyang Li and Daniel Harabor and Peter J. Stuckey and Graeme Gange and Liron Cohen and Sven Koenig},
  title     = {Nested ECBS for Bounded-Suboptimal Multi-Agent Path Finding},
  booktitle = {IJCAI Workshop on Multi-Agent Path Finding},
  year      = {2020}
}
</pre></div>

## Abstract

Multi-Agent Path Finding (MAPF) is the problem of finding collision-free paths for multiple agents on a map. Conflict-Based Search (CBS) is a powerful, complete, and optimal MAPF solver, while Enhanced CBS (ECBS) improves the efficiency of CBS by only guaranteeing a bounded-suboptimal solution. Both MAPF solvers suffer from the weakness of repeatedly resolving the same collisions between the same agents. Merging agents into meta-agents and planing their paths in the joint state space can be used to overcome this problem. However, a joint-state-space MAPF solver makes resolving collisions within meta-agents inefficient. In this paper, we therefore propose Nested ECBS (NECBS), a nested architecture based on ECBS, where collisions within meta-agents are resolved with ECBS. NECBS preserves the important properties of ECBS, namely its completeness and bounded-suboptimality. Empirically, NECBS has a higher success rate than ECBS and its state-of-the-art variants for a runtime limit of 5 minutes.