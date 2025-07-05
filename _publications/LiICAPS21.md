---
layout: archive
title: "Scalable Rail Planning and Replanning: Winning the 2020 Flatland Challenge"
permalink: /publications/LiICAPS21/
author_profile: true
---

{% include base_path %}

(**Winner of the NeurIPS'20 Flatland Challenge**).  
Jiaoyang Li, Zhe Chen, Yi Zheng, **Shao-Hung Chan**, Daniel Harabor, Peter J. Stuckey, Hang Ma, and Sven Koenig.  
<i>International Conference on Automated Planning and Scheduling (**ICAPS**)</i>, pages 477-485, 2021.  
A [short version](https://ojs.aaai.org/index.php/SOCS/article/view/18576) appeared at the <i>International Symposium on Combinatorial Search (**SoCS**)</i>, pages 179-181, 2021. <br>
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-LiICAPS21');">bibtex</a>]
[[code](https://github.com/Jiaoyang-Li/Flatland)] 
[[demo](https://youtu.be/Pw4GBL1UhPA)] 
[[media](https://viterbischool.usc.edu/news/2021/03/making-the-virtual-trains-run-on-time-usc-team-world-champs-in-ai-challenge/)] 
[[pdf](https://shchan13.github.io/files/LiICAPS21.pdf)]
[[publisher](https://ojs.aaai.org/index.php/ICAPS/article/view/15994)]
[[talk](https://slideslive.com/38942745/2020-flatland-challenge)] 
<div id="bibtex-LiICAPS21" style="display:none">
<pre>@inproceedings{LiICAPS21,
  author    = {Jiaoyang Li and Zhe Chen and Yi Zheng and Shao-Hung Chan and Daniel Harabor and Peter J. Stuckey and Hang Ma and Sven Koenig},
  title     = {Scalable Rail Planning and Replanning: Winning the 2020 Flatland Challenge},
  booktitle = {Proceedings of the International Conference on Automated Planning and Scheduling (ICAPS)},
  pages     = {477--485},
  year      = {2021}
}
</pre></div>  

<div style="text-align:center; width:100%; display: flex; align-items: center; justify-content: center;">
    <iframe style="max-width: 500px; aspect-ratio: 16/9;"
        src="https://www.youtube.com/embed/Pw4GBL1UhPA"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
    </iframe>
</div>

## Abstract

Multi-Agent Path Finding (MAPF) is the combinatorial problem of finding collision-free paths for multiple agents on a graph. This paper describes MAPF-based software for solving train planning and replanning problems on large-scale rail networks under uncertainty. The software recently won the 2020 Flatland Challenge, a NeurIPS competition trying to determine how to efficiently manage dense traffic on rail networks. The software incorporates many state-of-the-art MAPF or, in general, optimization technologies, such as prioritized planning, large neighborhood search, safe interval path planning, minimum communication policies, parallel computing, and simulated annealing. It can plan collision-free paths for thousands of trains within a few minutes and deliver deadlock-free actions in real-time during execution. 