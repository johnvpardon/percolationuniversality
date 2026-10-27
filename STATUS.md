# Research status — 27 October 2026

**The corrected three-axiom classification and critical percolation universality remain open.** Locality compares any common colored source neighborhood, including different targets. The historical target-germ counterexample does not satisfy this corrected axiom.

## New continuation results

- **A conditional first-moment route to SLE₆.** Bounds |E[X_t−X_s | F_s]| ≤ K(t−s) for bounded stopped drivers imply a canonical absolutely continuous drift with |b|≤K by Doob–Meyer. Applying locality to two mirrored shrinking slits forces essential initial limits b→0 and bracket density v→6, without assuming initial tangents or right-continuous densities. The slit constants may grow as o(ε⁻¹). With the explicitly stated strong-DMP, natural-filtration, and canonical-restart compatibility premises, this gives Brownian driving. This is an observable sufficient criterion, not a derivation of cancellation from RSW. See sec:conditional-bias and thm:cbias-rigidity.
- **A lattice-level transfer criterion.** Signed conditional grid-increment bounds pass under bounded continuous-driver convergence to the usual natural limit filtration. A random exploration-clock version uses conditional expected capacity increments and optional sampling. Filtration convergence is unnecessary; strong limiting DMP remains a separate requirement. See prop:discrete-bias-transfer and (DB4).
- **Total-variation loss of source memory.** The joint law of the radius-r initial prefix and the terminal suffix after its last visit to the radius-R source ball differs from the product of its marginals by at most C(r/R)^α. This holds at every small r and allows arbitrary Borel suffix observations. It bounds expected conditional total variation. The proof uses independent inner resampling and exact common-suffix shielding, without limiting DMP. See thm:spatial-beta and cor:spatial-conditional-tv.
- **Annular statistics satisfy a centered strong law.** Last inner-to-outer crossings before first outer hits in dyadic source annuli have exponentially decaying absolute regularity, uniformly between an entire coarse vector and the infinite fine vector. Bounded empirical statistics minus their deterministic expected averages tend to zero almost surely. No dilation invariance, affine ansatz, or absence of later returns is assumed. Convergence and identification of the expected averages remain open. See thm:scenery-beta and cor:scenery-slln.
- **Whole-plane affine identifiability.** Every nonconstant isotropic scale-invariant continuous curve law has only similarities in its orientation-preserving linear stabilizer. An anisotropic symmetry would squeeze its initial trace onto a line. Under additional dilation ergodicity and Borel coding this gives a fixed-affine ordered-germ tensor decoder. It does not give a decoder on unlabelled frontiers under random coordinate maps. See lem:wp-stabilizer and prop:wp-fixed-decoder.

## Earlier results still needed

Independent-color RSW source shields yield an initial ordered-germ zero-one law and source-patch coalescence, also for controlled curved source annuli. An analytic regular endpoint germ decodes its affine tensor; exact common suffixes survive joint curve limits. These results collapse coherent affine-SLE₆ mixtures to one deterministic common tensor across regular marked domains. The mixture ansatz itself has not been derived.

Earlier conditional driving rigidity permits continuous finite-variation drift with a uniform tangent in probability, or tight random initial tangents. A wrong affine structure cannot have tame driving characteristics in all bounded domains. Inside the abstract deterministic affine ansatz, one stable straight slit-tip germ forces a common tensor. These remain conditional statements, not consequences of the bare three axioms.

## Bottlenecks and concrete next steps

1. Try to prove signed conditional cancellation (DB4) for discrete capacity increments after bounded stopping, in a fixed unknown affine normalization, with the shrinking-slit growth bound (BI5). RSW tightness and Brownian-order absolute increments do not supply this estimate. Derive compatible strong exploration kernels on random slit domains separately.
2. Alternatively derive affine-SLE/affine-mixture marginals from coarse geometry. The existing common-metric theorem only removes randomness and domain dependence after that representation is known. The new annular strong law isolates deterministic expected scale frequencies but neither proves they converge nor identifies their values.
3. Extend coupling from a source patch to a whole perturbed slit. A tip shield leaves altered boundary behind it; the boundary-three-arm union bound still lacks the deterministic implication from ordered curve disagreement to a suitable arm event. Inverse-chart convergence can create forced fjords.
4. For the abstract axioms, investigate whether rough source frontiers can encode a conserved tensor. Zhan's deterministic-capacity tip theorem is relevant, but random local maps, intrinsic point selection, and all-stopping-time compatibility are unresolved. Dense correct capacity tips cannot simply define an unlabelled-frontier decoder; affine capacity changes need not preserve null sets.

No unconditional near-critical counterexample is claimed. Configuration convergence, separate deterministic-domain curve convergence, and Brownian full support do not fill the random-kernel or null-history gaps.

## Preservation and verification

progress.tex records all new proofs and unsuccessful routes; final.tex includes the checked first-moment, discrete-transfer, total-variation, and annular-statistics results. Sources compile to 80 and 35 pages with resolved references and clean final logs. The tracked PDFs still precede this source checkpoint; their rendered update is next. AGENTS.md and PROJECT_DESCRIPTION.md are unchanged.

The new bias/slit, discrete-transfer, annular-vector, and affine-stabilizer arguments received primary and independent-agent checks. Compilation checks presentation only. The first continuation checkpoint was pushed to main as 4fa0e86; further meaningful checkpoints follow before the final report update.
