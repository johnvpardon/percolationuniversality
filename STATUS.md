# Research status — 28 October 2026

**The classification conjecture remains open. Current priority: the abstract continuum problem, assuming RSW, not verification of percolation scaling-limit axioms.**

## Current scope and plan (user clarification, 28 October)

Classify Borel families of oriented, unparameterized exploration curves in colored marked simply connected domains, assuming strong domain Markov property, corrected source-neighborhood locality (including different remote targets), physical translation covariance, and explicitly stated uniform RSW-type estimates. The expected conclusion is chordal SLE₆ after one deterministic affine normalization, common to the whole family. Do not assume conformal covariance, scale invariance, or that the single real driving coordinate is Markov.

The curves are limits of simple curves, **not themselves simple**. Dense self-touching and boundary swallowing are allowed; no nontrivial embedded exploration time interval is presumed. Keep ordered trace prefixes distinct from filled hulls and unlabelled accessible frontiers. The simple-SLE decoder theorem concerns known simple model arcs with 0<κ<4, not segments of the exploration. Identifying special frontier arcs would require a separate theorem and is not the principal current route.

1. Specify the curve class, target component, tip prime end, inherited boundary colors, and measurable restart state. Assume the genuine strong conditional-law identity on these random states; constructing it from lattice limits is deferred. Clarify whether source locality uses Euclidean or full prime-end neighborhoods at rough tips.
2. Separate continuous Loewner admissibility from stochastic regularity of the driver. Uniform approximation by suitable simple interior paths plus strict hull growth addresses the former; it supplies no semimartingale decomposition, bracket, or drift tangent.
3. State the RSW input at the curve level, uniformly in scale and after stopping: conditional bounds on unforced annulus/quad crossings, including the admissible rough restart states. Bare rectangle crossing language is insufficient for an abstract path ensemble. Distinguish this chosen assumption from any stronger estimate used later.
4. Investigate whether these continuum assumptions yield adequate signed conditional cancellation or another rigidity mechanism in **one unknown fixed affine structure**. Existing driving criteria do not derive this. Regularity in every preselected Euclidean chart would wrongly exclude anisotropic affine-SLE examples.
5. Test obstructions and counterexamples within this continuum class. Preserve useful failed approaches with exact reasons for failure. Leave discrete correctors, percolation kernel convergence, and universality transfer until later.

## New continuum regularity results (28 October)

- An explicit Brownian-plus-Takagi–Landsberg process has conditional Brownian-scale exponential sup bounds at stopping times, all Hölder exponents below 1/2, and Brownian dyadic quadratic variation, but is not a semimartingale. This is a driver-level obstruction to an unsigned regularity argument, not a curve-family counterexample.
- The exact signed restart budget (QV4) for bounded stopped drivers equals expected canonical drift variation when finite. Its finiteness is the classical quasimartingale criterion, expressed using mean increments at visited slit states with the correct inherited localization interval. This is a weaker first target than bounded drift density; no initial tangent or bracket follows yet.
- Vanishing drift pulses preserve uniform unsigned bounds and converge uniformly to Brownian motion while their initial bias diverges. Inverse-cubic slit biases fit pulses of duration order ε⁶ and height order ε³. Thus unsigned estimates and weak law continuity do not supply the slit-growth cancellation rate.

These arguments received an independent critical check. Detailed statements and proofs are in sec:continuum-regularity-gap in both sources. Source builds are being refreshed; report verification below refers to the earlier PDFs until that refresh is complete.

## Strongest established tools and their limits

- **Conditional driving rigidity:** locality and shrinking mirrored slits force drift zero and bracket six under controlled initial finite-variation characteristics, tight random tangent variants, or suitable signed conditional-bias bounds. Genuine strong DMP transports canonical drift/bracket automatically. The shrinking-slit rate control and existence of the needed characteristics are additional hypotheses, not consequences of RSW. See sec:fv-tangent-rigidity, sec:conditional-bias, and prop:automatic-characteristics.
- **Affine identifiability and decoders:** an analytic regular endpoint's ordered trace germ identifies its affine tensor. A robust whole-plane decoder permits sample-dependent local C1 maps under its explicit coding/model hypotheses. An intrinsic tube-cluster measure and natural-length Palm laws give a Borel decoder from every unlabelled compact interior subarc of known affine simple SLE, simultaneously over affine maps and subarc choices (0<κ<4). These do not identify the law of an unknown nonsimple exploration or its frontier. See thm:ed-analytic and thm:unlabelled-simple-arc.
- **Within an affine ansatz:** suitable coherence/stability premises eliminate varying metrics. For independent-color limits, source shields, endpoint decoding, and exact coalescence collapse coherent affine-SLE₆ mixtures to one deterministic common metric. The affine-mixture representation is unproved.
- **Independent-color results, reserved for later transfer:** RSW source shields imply initial ordered-germ zero-one, total-variation prefix/distant-suffix decoupling, exponential annular mixing, and a centered strong law. A martingale correction yields a functional Gaussian limit under an additional deterministic variance-rate limit. These use shared colors/resampling and are not deductions from abstract curve RSW alone.
- **Obstructions:** wrong affine coordinates cannot have tame driving characteristics in every bounded domain. Finite-energy Brownian drift preserves Wiener initial-germ probabilities, excluding such a representation for the nonzero near-critical limits covered by Aumann's comparison; this does not prove nonsemimartingality. Pointwise deterministic-state kernel convergence is insufficient for random-state continuation. Brownian full support does not repair null-history gaps.

The historical target-germ counterexample violates corrected source locality. No counterexample satisfying all current assumptions has been established. RSW must be uniform over all scales; a finite near-critical correlation scale is not a substitute.

## Record and preservation

Detailed proofs and failed approaches are in progress.tex; mature results are in final.tex. Previous reports under results/ have 101 and 56 pages, respectively. New work must be compiled and critically checked before updating that verification claim. AGENTS.md and PROJECT_DESCRIPTION.md are unchanged. Commit and push meaningful checkpoints to main periodically; substantive arguments must be in tracked sources, not only ignored work/ fragments.
