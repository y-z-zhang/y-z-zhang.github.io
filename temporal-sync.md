---
layout: post
title: Temporal sync
description: designing temporal networks that synchronize under resource constraints
image: assets/images/temporal_sync.png
nav-menu: false
show_tile: true
order: 28
---

### Synopsis
From power grids to neuronal populations, getting in sync is critical to the function of many distributed systems. Being fundamentally a non-equilibrium process, synchronization costs energy and resources to maintain. It is thus important to find strategies that can synchronize a system at the lowest cost in resources. One such resource is the coupling budget available in a network to facilitate the interaction and communication between individual neurons or power generators. For time-independent interactions (often represented by static networks), there is a well-defined lower bound on the amount of coupling that is required for a system to synchronize stably. However, when the network itself is allowed to be dynamic, much less is known.

Our new results show that, by allowing the connection patterns to change over time (modeled as temporal networks), one can go below the fundamental limit set by the optimal static networks and synchronize a system more efficiently. Importantly, our design of these temporal networks is open loop, meaning that the same design works out-of-the-box for very different systems. For example, the same temporal network is expected to facilitate synchronization in both power grids and neuronal populations. This versatility makes our design a powerful tool that can be applied to systems that need to synchronize under tight resource constraints.


### Press
* [Getting in synch on a budget---SFI Research Brief](https://www.santafe.edu/news-center/news/research-brief-getting-synch-budget)

### Talk
Here is me presenting the work at the Systems Neuroscience and Complexity Seminar @ University of Sydney.

<div class="resp-container">
  <iframe class="resp-iframe" src="https://www.youtube.com/embed/UKkiCTF03jA" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### Code
The code accompanying this work can be found [here](https://github.com/y-z-zhang/temporal_sync).

### References
* __Y. Zhang__ and S. H. Strogatz, *Designing temporal networks that synchronize under resource constraints*, [Nat. Commun. 12, 3273 (2021)](https://doi.org/10.1038/s41467-021-23446-9)
