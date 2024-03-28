---
layout: archive
title: "Greedy Priority-Based Search for Suboptimal Multi-Agent Path Finding"
permalink: /publications/ChanSoCS23/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Roni Stern, Ariel Felner and Sven Koenig
<i>Symposium on Combinatorial Search (**SoCS**)</i>, pages 11-19, 2023.
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-ChanSoCS23');">bibtex</a>]
[[code](https://github.com/shchan13/GPBS)]
[[pdf](https://shchan13.github.io/files/2023-socs.pdf)]
[[publisher](https://ojs.aaai.org/index.php/SOCS/article/view/27278)]
<div id="bibtex-ChanSoCS23" style="display:none">
<pre>@inproceedings{ChanSoCS23,
  author    = {Shao-Hung Chan and Roni Stern and Ariel Felner and Sven Koenig},
  title     = {Greedy Priority-Based Search for Suboptimal Multi-Agent Path Finding},
  booktitle = {Proceedings of the Symposium on Combinatorial Search (SoCS)},
  pages     = {11--19},
  year      = {2023}
}
</pre></div>

## Abstract
Multi-Agent Path Finding (MAPF) is the problem of finding collision-free paths, one for each agent, in a shared environment, while minimizing their sum of travel times. Since solving MAPF optimally is NP-hard, researchers have explored algorithms that solve MAPF suboptimally but efficiently. Priority-Based Search (PBS) is the leading algorithm for this purpose. It finds paths for individual agents, one at a time, and resolves collisions by assigning priorities to the colliding agents and replanning their paths during its search. However, PBS becomes ineffective for MAPF instances with high densities of agents and obstacles. Therefore, we introduce Greedy PBS (GPBS), which uses greedy strategies to speed up PBS by minimizing the number of collisions between agents. We then propose techniques that speed up GPBS further, namely partial expansions, target reasoning, induced constraints, and soft restarts. We show that GPBS with all these improvements has a higher success rate than the state-of-the-art suboptimal algorithm for a 1-minute runtime limit, especially for MAPF instances with small maps and dense obstacles.