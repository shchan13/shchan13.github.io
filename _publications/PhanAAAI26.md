---
layout: archive
title: "Truncated Counterfactual Learning for Anytime Multi-Agent Path Finding"
permalink: /publications/PhanAAAI26/
author_profile: true
---

{% include base_path %}

Thomy Phan, **Shao-Hung Chan**, and Sven Koenig.  
<i>AAAI Conference on Artificial Intelligence (**AAAI**)</i>, pages 29633--29641, 2026.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-PhanAAAI26');">bibtex</a>]
[[code](https://github.com/thomyphan/counterfactual-mapf-lns)]
[[pdf](https://shchan13.github.io/files/PhanAAAI26.pdf)]
[[publisher](https://ojs.aaai.org/index.php/AAAI/article/view/40207)]
<div id="bibtex-PhanAAAI26" style="display:none">
<pre>@inproceedings{PhanAAAI26,
  author    = {Thomy Phan and Shao-Hung Chan and Sven Koenig},
  title     = {Truncated Counterfactual Learning for Anytime Multi-Agent Path Finding},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)},
  pages     = {29633--29641},
  year      = {2026}
}
</pre></div>

## Abstract

Anytime multi-agent path finding (MAPF) is a promising approach to scalable and collision-free path optimization in multi-agent systems. MAPF-LNS, based on Large Neighborhood Search (LNS), is the current state-of-the-art approach where a fast initial solution is iteratively optimized by destroying and repairing selected paths, i.e., a neighborhood, of the solution. Delay-based MAPF-LNS has demonstrated particular effectiveness in generating promising neighborhoods via seed agents, according to their delays. Seed agents are selected using handcrafted strategies or online learning, where the former relies on human intuition about underlying structures, while the latter conducts black-box optimization, ignoring any structure. In this paper, we propose Truncated Adaptive Counterfactual K-ranked LEarning (TACKLE) to select seed agents via informed online learning by leveraging handcrafted strategies as human intuition. We show theoretically that TACKLE dominates its handcrafted and black-box learning counterparts in the limit. Our experiments demonstrate cost improvements of at least 60% in instances with one thousand agents, compared with state-of-the-art anytime solvers.
