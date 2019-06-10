---
layout: post
title: Optimal stability analysis of synchronization patterns
description: a fast, error-tolerant and symmetry-independent algorithm to optimally decouple variational equations
image: assets/images/cluster.png
nav-menu: false
---

### Abstract
> The field of network synchronization has seen tremendous growth in the past two decades following the introduction of the master stability function (MSF) formalism, which enables the efficient stability analysis of identical synchronization in large oscillator networks.
> However, to make further progress we must overcome the limitations of this celebrated formalism, which requires both the oscillators and their interactions, as well as the form of synchronization to be identical.
> Here, we establish a generalization of the MSF formalism that can probe synchronization stability when the oscillators, the interactions, or the synchronization states are nonidentical, under the unifying framework of finest simultaneous block diagonalization.
> In particular, we develop a symmetry-independent approach to cluster synchronization (i.e., nonidentical states), which, apart from finding optimal decomposition for any synchronization pattern, is also error-tolerant and orders-of-magnitude faster than existing symmetry-dependent methods based on irreducible representations.
> The new formalism also enables the systematic investigation of asymmetry-induced synchronization, where multiple types of oscillators or interactions are required to stabilize identical synchronization.
> The ability to treat heterogeneous systems and states under a unified and efficient framework will likely stimulate future research on collective dynamics in complex networks.

### Code
Our Matlab code to find the finest simultaneous block diagonalization of matrices can be found [here](https://github.com/y-z-zhang/net-sync-sym).

### References
* **Y. Zhang** and A. E. Motter, *Fast, unified, and symmetry-independent approach to network synchronization*, in preparation
