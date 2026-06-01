---
title:          "Dependent Session Types for Verified Concurrent Programming"
date:           2025-10-23 00:01:00 +0800
selected:       true
pub:            "arXiv"
pub_date:       "2025"
abstract: >-
    We present TLLC which extends the Two-Level Linear dependent type theory (TLL) with session-based concurrency. Equipped with Martin-Löf style dependency, the session types of TLLC allow protocols to specify properties of communicated messages. When used in conjunction with the dependent type machinery already present in TLL, dependent session types facilitate a form of relational verification by relating concurrent programs with their idealized sequential counterparts. Correctness properties proven for sequential programs can be easily lifted to their corresponding concurrent implementations. TLLC makes session types a powerful tool for intrinsically verifying the correctness of data structures such as queues and concurrent algorithms such as map-reduce. To extend TLL with session types, we develop a novel formulation of intuitionistic session type which we believe to be widely applicable for integrating session types into other type systems beyond the context of TLLC. We study the meta-theory of our language, proving its soundness as both a term calculus and a process calculus. To demonstrate the practicality of TLLC, we have implemented a prototype compiler that translates TLLC programs into concurrent C code, which has been extensively evaluated.
cover:          /assets/images/covers/arxiv.png
authors:
- Qiancheng Fu
- Hongwei Xi
links:
  Paper: https://arxiv.org/abs/2510.19129
---


