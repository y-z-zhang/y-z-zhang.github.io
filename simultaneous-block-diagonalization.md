---
layout: post
title: Finest simultaneous block diagonalization
description: a fast, versatile, and symmetry-independent algorithm to characterize the stability of network synchronization patterns
image: assets/images/SBD.png
nav-menu: false
show_tile: true
order: 5
---

### Abstract
> The field of network synchronization has seen tremendous growth following the introduction of the master stability function (MSF) formalism, which enables the efficient stability analysis of synchronization in large oscillator networks.
> However, to make further progress we must overcome the limitations of this celebrated formalism, which focuses on global synchronization and requires both the oscillators and their interactions to be identical, while many systems of interest are inherently heterogeneous and exhibit complex synchronization patterns.
> Here, we establish a generalization of the MSF formalism that can characterize the stability of any cluster synchronization pattern, even when the oscillators and/or their interactions are nonidentical.
> The new framework is based on finding the finest simultaneous block diagonalization of matrices and does not rely on information about network symmetry.
> This leads to an algorithm that is error-tolerant and orders of magnitude faster than existing symmetry-based algorithms.
> As an application, we rigorously characterize the stability of chimera states in networks with multiple types of interactions.

### Code
Our Matlab code to find a finest simultaneous block diagonalization of matrices can be found [here](https://github.com/y-z-zhang/net-sync-sym).

### References
* **Y. Zhang** and A. E. Motter, *Symmetry-independent stability analysis of synchronization patterns*, [arXiv:2003.05461](https://arxiv.org/abs/2003.05461), to appear in SIAM Review
