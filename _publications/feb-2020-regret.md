---
title: "Optimal anytime regret with two experts"
collection: publications
permalink: /publication/2020-02-20-regret	
venue: "IEEE Symposium on Foundations of Computer Science"
location: "Virtual Conference"
date: 'November 2020'
with: '<a href="https://www.cs.ubc.ca/~nickhar/">Nick Harvey</a>, <a href="https://www.cs.ubc.ca/~cvliaw">Chris Liaw</a>, and <a href="https://www.math.ubc.ca/~perkins/perkins.html">Edwin Perkins</a>'
links: '<a href="https://arxiv.org/abs/2002.08994">arXiv</a>'
abstract: 'hi'
---

---

The multiplicative weights method is an algorithm for the problem of prediction with expert advice. It achieves the optimal regret asymptotically if the number of experts is large, and the time horizon is known in advance.
Optimal algorithms are also known if there are exactly two, three or four experts, and the time horizon is known in advance.

In the anytime setting, where the time horizon is \emph{not} known in advance, algorithms can be obtained by the "doubling trick", but they are not optimal, let alone practical.
No minimax optimal algorithm was previously known in the anytime setting, regardless of the number of experts.


We design the first minimax optimal algorithm for minimizing regret in the anytime setting.
We consider the case of two experts, and prove that the optimal regret is $\gamma \sqrt{t} / 2$ at all time steps $t$, where $\gamma$ is a natural constant that arose 35 years ago in studying fundamental properties of Brownian motion.
The algorithm is designed by considering a continuous analogue of the regret problem, which is solved using ideas from stochastic calculus.
