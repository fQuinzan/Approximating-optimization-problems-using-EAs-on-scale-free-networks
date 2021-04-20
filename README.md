# Approximating-optimization-problems-using-EAs-on-scale-free-networks

This repository provides a python implementation of our [GECCO 2017](https://dl.acm.org/doi/10.1145/3071178.3071257) paper titled ''Approximating Optimization Problems using EAs on Scale-Free Networks''.

## Abstract

It has been experimentally observed that real-world networks follow certain topological properties, such as small-world, power-law etc. To study these networks, many random graph models, such as Preferential Attachment, have been proposed.
Tn this paper, we consider the deterministic properties which capture power-law degree distribution and degeneracy. Networks with these properties are known as scale-free networks in the literature. Many interesting problems remain NP-hard on scale-free networks. We study the relationship between scale-free properties and the approximation-ratio of some commonly used evolutionary algorithms.
For the Vertex Cover, we observe experimentally that the (1+1) EA always gives the better result than a greedy local search, even when it runs for only O(nlog(n)) steps. We give the construction of a scale-free network in which a multi-objective algorithm and a greedy algorithm obtain optimal solutions, while the (1+1) EA obtains the worst possible solution with constant probability.
We prove that for the Dominating Set, Vertex Cover, Connected Dominating Set and Independent Set, the (1+1) EA obtains constant-factor approximation in expected run time O(nlog(n)) and O(n4) respectively. Whereas, GSEMO gives even better approximation than (1+1) EA in expected run time O(n3) for Dominating Set, Vertex Cover and Connected Dominating Set on such networks.

## Files and folders

- The folder graphExplorer contains the software used for the epxeriments.
- The folder sdata contains some sample graphs taken from [SNAP](http://snap.stanford.edu/) used in the experiments.

## Requirements

This software is written in C++17.
