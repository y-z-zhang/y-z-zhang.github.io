---
layout: post
title: Topological control
description: manipulating synchronization patterns through minimal topological perturbations
image: assets/images/topo.png
nav-menu: false
show_tile: true
order: 25
---

### Overview
Different synchronization patterns are critical to the function of many interconnected systems (e.g., information processing in the brain). In practice, it is often important to be able to control these dynamical patterns without altering the node dynamics or imposing external control signal. In this work, we propose a new control strategy called topological control, which introduces minimal perturbations on the network structure so that the desired synchronization pattern can spontaneously emerge.

### Abstract
> Symmetries are ubiquitous in network systems and have profound impacts on the observable dynamics.
> At the most fundamental level, many synchronization patterns are induced by underlying network symmetry, and a high degree of symmetry is believed to enhance the stability of identical synchronization.
> Yet, here we show that the synchronizability of almost any symmetry cluster in a network of identical nodes can be enhanced precisely by breaking its structural symmetry.
> This counterintuitive effect holds for generic node dynamics and arbitrary network structure and is, moreover, robust against noise and imperfections typical of real systems, which we demonstrate by implementing a state-of-the-art optoelectronic experiment.
> These results lead to new possibilities for the topological control of synchronization patterns, which we substantiate by presenting an algorithm that optimizes the structure of individual clusters under various constraints.

### Code
Our simulated annealing algorithm to improve the synchronizability of oscillator networks through minimal link rewiring, removal, or addition can be found [here](https://github.com/y-z-zhang/optimize_sym_cluster).

### Press
* [Scientists Discover Exotic New Patterns of Synchronization---Quanta Magazine](https://www.quantamagazine.org/physicists-discover-exotic-patterns-of-synchronization-20190404/)
* [The Math of How Crickets, Starlings, and Neurons Sync Up---Wired](https://www.wired.com/story/the-math-of-how-crickets-starlings-and-neurons-sync-up)

### References
* J. D. Hart\*, __Y. Zhang__\*, R. Roy, and A. E. Motter, *Topological control of synchronization patterns: trading symmetry for stability*, [Phys. Rev. Lett. 122, 058301 (2019)](https://doi.org/10.1103/PhysRevLett.122.058301)
