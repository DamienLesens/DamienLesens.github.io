---
title: "Algorithms for symmetric Birkhoff-von Neumann decomposition of symmetric doubly stochastic matrices"
collection: publications
permalink: /publication/2025-01-algos-for-sym-BvN-decomp-of-sym-matrices
excerpt: ''
date: 2025-01
venue: 'SIAM Journal on Matrix Analysis and Applications'
slidesurl: ''
paperurl: 'https://inria.hal.science/hal-04877502/'
citation: 'Damien Lesens, Jérémy E. Cohen, Bora Uçar. Algorithms for symmetric Birkhoff-von Neumann decomposition of symmetric doubly stochastic matrices. RR-9566, Inria Lyon. 2025, pp.1-30. ⟨hal-04877502⟩'
---

The classical Birkhoff-von Neumann (BvN) decomposition writes a given doubly stochastic matrix as a convex combination of permutation matrices. We investigate the BvN decomposition of symmetric doubly stochastic matrices where the permutation matrices in the decomposition are also symmetric, called symBvN decomposition. This decomposition is not always possible. Two pioneering theoretical works establish the conditions under which such a decomposition is possible for the adjacency matrices of a special class of weighted undirected graphs. Building on these two works, we derive a practical algorithm for the same class of matrices. We also discuss a transformation which converts a given symmetric doubly stochastic matrix, with possibly nonzero diagonal elements, to be the adjacency matrix of an undirected graph. The adjacency matrix of the resulting graph admits a symBvN decomposition if and only if the given matrix does so. This transformation and the practicality of the derived algorithm allow us to propose the first-ever, to the best of our knowledge, implementation of algorithms for symmetric BvN decomposition of symmetric doubly stochastic matrices. We present a set of experiments on decomposing symmetric doubly stochastic matrices as a convex combination of symmetric permutation matrices. Our experiments suggest that the proposed algorithm is as effective as the state-of-the-art algorithms for the classical BvN decomposition.