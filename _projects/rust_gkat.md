---
show: true
width: 12
zenodo: 18304183
date: 2024-01-12 00:01:00 +0800
---
<div>
  <div class="card-body">
    <h5 class="card-title">On-the-fly GKAT</h5>
    <p class="card-text">
      The theory of Kleene Algebra with Tests (KAT) allows one to decide the
      equivalence of imperative programs using an elegant equational theory. The
      theory of Guarded Kleene Algebra with Tests (GKAT) promises to improve the
      performance of KAT by restricting its scope to the deterministic fragment of
      KAT. In practice, however, GKAT decision algorithms tend to be even slower than
      KAT algorithms due to the necessity of performing additional normalization
      steps. To solve the issue of using GKAT in practice, we introduce a novel
      on-the-fly algorithm for GKAT which performs bisimulation in a greedy
      manner and defers normalization to when it is absolutely necessary. We develop
      the rust-gkat tool in Rust. Through experiments, we show that our tool
      performs orders of magnitudes faster than existing KAT solvers.
    </p>
    <p class="card-text">
      <ul id="horizontal">
        <li>
          <i class="fa-brands fa-github"></i>
          <a href="https://github.com/qcfu-bu/rust-gkat" target="_blank">Source Repository</a>
        </li>
      </ul>
    </p>
  </div>
</div>


