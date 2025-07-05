---
layout: archive
title: "Counterfactual Online Learning for Open-Loop Monte-Carlo Planning"
permalink: /publications/Phan2AAAI25/
author_profile: true
---

{% include base_path %}

Thomy Phan, **Shao-Hung Chan**, and Sven Koenig.  
<i>AAAI Conference on Artificial Intelligence (**AAAI**)</i>, pages 26651--26658, 2025.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-Phan2AAAI25');">bibtex</a>]
[[code](https://github.com/thomyphan/counterfactual-planning)]
[[pdf](https://shchan13.github.io/files/Phan2AAAI25.pdf)]
[[publisher](https://ojs.aaai.org/index.php/AAAI/article/view/21162)]
<div id="bibtex-Phan2AAAI25" style="display:none">
<pre>@inproceedings{Phan2AAAI25,
  author    = {Thomy Phan and Shao-Hung Chan and Sven Koenig},
  title     = {Counterfactual Online Learning for Open-Loop Monte-Carlo Planning},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)},
  pages     = {26651--26658},
  year      = {2025}
}
</pre></div>

## Abstract

Monte-Carlo Tree Search (MCTS) is a popular approach to online planning under uncertainty. While MCTS uses statistical sampling via multi-armed bandits to avoid exhaustive search in complex domains, common closed-loop approaches typically construct enormous search trees to consider a large number of potential observations and actions. On the other hand, open-loop approaches offer better memory efficiency by ignoring observations but are generally not competitive with closed-loop MCTS in terms of performance -- even with commonly integrated human knowledge. In this paper, we propose Counterfactual Open-loop Reasoning with Ad hoc Learning (CORAL) for open-loop MCTS, using a causal multi-armed bandit approach with unobserved confounders (MABUC). CORAL consists of two online learning phases that are conducted during the open-loop search. In the first phase, an intent policy is learned based on preferred actions. In the second phase, a counterfactual policy is learned with MABUCs to make a final decision using the previously learned intent policy. We evaluate CORAL in four POMDP benchmark scenarios and compare it with closed-loop and open-loop alternatives. In contrast to standard open-loop MCTS, CORAL achieves competitive performance compared with closed-loop algorithms while constructing significantly smaller search trees.
