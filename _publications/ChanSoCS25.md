---
layout: archive
title: "New Mechanisms in Flex Distribution for Bounded-Suboptimal Multi-Agent Path Finding"
permalink: /publications/ChanSoCS25/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**, Thomy Phan, Jiaoyang Li, and Sven Koenig.  
<i>International Symposium on Combinatorial Search (**SoCS**)</i>, in print, 2025.  

## Abstract

Multi-Agent Path Finding (MAPF) is the problem of finding a set of collision-free paths, one for each agent in a shared environment. Its objective is to minimize the sum of path costs (SOC), where the path cost of each agent is defined as the travel time from its start location to its target location. Explicit Estimation Conflict-Based Search (EECBS) is the leading algorithm for bounded-suboptimal MAPF, with the SOC of the solution being at most a user-specified factor *w* away from optimal. EECBS maintains sets of paths and a lower bound $LB$ on the optimal SOC. Then, it iteratively selects a set of paths whose SOC is at most *w* times *LB* and introduces constraints to resolve collisions. For each path in a set, EECBS maintains a lower bound on its optimal path that satisfies constraints. By finding an individually bounded-suboptimal path with cost at most a threshold of *w* times its lower bound, EECBS guarantees to find a bounded-suboptimal solution. To speed up EECBS, previous work uses *flex distribution* to increase the threshold. Though EECBS with flex distribution guarantees to find a bounded-suboptimal solution, increasing the thresholds may push the SOC beyond *w* times *LB*, forcing EECBS to switch among different sets of paths (whose SOC are still at most *w* times *LB*) instead of resolving collisions on a particular set of paths, and thus reducing efficiency. To address this issue, we propose *Conflict-Based Flex Distribution* that distributes flex in proportion to the number of collisions. We also estimate the extra travel time (i.e., delays) needed to satisfy constraints and propose *Delay-Based Flex Distribution*. On top of that, we propose *Mixed-Strategy Flex Distribution*, combining both in a hierarchical framework. We prove that EECBS with our new flex distribution mechanisms is complete and bounded-suboptimal. Our experiments show that our approaches outperform the original (greedy) flex distribution. Also, we redesign Focal-A* search from the previous work to improve $LB$ for a congested environment.
