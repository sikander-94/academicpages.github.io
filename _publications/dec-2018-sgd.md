---
title: "Tight analyses for non-smooth stochastic gradient descent"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'We show that returning the final iterate is sub-optimal when running SGD on non-smooth functions in both the strongly-convex and Lipschitz case. We also provide high probability upper bounds on the error of the final iterate and suffix average of SGD.'
paperurl: 'http://sikander-randhawa.github.io/files/sgd.pdf'
date: 2018-12-01
---


Consider the problem of minimizing functions that are Lipschitz and strongly convex, but not necessarily differentiable. We prove that after T steps of stochastic gradient descent, the error of the final iterate is O(\log(T)/T) with high probability. We also construct a function from this class for which the error of the final iterate of deterministic gradient descent is \Omega(\log(T)/T). This shows that the upper bound is tight and that, in this setting, the last iterate of stochastic gradient descent has the same general error rate (with high probability) as deterministic gradient descent. This resolves both open questions posed by [Shamir 2012].

An intermediate step of our analysis proves that the suffix averaging method achieves error O(1/T) with high probability, which is optimal (for any first-order optimization method). This improves results of [Rakhlin et al. 2012] and [Hazan and Kale 2014], both of which achieved error O(1/T), but only in expectation, and achieved a high probability error bound of O(log log(T)/T), which is suboptimal.

We prove analogous results for functions are Lipschitz and convex, but not necessarily strongly convex or differentiable. After T steps of stochastic gradient descent, the error of the final iterate is O(\log(T)/T^{0.5}) with high probability, and there exists a function for which the error of the final iterate of deterministic gradient descent is \Omega(log(T)/T^{0.5}).

[arXiv](https://arxiv.org/abs/1812.05217)

