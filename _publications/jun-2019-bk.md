---
title: "The Vickrey Auction with a Single Duplicate Bidder Approximates the Optimal Revenue"
venue: "ACM Conference on Economics and Computation"
location: "Phoenix, AZ"
date: 2019-06-24
year: 2019
with: '<a href="http://www.fuhuthu.com/">Hu Fu</a> and <a href="https://www.cs.ubc.ca/~cvliaw">Chris Liaw</a>'
links: '<a href="https://arxiv.org/abs/1905.03773">arXiv</a>, <a href="https://dl.acm.org/doi/10.1145/3328526.3329597">EC 2019</a>'
slides: '<a href="https://arxiv.org/abs/1905.03773">Slides by Chris Liaw</a>'
---

---

Bulow and Klemperer's well-known result states that, in a single-item auction where the $n$ bidders' values are independently and identically drawn from a regular distribution, the Vickrey auction with one additional bidder (a duplicate) extracts at least as much revenue as the optimal auction without the duplicate.  Hartline and Roughgarden, in their influential 2009 paper, removed the requirement that the distributions be identical, at the cost of allowing the Vickrey auction to recruit $n$ duplicates, one from each distribution, and relaxing its revenue advantage to a $2$-approximation.

In this work we restore Bulow and Klemperer's number of duplicates in Hartline and Roughgarden's more general setting.  We show that recruiting a duplicate from one of the distributions suffices for the Vickrey auction to $10$-approximate the optimal revenue.  We also show that in a $k$-unit auction, recruiting $k$ duplicates suffices for the VCG auction to $O(1)$-approximate the optimal revenue.

We also tighten the analysis for Hartline and Roughgarden's Vickrey auction with $n$ duplicates.  We show that, for two distributions, the Vickrey auction with two duplicates obtains at least $3/4$ of the optimal revenue.  This is tight by meeting a lower bound by Hartline and Roughgarden.  En route, we obtain a transparent analysis of their $2$-approximation, by a natural connection to Ronen's lookahead auction.

You may download a copy of the paper [here](https://sikander-randhawa.github.io/files/bk.pdf), or view it online on [arXiv]("https://arxiv.org/abs/1905.03773) or the [extended abstract](https://dl.acm.org/doi/10.1145/3328526.3329597) from EC'19.