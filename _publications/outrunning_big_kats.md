---
title:          "Outrunning Big KATs: Efficient Decision Procedures for Variants of GKAT"
date:           2026-04-10 00:01:00 +0800
selected:       true
pub:            "European Symposium on Programming"
pub_date:       "2026"
abstract: >-
    This paper presents several efficient decision procedures for trace equivalence of GKAT automata, which make use of on-the-fly symbolic techniques via SAT solvers. To demonstrate applicability of our algorithms, we designed symbolic derivatives for CF-GKAT, a practical system based on GKAT designed to validate control-flow transformations. We implemented the algorithms in Rust and evaluated them on both randomly generated benchmarks and real-world control-flow transformations. Indeed, we observed order-of-magnitude performance improvements against existing implementations for both KAT and CF-GKAT. Notably, our experiments also revealed a bug in Ghidra, an industry-standard decompiler, highlighting the practical viability of these systems.
cover:          /assets/images/covers/esop2026.png
authors:
- Cheng Zhang
- Qiancheng Fu
- Hang Ji
- Ines Santacruz Del Valle
- Alexandra Silva
- Marco Gaboardi
links:
  Paper: https://link.springer.com/chapter/10.1007/978-3-032-22723-2_14
---

