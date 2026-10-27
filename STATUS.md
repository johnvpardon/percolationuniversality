# Research status — corrected locality, 27 October 2026

**The corrected classification and universality remain open.** The user's commits `32f8e45` and `0e47018` replace fixed-target deletion locality by agreement up to exit from any common colored source neighborhood, even for different targets. No counterexample satisfying the corrected three axioms in one fixed color convention has been constructed.

## New proved results and their assumptions

- **Checkpoint: weaker driving rigidity (27 October).** The classification now permits an arbitrary continuous finite-variation canonical drift, with only a deterministic uniform first-order tangent in probability at every initial state. No drift density, right continuity, or total-variation-rate bound is assumed. An analytic-field comparison yields the same initial bracket/slit covariance; strong DMP and an inverse-variation stopping-time lemma eliminate drift and force bracket six. The mirrored-slit initial-drift bound and conditional-characteristic restart compatibility remain explicit hypotheses. This also weakens the wrong-affine obstruction. See `sec:fv-tangent-rigidity` in `progress.tex`. Independent checking completed; these hypotheses have not been derived for percolation limits.
- **Driving rigidity without a quadratic-variation assumption.** Assume continuous semimartingale drivers with absolutely continuous, finite right-continuous drift, deterministic initial drift, strong DMP, and admissible source-preserving slit comparisons. Locality first regularizes the bracket near the start. Bounded initial drifts along two explicit shrinking mirrored slits force zero drift and variance six; strong DMP then gives SLE₆. Local boundedness in inverse-chart topology suffices. These analytic assumptions have **not** been derived from RSW.
- **Quantitative obstruction:** non-six variance produces inverse-cubic drift blow-up under the slit test; nonzero drift produces inverse-linear blow-up. A locally bounded closure using finitely many interior conformal-map jets is completely classified.
- **Wrong-coordinate obstruction:** a nonsimilarity affine image of SLE₆ cannot have tame drift in every bounded-domain Euclidean chart, even without bounded initial drift as a function of domains. Proof: bracket regularization, transfer to the known scale-invariant half-plane law, a martingale CLT, swallowing races, and affine identifiability. This does not construct the correct metric for an unknown family.
- **Affine marginal ansatz:** strong locality permits source-germ metrics before DMP is imposed. DMP requires metric conservation. Stability only at one canonical straight slit-tip germ then forces a common metric; full domain continuity and reversal are unnecessary. Ordinary a.s. DMP alone does not supply this stability. A pointwise analytic-history alternative is stated as an extra premise.
- **Coarse bounds:** uniform small-ball nonconcentration makes half-plane affine metrics compact. Strong locality plus a specified conditional unforced-annulus bound gives Hölder stability for target-patch changes with a local access condition. These are curve estimates, not an assertion that arbitrary path families come from one coloring.

- **A direct RSW source coupling:** for independent triangular site percolation (or the stated compatible cellular model), a one-edge monochromatic shield forces two shared-color explorations to merge permanently. Flat and straight-slit source patches obey `P(d_F > 2R) ≤ C((ε+δ)/R)^α`. This transfers to marginal curve limits without a limiting DMP theorem. It does not establish arbitrary inverse-chart stability.

## Obstructions and useful failed approaches

- Moving the old selector from target to source gives strong locality but does not establish DMP. A source-flat/default-identity version provably fails DMP at the first hit of a fresh horizontal level.
- The initial ordered-trace-germ decoder does not decode a later unlabelled accessible frontier at every stopping time. Source-germ metric memory is an unresolved possibility, not a constructed example.
- Brownian full support cannot extend an a.s. identity to deterministic null histories without stability. Forced source-access fjords also obstruct inferring physical curve continuity from inverse-chart convergence and unforced-crossing bounds alone.
- Near-critical configuration convergence still does not supply ordered exploration kernels in random slit domains. No unconditional near-critical counterexample is claimed.

## Next priorities

1. Derive regular driving characteristics in a suitable fixed affine structure, or find a structure theorem avoiding semimartingales.
2. Extend the proved source-shield coupling to controlled tubular approximations of simple slits, to approach straight-tip stability with explicit access control.
3. Establish limiting strong conditional kernels on random slit domains.
4. Investigate frontier-germ metric recovery or prove its impossibility.

## Files and verification

`progress.tex` retains the full history and corrected-locality continuation (62 compiled pages at this checkpoint). Its new finite-variation extension has been independently checked. `final.tex` still presents the preceding driving rigidity and wrong-coordinate results (13 pages); promotion of the extension is pending the next checkpoint. `archive/original-locality-results.tex` preserves the old counterexample with a historical-scope notice. Compiled reports are under `results/` and `archive/`; scratch/build files remain in ignored `work/`.

New arguments received independent agent and primary-agent checks. Symbolic checks cover mirrored-slit derivatives, drift identities, analytic-germ covariance, and general-κ boundary races. All three edited LaTeX documents compile with clean final logs, and all symbolic checks pass. The user's project specification and `AGENTS.md` are preserved unchanged.

