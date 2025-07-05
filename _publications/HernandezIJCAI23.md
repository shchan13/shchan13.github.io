---
layout: archive
title: "Multi-objective Search via Lazy and Efficient Dominance Checks"
permalink: /publications/HernandezIJCAI23/
author_profile: true
---

{% include base_path %}

Carlos Hernández, William Yeoh, Jorge A. Baier, Ariel Felner, Oren Salzman, Han Zhang, **Shao-Hung Chan**, and Sven Koenig.  
<i>International Joint Conference on Artificial Intelligence (**IJCAI**)</i>, pages 7223-7230, 2023.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-HernandezIJCAI23');">bibtex</a>]
[[pdf](https://shchan13.github.io/files/HernandezIJCAI23.pdf)]
[[publisher](https://doi.org/10.24963/ijcai.2023/850)]
<div id="bibtex-HernandezIJCAI23" style="display:none">
<pre>@inproceedings{HernandezIJCAI23,
    author    = {Carlos Hernández and William Yeoh and Jorge A. Baier and Ariel Felner and Oren Salzman and Han Zhang and Shao-Hung Chan and Sven Koenig},
    title     = {Multi-objective Search via Lazy and Efficient Dominance Checks},
    booktitle = {Proceedings of the International Joint Conference on Artificial Intelligence (IJCAI)},
    pages     = {7223--7230},
    year      = {2023},
    doi       = {10.24963/ijcai.2023/850},
    url       = {https://doi.org/10.24963/ijcai.2023/850}
}</pre>
</div>

## Abstract

Multi-objective search can be used to model many real-world problems that require finding Pareto optimal paths from a specified start state to a specified goal state, while considering different costmetrics such as distance, time, and fuel. The performance of multi-objective search can be improved by making dominance checking—an operation necessary to determine whether or not a path dominates another—more efficient. This was shown in practice by BOA*, a state-of-the-art bi-objective search algorithm, which outperforms previously existing bi-objective search algorithms in part because it adopts a lazy approach towards dominance checking. EMOA*, a recent multi-objective search algorithm, generalizes BOA* to more-than-two objectives using AVL trees for dominance checking. In this paper, we first propose Linear-Time Multi-Objective A* (LTMOA*), an multi-objective search algorithm that implements a more efficient dominance checking than EMOA* using simple data structures like arrays. We then propose an even lazier approach towards dominance checking, and the resulting algorithm, LazyLTMOA*, distinguishes from EMOA* and LTMOA* by removing the dominance checking during node generation. Our experimental results show that LazyLTMOA* outperforms EMOA* by up to an order of magnitude in terms of runtime.