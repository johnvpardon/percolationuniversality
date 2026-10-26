# Research status — 26 October 2026

The proposed classification is **false as stated** under standard chordal locality (deletions preserve the marked end neighborhoods). Critical percolation universality remains open. `PROJECT_DESCRIPTION.md` is unchanged.

## Proved and independently checked

- **Exact counterexample:** choose the affine SLE₆ metric from the terminal boundary tangent, with a default for nonregular end germs. The target germ survives finite exploration and locality deletions. The resulting ensemble has strong DMP, locality, translation covariance, and even covariance under every Euclidean similarity. It has no single affine normalizer, already for two targets on one disk (`progress.tex`, sections “An affine metric…” and “An exact counterexample…”).
- **Single-pair metric identification:** one marked bounded-domain curve law determines its affine metric up to scalar. First proved for Jordan boundaries by a strictly monotone Beta(1/3,1/3) boundary-swallowing race and harmonic uniqueness; extended to arbitrary bounded simply connected prime-end domains using quasiconformal compactness and Fatou limits.
- **Positive rigidity:** a homeomorphism preserving the full SLE₆ family is conformal (boundary race + Morera). A family obtained using one global homeomorphism is translation covariant only if that homeomorphism is real affine.
- **Boundary stability:** localized smooth rotations at the target exhibit a concrete discontinuity of the counterexample. Boundary continuity classifies the entire tangent-dependent affine ansatz as one fixed metric. Reversal and distant-target consistency also eliminate varying endpoint metrics within their stated affine ansatz.
- **Conditional identification:** DMP + locality + continuous local-martingale driving in every marked domain force quadratic variation `6t`, hence SLE₆. No quadratic-variation density assumption is needed. The driving-martingale premise is **not derived** from the original axioms.
- **A common metric within the affine-SLE ansatz:** if all marginals are already affine SLE₆, DMP + marked-chart continuity force source independence. Adding local target consistency, locality, and translations gives one fixed affine metric on all bounded prime-end domains. A separate regular-domain theorem replaces DMP/continuity by geometric reversal. Neither proves the affine-SLE ansatz itself.
- **Connection to actual percolation limits:** local agreement of two common-color discrete explorations passes to their marginal uniform curve limits, using almost-every-radius stopping continuity and then composition of stopping maps. This rules out the target-tangent example for simultaneous two-target percolation limits without requiring a limiting strong DMP theorem.
- **Initial-germ decoding:** dilation ergodicity identifies any prescribed countable collection of affine metrics from one arbitrarily short ordered initial trace germ; under standard joint Borel capacity coding, one decoder identifies every normalized metric. This does not decode a later unlabelled slit boundary.
- **Driving-function admissibility:** simple approximation proves continuous Loewner driving after affine deformation. A further quasiconformal/ergodicity argument proves infinite capacity lifetime, closing the `[0,∞)` time-domain issue.

## Important limits and failed approaches

- The exact counterexample is not asserted to arise from any fixed critical percolation model. Standard stronger percolation couplings can rule it out.
- Simply adding dilation, rotation, or reflection covariance does not repair the classification.
- Near-critical percolation gives a separate criticality obstruction, but configuration-valued convergence is not ordered-curve kernel convergence in random slit domains. The checked GPS source explicitly leaves ordered-interface uniqueness unproved. Do not claim an unconditional near-critical exploration-ensemble counterexample from those references alone.
- DMP does not make the one-dimensional driver Markov in conformally mapped slit domains. The proved deletion formula includes a geometry-dependent drift term.
- Tightness and mesh covariance make the **cluster set** dilation invariant; individual subsequential limits need not be. A uniqueness argument cannot assume their scale invariance without justification.

## Next investigations

1. Prove a structure theorem for arbitrary exploration laws, rather than assume each marginal is affine SLE₆. The conditional common-metric results isolate this as a central bottleneck.
2. Establish marked-domain/boundary stability and the strong conditional-kernel limit in random slit domains from uniform crossing bounds. The simpler local target-consistency transfer is already proved here under marginal curve convergence.
3. Find observables implying chart-local-martingale driving after one affine normalization; this would activate the conditional theorem.
4. Investigate metric recovery from later accessible frontier germs, or prove its impossibility. Initial ordered-germ recovery is established; no new target-consistent counterexample follows yet.

## Files and checks

`progress.tex` contains the detailed research record (34 compiled pages), including proofs, conditional results, caveats, and failed approaches. `final.tex` contains the polished core counterexample and global-deformation rigidity (8 compiled pages). Scratch investigations and build products live in `work/`, which is ignored by Git; all substantive findings are integrated into the two main LaTeX files.

Arguments were critically reviewed by independent agents and the primary agent. Both LaTeX documents compile with `latexmk -pdf -outdir=work/build <file>.tex`. Exact symbolic checks of the race diffusion, Beta density, deletion-chart coefficient, and slit derivatives pass. Compilation is not mathematical verification. The project specification and instructions remain unchanged.
