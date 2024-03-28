---
layout: archive
title: "Flatland Competition 2020: MAPF and MARL for Efficient Train Coordination on a Grid World"
permalink: /publications/Laurent21/
author_profile: true
---

{% include base_path %}

Florian Laurent, Manuel Schneider, Christian Scheller, Jeremy Watson, Jiaoyang Li, Zhe Chen, Yi Zheng, **Shao-Hung Chan**, Konstantin Makhnev, Oleg Svidchenko, Vladimir Egorov, Dmitry Ivanov, Aleksei Shpilman, Evgenija Spirovska, Oliver Tanevski, Aleksandar Nikov, Ramon Grunder, David Galevski, Jakov Mitrovski, Guillaume Sartoretti, Zhiyao Luo, Mehul Damani, Nilabha Bhattacharya, Shivam Agarwal, Adrian Egli, Erik Nygren and Sharada Mohanty.  
<i>NeurIPS 2020 Competition and Demonstration Track</i>, PMLR, volume 133, pages 275-301, 2021.  
[<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-Laurent21');">bibtex</a>]
[[pdf](https://shchan13.github.io/files/Laurent21.pdf)]
[[publisher](http://proceedings.mlr.press/v133/laurent21a.html)]
<div id="bibtex-Laurent21" style="display:none">
<pre>@inproceedings{Laurent21,
  title     = {Flatland Competition 2020: MAPF and MARL for Efficient Train Coordination on a Grid World},
  author    = {Laurent, Florian and Schneider, Manuel and Scheller, Christian and Watson, Jeremy and Li, Jiaoyang and Chen, Zhe and Zheng, Yi and Chan, Shao-Hung and Makhnev, Konstantin and Svidchenko, Oleg and Egorov, Vladimir and Ivanov, Dmitry and Shpilman, Aleksei and Spirovska, Evgenija and Tanevski, Oliver and Nikov, Aleksandar and Grunder, Ramon and Galevski, David and Mitrovski, Jakov and Sartoretti, Guillaume and Luo, Zhiyao and Damani, Mehul and Bhattacharya, Nilabha and Agarwal, Shivam and Egli, Adrian and Nygren, Erik and Mohanty, Sharada},
  booktitle = {Proceedings of the NeurIPS 2020 Competition and Demonstration Track},
  pages     = 	 {275--301},
  year      = 	 {2021},
  volume    = 	 {133},
  series    = 	 {Proceedings of Machine Learning Research},
}
</pre></div> 

## Abstract
The Flatland competition aimed at finding novel approaches to solve the vehicle re-scheduling problem (VRSP). The VRSP is concerned with scheduling trips in traffic networks and the re-scheduling of vehicles when disruptions occur, for example the breakdown of a vehicle. While solving the VRSP in various settings has been an active area in operations research (OR) for decades, the ever-growing complexity of modern railway networks makes dynamic real-time scheduling of traffic virtually impossible. Recently, multi-agent reinforcement learning (MARL) has successfully tackled challenging tasks where many agents need to be coordinated, such as multiplayer video games. However, the coordination of hundreds of agents in a real-life setting like a railway network remains challenging and the Flatland environment used for the competition models these real-world properties in a simplified manner. Submissions had to bring as many trains (agents) to their target stations in as little time as possible. While the best submissions were in the OR category, participants found many promising MARL approaches. Using both centralized and decentralized learning based approaches, top submissions used graph representations of the environment to construct tree-based observations. Further, different coordination mechanisms were implemented, such as communication and prioritization between agents. This paper presents the competition setup, four outstanding solutions to the competition, and a cross-comparison between them.          
