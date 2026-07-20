---
title:          "A Fast Quantitative Analyzer for NetKAT"
date:           2026-07-15 00:01:00 +0800
selected:       false
pub:            "arXiv"
pub_date:       "2026"
abstract: >-
    When designing a network, engineers must navigate trade-offs (e.g., one topology offers more aggregate bandwidth, another lower latency or better resilience) that demand reasoning about quantitative properties. We present a fast analyzer for quantitative network properties based on weighted NetKAT (wNetKAT), a domain-specific language that provides a semantic foundation for quantitative reasoning by modeling network behavior using weights drawn from a semiring. At the core of our development is the design of a symbolic data structure -- weighted symbolic packet programs (wSPPs) -- that compactly represent the semantics of weighted policies, for which a direct implementation would be intractable. We show how to compute all policy constructs symbolically; unsurprisingly, the crux is Kleene star, for which we design a tailored algorithm. We further develop trace-carrying Pareto semirings, which compute multi-objective frontiers together with the network paths that realize them. We formalize the development in Lean and provide an optimized Rust implementation. Being parametric on a semiring, our implementation covers both classical and quantitative analyses: we show that it is competitive with KATch, a heavily optimized Boolean-reachability verifier, and orders of magnitude faster than McNetKAT and Storm on probabilistic analyses. A case study comparing Fat-tree and Jellyfish data-center topologies shows the framework supports multi-objective design-time analysis.
cover:          /assets/images/covers/arxiv.png
authors:
- Thomas Lu
- Qiancheng Fu
- Kevin Batz
- Oliver Bøving
- Tiago Ferreira
- Mark Moeller
- Nate Foster
- Alexandra Silva 
links:
  Paper: https://arxiv.org/abs/2607.14420
---

