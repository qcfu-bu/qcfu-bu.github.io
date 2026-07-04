---
title:          "A Dependently Typed Language with Dynamic Equality"
date:           2023-09-04 00:01:00 +0800
selected:       false
pub:            "Workshop on Type-Driven Development"
pub_date:       "2023"
abstract: >-
  Dependent type systems are powerful tools for preventing bugs in programs. Unlike other formal methods, dependent type systems can reuse the methodology and syntax familiar to functional programmers to construct formal proofs. However, usability issues, like confusing error messages, often arise from the conservative equalities required by such type theories. We address this issue by designing a dependently typed language where equality checking is delayed until runtime. What were once static errors can now be presented to programmers as warnings. When runtime failures occur, the blame system provides clear error messages indicating the exact static assumption violated during execution. We present several examples in this system, introduce novel correctness properties, and prove them for a fragment of the language. Our full system handles dependent indexed data and pattern matching, which are difficult for dependent gradual typing systems to manage. Finally, we have implemented a prototype of the language.
cover:          /assets/images/covers/acm-mark.svg
authors:
- Mark Lemay
- Qiancheng Fu
- William Blair
- Cheng Zhang
- Hongwei Xi
links:
  Paper: https://icfp23.sigplan.org/details/tyde-2023/7/A-Dependently-Typed-Language-with-Dynamic-Equality
---



