# Research status — 29 October 2026

**New obstruction:** a checked boundary-recorded one-switch construction obeys the Borel exploration axioms and a uniform unforced-quad crossing bound on an explicit restart-closed class of bounded locally connected domains, but uses different affine SLE6 metrics in unit disks and disks of radius two. The common-affine classification implication therefore fails on this class. Critical percolation universality is not proved. Extension to arbitrary non-continuously charted prime-end domains is not claimed.

## Scope

States have continuous inverse maps on the closed prime-end disk. They may have dense touches and different prime ends with the same physical impression. The class is Borel, explicitly normalized, and preserved by affine changes and the restart kernels. Curves have continuous Loewner generation and strict hull growth. Their embedded approximants have endpoints converging to the marked prime ends; fixed physical approximation endpoints are not required. Corrected locality retains full colored prime-end sides and permits different remote targets. Crossings count contacts with distinguished prime-end sides.

## Construction and proof

The complete proof is in continuation/boundary_switching.tex, included by final.tex and progress.tex. See sec:one-switch-construction and thm:one-switch-lc-counterexample.

1. Fix ordinary SLE6 (Q0=I) and one different affine-SLE6 metric Q1.
2. Mark old boundary intervals whose compact physical arcs have a hereditary Q1 certificate or lie on a unit circle. Heredity makes rational intervals sufficient, giving a Borel open set O of prime ends.
3. Run metric zero to first hitting of O, then metric one forever. The infimum is Borel even when unattained.
4. Fresh type-zero frontier cannot create marked arcs. Fresh type-one frontier supplies a whole marked one-sided interval next to the tip, which type-zero SLE6 hits immediately. The ordinary remaining domain therefore records the continuation law.
5. Prove strong DMP in the expanded piecing filtration and descend to the usual natural trace filtration. An unattained switch need not remain observable as the same hitting functional after replacing its future. Completions use the same product probability space.
6. Locality and translations survive. Splitting a long unforced quad into two halves gives the bound 2q<1 from baseline bounds q<1/2.

In unit disks the rule switches immediately; in radius-two disks O is empty. Tensor identifiability rules out any common affine normalizer.

## Main checked ingredients

- Hereditary Borel certificates (sec:hereditary-cluster-certificate): every tubular-measure cluster is uniformly comparable with the canonical atomless full-support intrinsic measure; both local branch decoders give the tensor almost everywhere. Matched-radius limits restrict exactly to each subarc, proving heredity. Known affine simple-SLE pieces are accepted; other tensors and smooth arcs rejected. Isotropic certificates are stable under local conformal maps followed by a fixed affine map.
- Stopping-time frontier bridge (sec:frontier-certificate-bridge): Zhan's fixed-real swallowing-time duality, localized force-point SLE8/3 Girsanov, and certificate stability handle special times. Positive-probability continuation preserving a chosen compact boundary piece transfers the certificate to each arbitrary chosen stopping time. No uncountable all-time event or dimension-only local-law inference is used.
- Known-model continuity (prop:affine-sle-closed-chart-continuity): uniform convergence of inverse charts on the closed prime-end disk gives uniform whole-curve couplings for every fixed affine-SLE6 family. The new family violates this property along disk radii tending to one. Such continuity is a concrete compatible extra hypothesis; its sufficiency for classification is open.
- Affine energy coercivity (sec:affine-tensor-coercivity): two opposite slit comparisons control both driving characteristics. On two bounded calibration states, four full auxiliary energies obey kappa(A)^(p-1) <= C(1+B_p(A)). Their uniform signed feasibility remains unproved; these are candidate-dependent full energies, not four scalar tests.

## Positive regularity tools retained

Exact adaptive exit-sign budgets characterize finite-variation drift, and normalized subquadratic energies characterize absolutely continuous Lp drift (sec:exit-signed-bridge). In a specified common structure, local Lp energy, source-linear initial rates K(f)^p, and epsilon max K(f_epsilon^+/-) -> 0 imply zero drift and bracket 6t (sec:exit-energy-rigidity).

Convex dual signed-test energy is lower semicontinuous in the affine tensor; simultaneous finite-test feasibility with fixed envelopes selects a common tensor on a compact class (sec:finite-affine-energy-selection). Calibration energies can supply compactness.

RSW and corrected ray locality give upper/lower driving tails, variation index two, and nondegenerate adaptive quadratic-activity clusters, without semimartingality or a canonical quadratic variation. Finite-mesh locality transports signed increments and variance-six defects before semimartingality.

Matched-prefix affine response is explicit for nonsimple hulls. Clock derivative regularity does not imply clock AC. Actual affine-SLE6 clock AC, wrong-coordinate semimartingality and reverse-flow coefficient c6 remain open. Shared smooth global-coordinate priors collapse under strong DMP and translations (sec:random-smooth-medium-rigidity); the new family has a geometric metric change rather than that representation.

## Next investigations

1. Test domain continuity under uniform closed-chart convergence, including smooth approximations of rough restart states, as a way to exclude boundary memory. Do not silently change PROJECT_DESCRIPTION.md.
2. Determine whether this eliminates general phase-selection rules, then return to the signed exit-energy bridge and simultaneous finite-test feasibility.
3. Investigate extension of the construction beyond continuously charted domains, keeping physical continuity, prime-end observability and Borel kernels explicit.
4. Retain affine clock entropy/UI and reverse-flow calculations as calibration tools, without treating unsigned estimates as signed cancellation.

## Verification and preservation

The hereditary certificate, frontier bridge, full switching construction, state coding, filtration argument and continuity proposition received independent critical checks. A full integrated form of the main construction compiled cleanly before the execution environment disconnected again. The final source assembly was preserved through the repository connection and passed brace, environment and reference checks; a fresh LaTeX build remains pending because the execution environment is unavailable.

The results PDFs still correspond to checkpoint b492628 and do not yet include the new frontier and switching sections. Refresh them when execution resumes. Earlier checkpoints 4ee7649 and b492628 preserve smooth-medium rigidity, visited-state energy blow-up, affine energy coercivity and hereditary certificates. AGENTS.md and PROJECT_DESCRIPTION.md are unchanged.
