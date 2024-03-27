---
layout: archive
title: "Parallelism in Multi-Agent Systems"
permalink: /research/parallel/
author_profile: true
---

{% include base_path %}

## Parallelism on Large Neighborhood Search

<img src="https://shchan13.github.io/images/research/DROPLNS_concept.png" title="Parallelism on LNS" style="float:right; width:250pt;padding-left:10px;"  alt="DROPLNS concept"/>

The current state-of-the-art anytime algorithm for MAPF is based on Large Neighborhood Search (LNS), which iteratively destroys and repairs a subset of collision-free paths in order to optimize the sum of travel times.
However, the destroy and repair operations can be time-consuming, and thus limit the effectiveness due to fewer iterations and scalability w.r.t. the number of agents.
In this paper, we propose **Destroy-Repair Operation Parallelism for LNS (DROP-LNS)**, a parallel framework that performs multiple destroy and repair processes simultaneously to explore a larger searching space under a limited time budget. Unlike MAPF-LNS, DROP-LNS is able to exploit parallelized hardware to improve the solution quality. We compare DROP-LNS to two parallelism variants (SYNC-LNS and DETA-LNS). The results show that DROP-LNS significantly outperforms bothe variants as well as the state-of-the-art.

*Publications:*
TBD
<!-- [1] [Diversity-Aware Planning](https://thomyphan.github.io/publication/2018-09-01-icac-gabor)  
[2] [Productive Fitness](https://thomyphan.github.io/publication/2021-01-01-naco-gabor)   -->

<div style="float: right;">
    <a href="https://thomyphan.github.io/research/"><strong>Back to Research</strong></a>
</div>