---
show: true
width: 6
group: "Type Theory & Verification"
zenodo: 15151161
date: 2025-01-12 00:01:00 +0800
---
<div>
  <div class="card-body">
    <h5 class="card-title">Probabilistic Refinement Session Types</h5>
    <p class="card-text">
      We develop a novel theory of probabilistic refinement session types (PReST) to
      symbolically specify and reason about probabilistic message passing
      concurrent programs. The soundness of the PReST type system ensures that the
      probabilistic distributions specified in communication protocols are respected
      at runtime. Most surprisingly, probabilistic refinement types can even be used
      to statically verify parametric distributions such as the uniform distribution
      over {0, ..., k}. Using PReST we are able to specify probabilistic
      distributed protocols such as Leader Election, Bounded Retransmission and Crowd
      Forwarding.  We implement a type checker in OCaml using Z3 and CVC5 to
      efficiently solve complex generated constraints.
    </p>

  </div>
</div>

