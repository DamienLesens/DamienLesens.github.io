---
title: "An Efficient Newton Algorithm for Nonnegative Matrix Factorization with the Kullback-Leibler Divergence"
collection: publications
permalink: /publication/2026-07-Efficient-Newton-Algorithm-for-NMFKL
excerpt: ''
date: 2026-7-15
venue: 'arxiv (pre-print)'
slidesurl: ''
paperurl: 'https://arxiv.org/pdf/2607.13919'
citation: 'Damien Lesens, Jérémy E Cohen, Bora Uçar. An Efficient Newton Algorithm for Nonnegative Matrix Factorization with the Kullback-Leibler Divergence. 2026. '
---

Nonnegative Matrix Factorization (NMF) is a fundamental tool in unsupervised learning, which approximates a nonnegative matrix by the product of two low-rank nonnegative factors. The Kullback-Leibler (KL) divergence is best suited to measure the data to model discrepancy when the decomposed data sample follows a Poisson distribution, which is the case for count datasets such as term-document matrices or images. Most KL-NMF algorithms in the literature minimize a separable majorant of the loss to find their next iterate. We argue that this method has reached its limits and propose to use instead the second-order Taylor expansion of the loss, leading to a Newton-type method. We minimize this non-separable surrogate by proposing a generalization of the well-known HALS algorithm. This yields an efficient KL-NMF algorithm which provably converges and which competes favorably with state-of-the-art algorithms on a large variety of datasets. 