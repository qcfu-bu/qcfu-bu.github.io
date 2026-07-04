---
show: true
group: "Algebraic Formal Methods"
title: "On-the-fly GKAT"
desc: >-
  Guarded Kleene Algebra with Tests (GKAT) promises faster equivalence
  checking than KAT, but its decision algorithms are often slower in practice
  due to normalization overhead. We introduce a novel on-the-fly algorithm
  that performs bisimulation greedily and defers normalization until strictly
  necessary. The resulting rust-gkat tool runs orders of magnitude faster
  than existing KAT solvers.
zenodo: 18304183
date: 2024-01-12 00:01:00 +0800
---
