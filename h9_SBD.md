---
layout: post
title: Optimal stability analysis of synchronization patterns
description: a fast, error-tolerant, and symmetry-independent algorithm to optimally decouple variational equations
image: assets/images/cluster.png
nav-menu: false
---

### Abstract
> The field of network synchronization has seen tremendous growth in the past two decades following the introduction of the master stability function (MSF) formalism, which enables the efficient stability analysis of identical synchronization in large oscillator networks.
> However, to make further progress we must overcome the limitations of this celebrated formalism, which focuses on identical synchronization and requires both the oscillators and their interactions to be identical.
> Here, we establish a generalization of the MSF formalism that can probe the stability of any cluster synchronization pattern when the oscillators or their interactions are allowed to be nonidentical.
> The new framework utilizes the finest simultaneous block diagonalization of matrices and does not rely on information about network symmetry.
> This leads to an algorithm that is error-tolerant and orders-of-magnitude faster than existing symmetry-based algorithms using irreducible group representations.
> As an application, we study chimera states in networks with multiple types of interactions and rigorously characterize their stability.

### Code
Our Matlab code to find a finest simultaneous block diagonalization of matrices can be found [here](https://github.com/y-z-zhang/net-sync-sym).

### References
* **Y. Zhang** and A. E. Motter, *Fast and symmetry-independent stability analysis of cluster synchronization patterns*, in preparation
