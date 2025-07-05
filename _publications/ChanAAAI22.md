---
layout: archive
title: "Flex Distribution for Bounded-Suboptimal Multi-Agent Path Finding"
permalink: /publications/ChanAAAI22/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Jiaoyang Li, Graeme Gange, Daniel Harabor, Peter J. Stuckey, and Sven Koenig.  
<i>AAAI Conference on Artificial Intelligence (**AAAI**)</i>, pages 9313-9322, 2022.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ChanAAAI22');">bibtex</a>]
[[code](https://github.com/shchan13/FEECBS)]
[[pdf](https://shchan13.github.io/files/ChanAAAI22.pdf)]
[[publisher](https://ojs.aaai.org/index.php/AAAI/article/view/21162)]
<div id="bibtex-ChanAAAI22" style="display:none">
<pre>@inproceedings{ChanAAAI22,
  author    = {Shao-Hung Chan and Jiaoyang Li and Graeme Gange and Daniel Harabor and Peter J. Stuckey and Sven Koenig},
  title     = {Flex Distribution for Bounded-Suboptimal Multi-Agent Path Finding},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)},
  pages     = {9313--9322},
  year      = {2022}
}
</pre></div>

## Abstract
Multi-Agent Path Finding (MAPF) is the problem of finding collision-free paths for multiple agents that minimize the sum of path costs. EECBS is a leading two-level algorithm that solves MAPF bounded-suboptimally, that is, within some factor w of the minimum sum of path costs C*. It uses focal search to find bounded-suboptimal paths on the low level and Explicit Estimation Search (EES) to resolve collisions on the high level. EES keeps track of a lower bound LB on C* to find paths whose sum of path costs is at most w LB in order to solve MAPF bounded-suboptimally. However, the costs of many paths are often much smaller than w times their minimum path costs, meaning that the sum of path costs is much smaller than w C*. In this paper, we therefore propose Flexible EECBS (FEECBS), which uses a flex (ible) distribution of the path costs (that relaxes the requirement to find bounded-suboptimal paths on the low level) in order to reduce the number of collisions that need to be resolved on the high level while still guaranteeing to solve MAPF bounded suboptimally. We address the drawbacks of flex distribution via techniques such as restrictions on the flex distribution, restarts of the high-level search with EECBS, and low-level focal-A* search. Our empirical evaluation shows that FEECBS substantially improves the efficiency of EECBS on MAPF instances with large maps and large numbers of agents.