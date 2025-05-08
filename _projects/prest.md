---
show: true
width: 12
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
    <p class="card-text">
      <ul id="horizontal">
        <li>
          <i class="fa fa-github"></i>
          <a href="https://github.com/qcfu-bu/PReST" target="_blank">Source Repository</a>
        </li>
        <li>
          <i class="fa-brands fa-docker"></i>
          <a href="https://zenodo.org/records/15151161" target="_blank">Docker Artifact</a>
        </li>
      </ul>
    </p>
  </div>
</div>

