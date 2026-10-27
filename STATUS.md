# Research status — 27 October 2026

**The corrected three-axiom classification and percolation universality remain open.** Locality means agreement up to exit from any common colored source neighborhood, including different targets. The historical target-germ counterexample does not satisfy this corrected axiom.

## Results established in this session

- **Total-variation loss of source memory (new continuation).** The joint law of the radius-r initial prefix and the terminal suffix after its last visit to the radius-R source ball differs from the product of its marginals by at most C(r/R)^α. This holds at every small r, allows arbitrary bounded Borel suffix observables, and bounds the expected conditional total-variation distance. It uses independent inner resampling and exact common-suffix shielding, without limiting DMP. See thm:spatial-beta and cor:spatial-conditional-tv.

- **An initial-germ zero-one law without an affine ansatz.** For independent-color curve limits admitting the RSW source-shield coupling, every event determined by arbitrarily short ordered initial prefixes has probability zero or one. Resample the inner colors independently while keeping the outer colors shared: the first prefix is independent of the entire second curve, while shielding makes the full curves arbitrarily close. The proof also gives prefix/full-curve bounded-Lipschitz covariance of order r^(α/(1+α)). It needs marginal curve convergence, not limiting DMP or measurable continuum configurations. See thm:ed-germzeroone.
- **A common metric within the affine-mixture ansatz.** If a coherent family of independent-color exploration limits has marginals that are Borel mixtures of affine SLE₆ laws, those mixtures collapse to one deterministic tensor, common to all domains with analytic regular marks. Initial-germ triviality gives purity at a flat reference source; local source splicing and exact terminal coalescence identify all other metrics. This requires compatible common-mesh limits for the splice comparisons. It does not derive the affine-mixture ansatz. See thm:ed-coherent.
- **Endpoint decoding and exact coalescence.** One sample's ordered trace germ at an analytic regular endpoint recovers its affine tensor. Reversibility of the candidate SLE laws gives the terminal decoder, including rough opposite ends using only local finite prefixes. A closed common-suffix relation survives joint curve limits. Source-patch coupling gives total-variation control of metric mixing measures, and any positive coalescence probability identifies pure tensors. See thm:ed-analytic, lem:cb-closed, prop:cb-priors.
- **Weaker conditional driving rigidity.** The canonical drift may be arbitrary continuous finite variation, with only a uniform first-order initial tangent in probability. No density, right continuity, or total-variation-rate bound is assumed. Locality gives the bracket tangent and slit covariance; the mirrored-slit bound and compatible strong DMP force drift zero and bracket six. A further version allows random initial tangents and replaces the deterministic bound by uniform tightness of their laws along the mirrored slits. The wrong-affine obstruction also extends to deterministic finite-variation tangents. None of these analytic inputs has been derived for general percolation limits. See sec:fv-tangent-rigidity.
- **Curved common source geometry.** The shield coupling extends to compatible uniformly bi-Lipschitz common source annuli. The two domains must still agree outside the source patch. A known half-plane three-arm estimate yields a whole-segment union bound, but the deterministic implication needed for whole-tube curve stability remains unproved. See sec:ss-curved.

## Earlier results still useful

Two shrinking mirrored slits give inverse-linear drift and inverse-cubic variance anomalies; local boundedness of a finite bulk-jet closure yields SLE₆. A nonsimilarity affine image cannot have tame driving characteristics in all bounded Euclidean charts. Inside the abstract deterministic affine ansatz, stability at one straight slit-tip germ suffices for a common tensor. Uniform curve nonconcentration bounds anisotropy. Detailed proofs and historical failed approaches remain in progress.tex.

## Main gaps and next steps

1. Derive an affine-SLE/affine-mixture representation, or sufficient driving characteristics in a fixed affine structure, from coarse geometric input. The new common-metric theorem removes domain-dependent and random metric choices only after this representation is assumed.
2. Determine whether the abstract three axioms permit a conserved tensor encoded in rough source frontiers. Endpoint decoding concerns ordered trace germs at regular ends, not an unlabelled frontier at every stopping time.
3. Extend source coupling to perturbations along whole slits with explicit source access. A tip shield alone leaves altered boundary behind it; inverse-chart convergence can create forced fjords.
4. Establish conditional exploration kernels on random slit domains. Configuration convergence and separate deterministic-domain convergence do not suffice. No unconditional near-critical counterexample is claimed.

Brownian full support cannot replace continuity at deterministic null histories. The new percolation coupling results use an actual shared independent coloring and are not claims about all abstract three-axiom families.

## Files, preservation, and verification

progress.tex contains the full arguments (72 compiled pages); final.tex presents the checked driving, endpoint-decoding, and independent-color coupling results (28 pages). The new source addendum has been compiled locally; the reports under results/ still precede this continuation checkpoint. Historical fixed-target results remain under archive/. AGENTS.md and PROJECT_DESCRIPTION.md are unchanged.

The finite-variation, random-tangent, endpoint-decoder, coalescence, germ zero-one, and common-metric arguments received primary and independent-agent checks. Both reports compile with clean final logs and resolved references; representative mathematical pages were visually checked. Compilation is not mathematical verification. Intermediate checkpoints were pushed to main as 638039b and 3aae85a before the final report update.

