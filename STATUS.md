# Research status — 29 October 2026

**Continuum classification under RSW remains the priority and remains open.** Verification of domain Markov, locality, and translation covariance for percolation scaling limits is deferred.

## Current priority: understand driving in arbitrary affine coordinates

The next task is to determine the actual regularity of the ordinary Euclidean Loewner driver of a fixed-affine SLE₆, and use that model to choose attainable regularity targets for the unknown family. Do not presuppose a correct complex structure: proving existence of one common affine normalization with tame driving is a major missing step, not preliminary bookkeeping. Finiteness of the uncorrected signed restart budget is not presently known even for the wrong-coordinate affine-SLE₆ model.

Work in two linked directions: (1) study the known affine-SLE₆ driver, its capacity change, and its evolving quasiconformal correction, including small anisotropy; (2) seek regularity/cancellation consequences of DMP, corrected locality, translation covariance and the stated crossing input that accommodate this full model family. For a half-plane-preserving real-linear map L, the exact comparison is F_t = ĝ_{s(t)} ∘ L ∘ g_t⁻¹, with F_t(W_t) the corrected driver and μ_{F_t} = μ_L · overline{(g_t⁻¹)′}/(g_t⁻¹)′. This carries one unknown constant physical Beltrami coefficient into a history-dependent field. Its tip behavior and clock regularity must be justified; this identity alone is not a stochastic classification.

First establish what holds in wrong coordinates: semimartingality remains undecided by our existing obstruction, as do the precise drift/bracket or alternative stochastic descriptions. Preserve the conditional rigidity tools below, but do not use their coordinate-sensitive hypotheses as consequences of the axioms. The aim is to identify anisotropy and the stochastic law together, rather than require a separate prior decoder for the unknown exploration.

## Scope and precise assumptions

Classify Borel families of ordered unparameterized explorations in colored marked simply connected domains, with genuine strong DMP, corrected source-neighborhood locality (remote targets may differ), physical translation covariance, and explicit uniform curve crossing estimates. The expected conclusion allows one deterministic affine normalization common to the entire family. No conformal covariance, dilation invariance, or Markov property of the single real driver is assumed.

The explorations are uniform limits of simple curves, **not embedded curves**. Dense touches and swallowing are allowed; no nontrivial simple exploration time interval is presumed. Ordered traces, filled hulls, and unlabelled frontiers must remain distinct. Continuous Loewner admissibility/strict hull growth is a separate standing condition; arbitrary samplewise simple approximations are not probabilistic crossing-controlled approximants.

The current quantitative input is a uniform upper bound q<1 for avoidable boundary quads of modulus at least M, on every admissible restart state. Quad crossings allow contacts with boundary sides, which are distinguished as prime-end sides. Genuine DMP makes this conditional after stopping. On rough states, state explicitly which deletions preserve a full source prime-end neighborhood: Euclidean locality at coincident physical impressions is insufficient. The new lower-tail theorem uses the target-attached ray comparison (RL1); its inverse chart f∘F_r is explicit and Borel. This is automatic at regular separated source/target points and an explicit admissibility requirement at rough states.

## Strongest results of the latest investigation

- **Locality gives a diffusive lower driving tail.** Delete the upward ray from i√h in an inherited half-plane chart. Driver confinement forces entry into a small ball before the first ray hit; in the comparison domain that entry is a boundary-quad crossing. Corrected locality, allowing a changed remote target end, gives P{sup|ΔW|>δ√h | past}≥1−q. This uses no semimartingality and does not infer a general interior hitting estimate. See lem:ray-locality-driver-lower.
- **Driving variation index is exactly two before semimartingality.** A martingale-difference/Borel–Cantelli argument gives infinite r-variation for every r<2 on every nontrivial interval. The existing Hölder estimates give finite r-variation for r>2. This is not a claim about quadratic variation or the value at r=2. See prop:driver-variation-index.
- **Finite signed budget would give uniformly elliptic bracket automatically.** Conditional Brownian-order second moments force d⟨M⟩≤Kdt for any semimartingale decomposition, with no drift-density/tangent assumption. The new lower tail then gives cdt≤d⟨M⟩≤Kdt. The variance is not yet identified as six. Singular drift can remain, as the reflected-Brownian process example illustrates. See prop:moment-bracket-domination and prop:bracket-lower-tail.
- **Exact analytic-locality identities transport signed budgets.** Local semimartingality and finite expected drift variation transfer both ways through analytic deletion with matched stopping clocks. Two deletion directions invert the signed characteristic measures; absolute continuity of both deleted drifts forces that of original drift and bracket. Under the RSW bracket bound, singular drift transforms simply as h′dA⊥ and cannot be canceled by the Itô anomaly. These statements do not select the unknown affine structure. See sec:analytic-locality-budget.
- **The force-point alternative is excluded within its explicit ansatz.** Remote-deletion locality among canonical one-sided SLEκ(ρ), ρ>−2, forces κ=6,ρ=0. A nonzero Schwarzian remainder rules out target-invariant SLEκ(κ−6) branches; no finite initial tangent is needed. Their extra-mark Markov property also differs from the required two-end DMP. See prop:forcepoint-locality-exclusion.

These arguments received primary and independent critical checks. The rough-state deletion requirements and matched-clock localizations are essential qualifiers.

## Remaining bottlenecks and next questions

1. Establish the regularity class of fixed-affine SLE₆ in arbitrary Euclidean coordinates, then formulate an affine-compatible signed target (possibly using the evolving Beltrami field). Proving finite aggregate signed restart variation (QV4) in some common affine structure remains an eventual route, but neither its existence nor its validity in wrong coordinates is established. Two-sided driving tails and variation index do not imply it; Brownian plus deterministic infinite-variation Hölder drift demonstrates the process-level obstruction.
2. Once semimartingality is obtained, eliminate the singular drift and control AC bias across shrinking slit states. The bracket is then already bounded and positive. Locality transports drift measures, but source-dependent stopping intervals and constants can degenerate; finite budgets alone do not give the required first-order rate.
3. Investigate whether the non-Möbius/Schwarzian part of full locality supplies cancellation beyond target invariance. Do not assume finite-dimensional force-point closure. A variation modulus uniform over all rescalings of a chart can silently assume martingality and is not a legitimate coarse input.
4. Keep locality conventions on rough source prime ends explicit. The decoder remains supporting work: simple-SLE model arcs are not segments of the unknown nonsimple exploration. Frontier-law identification is not the main route.

## Earlier tools retained

The conditional driving rigidity theorems force SLE₆ from controlled finite-variation tangents, tight random tangents, or signed conditional-bias bounds with the shrinking-slit rate. Genuine strong DMP automatically transports canonical characteristics. A wrong affine structure cannot be tame in all bounded domains.

Regular endpoint germs identify affine tensors. The intrinsic-measure/Palm construction gives a simultaneous Borel decoder from unlabelled compact subarcs of known affine simple SLE (0<κ<4), without identifying unknown frontier laws. Coherent independent-color affine-SLE₆ mixtures collapse to a common deterministic tensor only after the unproved mixture ansatz is supplied.

Independent-color shielding, prefix/suffix decoupling, annular mixing/strong laws/conditional CLT, discrete correctors and kernel transfer are saved for later universality work. They are not deductions from abstract curve crossing bounds. No counterexample to the corrected conjecture has been established; the historical target-germ example fails its locality.

## Preservation and verification

All substantive new arguments are in progress.tex and final.tex; ignored work/ fragments are unnecessary to resume. Source builds and refreshed PDFs are being checked. The previous verified reports had 108 and 63 pages. AGENTS.md and PROJECT_DESCRIPTION.md are unchanged. Checkpoint 6491395 preceded this continuation; meaningful source and report checkpoints continue to be pushed to main.
