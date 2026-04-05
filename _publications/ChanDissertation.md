---
layout: archive
title: "Flex Distribution for Bounded-Suboptimal Multi-Agent Path Finding"
permalink: /publications/ChanDissertation/
author_profile: true
---

{% include base_path %}

**Shao-Hung Chan**
[[pdf](https://shchan13.github.io/files/ChanDissertation.pdf)]

## Abstract

Multi-Agent Path Finding (MAPF) is the problem of finding a list of collision-free paths, one for each agent, that move them from their respective start locations to their respective target locations in a shared environment.
The objective of MAPF is to minimize the sum of (path) costs (SOC), where the cost of a path is defined as the travel time for an agent to move from its start location to its target location when it follows the path.
MAPF has numerous applications in coordinating multiple agents, including automated warehouses, traffic management, quadrotor swarms, robotic multi-arm manipulation, and even the navigation of animated characters.
However, solving MAPF optimally is NP-hard, which makes it a challenging problem.
To trade off solution quality for runtime, researchers have been working on bounded-suboptimal MAPF, which aims to find a solution for a MAPF instance whose SOC is at most a user-specified bounded-suboptimality factor $w$ larger than optimal.
In other words, bounded-suboptimal MAPF strikes a balance between the runtime required to find a solution and the guarantee on its quality.

Explicit Estimation Conflict-Based Search (EECBS) is a state-of-the-art bounded-suboptimal MAPF algorithm.
It is a two-level MAPF algorithm that is based on heuristic search.
Its strategy is to iteratively find paths for agents on the low level and resolve collisions that occur between them on the high level.
To resolve collisions, EECBS uses constraints to prevent agents from occupying locations at times that would result in collisions.
To guarantee that the solution is bounded-suboptimal, EECBS requires the SOC of paths to be at most $w$ larger than the SOC of the minimum-cost paths that satisfy the constraints.
It achieves this by finding an individually bounded-suboptimal path for each agent.
A path is individually bounded-suboptimal iff its cost is at most a user-specified bounded-suboptimality factor $w$ larger than the cost of a minimum-cost path that satisfies all constraints.
To find an individually bounded-suboptimal path, EECBS runs Focal Search on its low level, which returns a lower bound on the cost of a minimum-cost path that satisfies the constraints and a path whose cost is at most $w$ times the lower bound, which guarantees the path to be individually bounded-suboptimal.
As each path is individually bounded-suboptimal, the SOC of each agent's path is at most $w$ times the sum of their lower bounds, which guarantees the SOC of paths to be at most $w$ larger than the SOC of the minimum-cost paths that satisfy the constraints (thereby guaranteeing the solution it finds is bounded-suboptimal).

Despite being the state-of-the-art bounded-suboptimal MAPF algorithm, EECBS maintains its guarantee of finding bounded-suboptimal solutions by finding individually bounded-suboptimal paths.
However, the definition of bounded-suboptimal MAPF algorithms depends on the **sum** of path costs rather than the cost of each path.
Thus, in this dissertation, we propose *Flex Distribution*, an approach that relaxes the requirement that the paths of agents be individually bounded-suboptimal while still guaranteeing that it finds bounded-suboptimal solutions.
Given a list of paths, some of them can satisfy constraints with costs that are close to optimal.
In this case, Flex Distribution allows the other paths to have costs that exceed $w$ times their lower bounds, enabling these agents to avoid collisions.
Although these paths are no longer individually bounded-suboptimal, Flex Distribution still guarantees that the SOC of each agent's path is at most $w$ times the sum of their lower bounds, thereby guaranteeing EECBS to find a bounded-suboptimal solution.

We first propose *Greedy Flex Distribution*, which is an intuitive mechanism that allows EECBS to find paths with costs as high as possible, as long as the SOC of paths is at most $w$ times the sum of their lower bounds.
We also propose *Conflict-Based Flex Distribution*, which provides thresholds on costs based on the number of collisions between paths.
In this case, EECBS can only find paths with costs at most the thresholds.
We also propose *Delay-Based Flex Distribution*, which estimates the additional cost (i.e., delays) required for a path to satisfy the constraints and then determines its threshold accordingly.
Furthermore, we propose *Mixed-Strategy Flex Distribution*, which combines Conflict-Based Flex Distribution and Delay-Based Flex Distribution in a hierarchical framework.
We prove that EECBS, combined with our Flex Distribution mechanisms, is still guaranteed to find bounded-suboptimal solutions if such solutions exist.
Empirically, we demonstrate that EECBS with our Flex Distribution mechanisms outperforms the one without Flex Distribution in terms of success rates within a 120-second runtime limit.

To improve the efficiency of EECBS, another line of research involves generating *guidance heuristics* that help reduce collisions when EECBS finds paths on its low level.
In this dissertation, we combine Flex Distribution and guidance heuristics to further improve the efficiency of EECBS.
In particular, we propose a two-phase guidance framework as a general approach for computing guidance heuristics.
Then, we propose the *Flow-Based Guidance Framework*, which uses Flex Distribution when computing the *Flow-Based Guidance Heuristic*.
That is, we apply Flex Distribution in both computing guidance heuristics and EECBS.
Empirically, we demonstrate that EECBS with our Mixed-Strategy Flex Distribution becomes even more efficient when using our Flow-Based Guidance Heuristics.
We also demonstrate that EECBS with our Mixed-Strategy Flex Distribution is more efficient when using our Flow-Based Guidance Heuristics than when using other state-of-the-art guidance heuristics.
