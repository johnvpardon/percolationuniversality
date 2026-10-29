# Research status — 29 October 2026

**Continuum classification under RSW remains open. Current priority: understand affine-SLE₆ driving in arbitrary coordinates before imposing coordinate-sensitive stochastic regularity.** Verification of the axioms for lattice scaling limits remains deferred.

## Scope and standing assumptions

Classify Borel families of ordered unparameterized explorations in colored marked simply connected domains, with genuine strong DMP, corrected source-neighborhood locality (remote targets may differ), physical translation covariance, and explicit uniform crossing estimates. The expected conclusion allows one deterministic affine normalization common to the family. No conformal covariance, dilation invariance, or Markov property of the single real driver is assumed.

Explorations are uniform limits of simple curves, **not embedded curves**. Dense touches and swallowing are allowed; no simple exploration time interval is presumed. Ordered traces, filled hulls, and unlabelled frontiers remain distinct. Continuous Loewner generation/strict hull growth is a separate standing admissibility condition. Samplewise simple approximations do not supply crossing-controlled approximating laws.

The quantitative input is an upper bound q<1 for avoidable boundary quads of modulus at least M, uniform over all admissible restart states. Crossings count contacts with boundary sides, distinguished as prime-end sides. Strong DMP makes this conditional. The lower driving tail also uses the target-attached ray comparison (RL1). At rough states this is an explicit source-prime-end deletion admissibility requirement; Euclidean locality at coincident impressions is insufficient.

## Why the strategy changed

The axioms do not yet select a correct affine structure. Existence of one common structure with tame driving is a major missing step, not an available normalization. For fixed-affine SLE₆, the ordinary driver in wrong coordinates is not Brownian and cannot satisfy the existing tame-characteristic assumptions throughout the domain family. Those obstructions do **not** settle semimartingality or finiteness of its raw signed restart budget.

Study the actual affine-SLE₆ driver and its capacity change, while deriving affine-compatible constraints on the unknown family. Retain the constant physical Beltrami coefficient as an unknown; identify anisotropy and stochastic law together. Do not demand finite raw signed variation in every affine coordinate system.

## New checked results

- **Exact evolving correction, with no clock-density assumption.** For a real-linear half-plane self-map L, F_t = ĝ_{s(t)} ∘ L ∘ g_t⁻¹ and μ_{F_t} = μ_L · overline{(g_t⁻¹)′}/(g_t⁻¹)′. There is an exact interior Stieltjes equation for F and a transport equation for μ. Interior finite variation does not justify an Itô formula at the moving boundary tip. See sec:affine-beltrami-prefix.
- **Affine parameter regularity even for nonsimple filled hulls.** At the same original prefix, affine perturbations have explicit first variations of both driver and capacity. A principal-Beltrami/Beurling argument gives boundary-uniform differentiability and uniform Taylor remainders O(ε²|ν|²R) and O(ε²|ν|²R²) on a bounded-hull horizon. Driver response is O(|ν|R), clock response O(|ν|R²). The linear clock response is deterministically 1/2-Hölder in original capacity. These are NOT fixed-transformed-capacity derivatives. Combined with crossing radius tails, they give Brownian-order stochastic bounds on parameter response. See prop:affine-prefix-variation, cor:affine-global-response, prop:affine-prefix-taylor, cor:affine-clock-holder.
- **Known-model mean response reduces to a concrete reverse-flow problem.** For SLEκ, E D_t = cκ Im(ν)√t. The finite coefficient has an absolutely convergent integral/Feynman–Kac representation using a two-dimensional reverse Loewner diffusion. The interior adjoint cancellation at κ=6 leaves uncontrolled boundary flux; c₆ has NOT been computed or shown nonzero. See sec:reverse-affine-response.
- **Nondegenerate adaptive quadratic activity from the continuum assumptions.** Radius-r exit times have conditional means comparable to r² and exponential slow-exit tails. Counts on any fixed interval concentrate at order length/r², with exponential errors. Along dyadic radii, every subsequential weak limit of the realized squared-exit-increment measures has density bounded above and below relative to capacity. No uniqueness, deterministic-partition quadratic variation, or semimartingality follows. See sec:adaptive-exit-clocks.
- **A concrete test for wrong-coordinate semimartingality.** In the known affine-SLE₆ model, semimartingality plus the already proved elliptic bracket forces the affine capacity clock to be absolutely continuous in the original SLE capacity. Brownian martingale representation proves this after geometric stopping-time changes. Actual clock AC/singularity remains unknown; inverse-clock AC is not asserted. Deterministically, global capacities satisfy hcap(LK) comparable to hcap(K), but this gives no increment bound after a rough restart. See prop:affine-clock-ac-necessary and prop:global-affine-capacity.
- **Scaling is insufficient.** A selfsimilar uniformly elliptic martingale with trivial initial germ can have no initial bracket tangent. This rules out strengthening the scaling obstruction without its characteristic premises. It is a process example, not a curve-family counterexample. See prop:selfsimilar-elliptic-no-tangent.

These arguments received primary and independent critical checks. Exact stopping clocks, rough-state locality admissibility, and matched-prefix indexing are essential.

## Next investigations

1. Determine actual AC/singularity and finer behavior of the affine-SLE₆ capacity clock. A singular component would exclude wrong-driver semimartingality. AC alone would not prove it.
2. Use the explicit affine response and reverse-flow representation to study its temporal regularity, correlations, and the coefficient c₆. Control the near-real-boundary flux before integrating the adjoint identity. Separate fixed-prefix parameter response from changing the Brownian time argument.
3. Seek signed constraints from the abstract axioms that accommodate every fixed-affine SLE₆. A concrete observable is predictable exit-sign bias after candidate affine correction. Exit counts control its number of terms but leave the crude total signed budget at order T/r. Translation covariance has not yet supplied the missing cancellation or existence of a preferred tensor.
4. Carry the transported Beltrami field through locality comparisons on rough slit states. Affine deformation of a restarted chart hull differs from fixed physical affine deformation of the already explored domain. Do not replace the latter field by a constant chart coefficient.

## Earlier tools retained and limitations

Crossing estimates give conditional exponential upper driving tails; corrected ray locality gives lower oscillation tails and variation index exactly two. If the finite signed restart budget (QV4) is obtained in some common structure, the bracket is automatically absolutely continuous and uniformly elliptic. Singular drift and variance-six identification still remain.

Conditional rigidity gives SLE₆ from controlled drift tangents or conditional-bias bounds with the required shrinking-slit rate. Analytic locality transports characteristic measures and finite budgets but gives no such rate by itself. Full remote-deletion locality excludes nontrivial canonical one-sided SLEκ(ρ), including target-invariant branches. None of these facts establishes a correct affine structure for the unknown family.

Affine identifiability and simple-SLE decoder results remain supporting tools; no unknown frontier law is identified. Independent-color shielding, mixing and discrete correctors are saved for later universality work, not deductions from the abstract crossing input. No counterexample to the corrected classification conjecture has been established.

## Preservation and verification

All substantive arguments are in progress.tex and final.tex; no scratch fragments are needed to resume. The sources and reports in results/ are refreshed after compilation. AGENTS.md and PROJECT_DESCRIPTION.md are unchanged. The direction change was pushed in 68bfe55 and the first checked clock results in 181990f; subsequent source/report checkpoints preserve the remaining work.
