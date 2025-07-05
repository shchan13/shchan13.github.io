---
layout: archive
title: "Theoretical Study on Multi-objective Heuristic Search"
permalink: /publications/SkylerIJCAI24/
author_profile: true
---

{% include base_path %}

Shawn Skyler, Shahaf Shperberg, Dor Atzmon, Ariel Felner, Oren Salzman, **Shao-Hung Chan**, Han Zhang, Sven Koenig, William Yeoh, and Carlos Hernandez.  
<i>International Joint Conference on Artificial Intelligence (**IJCAI**)</i>, pages 7021--7028, 2024.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-SkylerIJCAI24');">bibtex</a>]
[[pdf](https://shchan13.github.io/files/SkylerIJCAI24.pdf)]
<div id="bibtex-SkylerIJCAI24" style="display:none">
<pre>@inproceedings{SkylerIJCAI24,
author    = {Shawn Skyler and Shahaf Shperberg and Dor Atzmon and Ariel Felner and Oren Salzman and Shao-Hung Chan and Han Zhang and Sven Koenig and William Yeoh and Carlos Hernandez},
title     = {Theoretical Study on Multi-objective Heuristic Search},
booktitle = {Proceedings of the International Joint Conference on Artificial Intelligence (IJCAI)},
pages     = {7021--7028},
year      = {2024}
}
</pre></div>

## Abstract

This paper provides a theoretical study on Multi-Objective Heuristic Search. We first classify states in the state space into must-expand, maybe-expand, and never-expand states and then transfer these definitions to nodes in the search tree. We then formalize a framework that generalizes A* to Multi-Objective Search. We study different ways to order nodes under this framework and its relation to traditional tie-breaking policies and provide theoretical findings. Finally, we study and empirically compare different ordering functions.
