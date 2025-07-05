---
layout: archive
title: "Anytime Multi-Agent Path Finding with an Adaptive Delay-Based Heuristic"
permalink: /publications/Phan1AAAI25/
author_profile: true
---

{% include base_path %}

Thomy Phan, Benran Zhang, **Shao-Hung Chan**, and Sven Koenig.
<i>AAAI Conference on Artificial Intelligence (**AAAI**)</i>, pages 23286--23294, 2025.
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-Phan1AAAI25');">bibtex</a>]
[[code](https://github.com/JimyZ13/ADDRESS)]
[[pdf](https://shchan13.github.io/files/Phan1AAAI25.pdf)]
[[publisher](https://ojs.aaai.org/index.php/AAAI/article/view/21162)]
<div id="bibtex-Phan1AAAI25" style="display:none">
<pre>@inproceedings{Phan1AAAI25,
  author    = {Thomy Phan and Benran Zhang and Shao-Hung Chan and Sven Koenig},
  title     = {Anytime Multi-Agent Path Finding with an Adaptive Delay-Based Heuristic},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)},
  pages     = {23286--23294},
  year      = {2025}
}
</pre></div>

## Abstract

Anytime multi-agent path finding (MAPF) is a promising approach to scalable and collision-free path optimization in multi-agent systems. MAPF-LNS, based on Large Neighborhood Search (LNS), is the current state-of-the-art approach where a fast initial solution is iteratively optimized by destroying and repairing selected paths of the solution. Current MAPF-LNS variants commonly use an adaptive selection mechanism to choose among multiple destroy heuristics. However, to determine promising destroy heuristics, MAPF-LNS requires a considerable amount of exploration time. As common destroy heuristics are stationary, i.e., non-adaptive, any performance bottleneck caused by them cannot be overcome by adaptive heuristic selection alone, thus limiting the overall effectiveness of MAPF-LNS. In this paper, we propose Adaptive Delay-based Destroy-and-Repair Enhanced with Success-based Self-Learning (ADDRESS) as a single-destroy-heuristic variant of MAPF-LNS. ADDRESS applies restricted Thompson Sampling to the top-K set of the most delayed agents to select a seed agent for adaptive LNS neighborhood generation. We evaluate ADDRESS in multiple maps from the MAPF benchmark set and demonstrate cost improvements by at least 50% in large-scale scenarios with up to a thousand agents, compared with the original MAPF-LNS and other state-of-the-art methods.
