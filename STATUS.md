# Research status — 26 October 2026

The proposed classification is **false as stated** under standard chordal locality (deletions preserve the marked end neighborhoods). Critical percolation universality remains open. `PROJECT_DESCRIPTION.md` is unchanged.

## Proved and independently checked

- **Exact counterexample:** choose the affine SLE₆ metric from the terminal boundary tangent, with a default for nonregular end germs. The target germ survives finite exploration and locality deletions. The resulting ensemble has strong DMP, locality, translation covariance, and even covariance under every Euclidean similarity. It has no single affine normalizer, already for two targets on one disk (`progress.tex`, sections “An affine metric…” and “An exact counterexample…”).
- **Single-pair metric identification:** one marked bounded Jordan-domain curve law determines its affine metric up to scalar. Proof: a strictly monotone Beta(1/3,1/3) boundary-swallowing race determines the conformal boundary map; harmonic uniqueness forces any affine symmetry to be a similarity.
- **Positive rigidity:** a homeomorphism preserving the full SLE₆ family is conformal (boundary race + Morera). A family obtained using one global homeomorphism is translation covariant only if that homeomorphism is real affine.
- **Boundary stability:** localized smooth rotations at the target exhibit a concrete discontinuity of the counterexample. Boundary continuity classifies the entire tangent-dependent affine ansatz as one fixed metric. Reversal and distant-target consistency also eliminate varying endpoint metrics within their stated affine ansatz.
- **Conditional identification:** DMP + locality + continuous local-martingale driving in every marked domain force quadratic variation `6t`, hence SLE₆. No quadratic-variation density assumption is needed. The driving-martingale premise is **not derived** from the original axioms.

## Important limits and failed approaches

- The exact counterexample is not asserted to arise from any fixed critical percolation model. Standard stronger percolation couplings can rule it out.
- Simply adding dilation, rotation, or reflection covariance does not repair the classification.
- Near-critical percolation gives a separate criticality obstruction, but configuration-valued convergence is not ordered-curve kernel convergence in random slit domains. The checked GPS source explicitly leaves ordered-interface uniqueness unproved. Do not claim an unconditional near-critical exploration-ensemble counterexample from those references alone.
- DMP does not make the one-dimensional driver Markov in conformally mapped slit domains. The proved deletion formula includes a geometry-dependent drift term.
- Tightness and mesh covariance make the **cluster set** dilation invariant; individual subsequential limits need not be. A uniqueness argument cannot assume their scale invariance without justification.

## Next investigations

1. Derive local target consistency and controlled boundary stability from common-coloring couplings and uniform crossing bounds, while treating random slit-domain kernels separately.
2. Seek a common deterministic conformal metric across domains. The global-deformation theorem gives a useful solved subcase, not a representation theorem for arbitrary ensembles.
3. Find observables implying chart-local-martingale driving after one affine normalization; this would activate the conditional theorem.
4. Investigate whether source/frontier germs can encode geometry. No such full counterexample is currently established.

## Files and checks

`progress.tex` contains detailed proofs, conditional results, source caveats, and unsuccessful approaches. `final.tex` will contain the polished core counterexample and rigidity results. Scratch investigations and build products live in `work/`.

Core arguments were critically reviewed by independent agents. `progress.tex` compiles with `latexmk -pdf -outdir=work/build progress.tex`; presentation checks and the final handoff are being completed. Compilation is not mathematical verification.
