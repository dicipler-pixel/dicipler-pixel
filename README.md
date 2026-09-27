## Jeromie Beasley

Independent researcher in mathematical physics. No lab, no institution: a laptop, published data, and about two and a half years of asking what can be measured and what cannot.

> I want a way to map and measure everything as simply as light does.

The work runs through one idea: a projector, the operator that keeps part of a space and discards the rest, carries both the geometry and the bookkeeping of a physical system. Most of my papers follow that idea into a different problem: entanglement, gravity, knots, many-body motion, arithmetic.

Results are graded by what supports them: proved, derived, recognised or measured. The ones that can be machine-checked are checked in Lean.

---

### Machine-checked proofs

| Repository | What it proves | Check |
| :--- | :--- | :-: |
| [**offset-lean**](https://github.com/dicipler-pixel/offset-lean) | The finite algebra behind *The Offset Belongs to the Boundary*: the entanglement offset as log-odds of empty versus full, asymmetry = tanh(offset/2), endpoint bounds, a boundary-column degree mechanism. 143 theorems + 7 headline results. | [![check](https://github.com/dicipler-pixel/offset-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/offset-lean/actions/workflows/build.yml) |
| [**arithmetic-kakeya-finite-bridges**](https://github.com/dicipler-pixel/arithmetic-kakeya-finite-bridges) | For the Epoch FrontierMath arithmetic Kakeya problem: rational forcing equals integer forcing, and every completed configuration keeps two independent labels on every cut. 33 theorems. | [![check](https://github.com/dicipler-pixel/arithmetic-kakeya-finite-bridges/actions/workflows/kakeya-public.yml/badge.svg)](https://github.com/dicipler-pixel/arithmetic-kakeya-finite-bridges/actions/workflows/kakeya-public.yml) |
| [**what-russell-saw-lean**](https://github.com/dicipler-pixel/what-russell-saw-lean) | For *What Russell Saw*: Russell's paired-motion axiom as energy conservation for every oscillator motion (Physlib), why his `v ∝ 1/a` means an inverse-cube pull and spiral orbits, the apsidal angle and the ISCO at `r = 6M` derived from the Schwarzschild potential, Maxwell stress and Ampère's sign, the tide, the vortex and the cone. 43 theorems. | [![check](https://github.com/dicipler-pixel/what-russell-saw-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/what-russell-saw-lean/actions/workflows/build.yml) |
| [**dirac-time-lean**](https://github.com/dicipler-pixel/dirac-time-lean) | For *The Dirac Time of the Gigantefermion*: every exact finite result the paper states: the predictive quotient (Cayley–Hamilton closure and minimality), projector tangent geometry and its block formulas, the common-clock corollaries, the weak-value bound, path-ledger descent, finite return in discrete and continuous time, the entropy/correlation ledger with unitary invariance of entropy proved via Physlib, the moving-frame identity, the equal-endpoint witness, friction on projector rotations and the torus-knot silence criterion. 86 theorems + 3 headline results. | [![check](https://github.com/dicipler-pixel/dirac-time-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/dirac-time-lean/actions/workflows/build.yml) |
| [**connection-energy-lean**](https://github.com/dicipler-pixel/-connection-energy-lean) | For *Non-Normality Is Connection Energy*: `[H, H†] = −2[D, A]`, the energy identity `⅛‖[H, H†]‖² = Σ_edges ‖Dᵢ − AᵢⱼDⱼAᵢⱼ†‖²`, and `H` normal exactly when `D` is parallel along every edge. 14 theorems. | [![check](https://github.com/dicipler-pixel/-connection-energy-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/-connection-energy-lean/actions/workflows/build.yml) |
| [**light-ledger-lean**](https://github.com/dicipler-pixel/light-ledger-lean) | For *Light Keeps the Ledger*: boundary elimination and the matrix Smith transform, the transition-window census, Gram positivity, optical response as a reweighted metric and the peel, rigidity, completion steps, the Edition 7.2 spectral bounds, upward redistribution and oscillator realization, with the exact counterexamples that bound each claim. 122 theorems. | [![check](https://github.com/dicipler-pixel/light-ledger-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/light-ledger-lean/actions/workflows/build.yml) |
| [**gravity-ledger-lean**](https://github.com/dicipler-pixel/gravity-ledger-lean) | For *The Ledger Outlives the Metric*: projector tangents are off-diagonal, the signed metric and reciprocal determinant, the local overlap cap, and the projector-overlap Taylor bridge from differentiability alone. 30 theorems. | [![check](https://github.com/dicipler-pixel/gravity-ledger-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/gravity-ledger-lean/actions/workflows/build.yml) |
| [**square-case-lean**](https://github.com/dicipler-pixel/square-case-lean) | For *The Square Case* and *5D Spectral Anatomy of Four-Body Obstructions*: the Gram invariant, the forced transport coefficient, symmetrisation of the eigenvalue block, the eigenframe spectrum, and interlacing (exactly one eigenvalue in every gap), and the four-body binary-wall theorems. 63 theorems. | [![check](https://github.com/dicipler-pixel/square-case-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/square-case-lean/actions/workflows/build.yml) |
| [**price-of-a-direction-lean**](https://github.com/dicipler-pixel/price-of-a-direction-lean) | For *The Price of a Direction*: directions as channels (`cos²θ` overlap, `sin²θ` separation), exchange symmetry of nonzero spectra, trackability loss at a defective point, the metric–curvature inequality, and the exact ratio-gate onset. 17 theorems. | [![check](https://github.com/dicipler-pixel/price-of-a-direction-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/price-of-a-direction-lean/actions/workflows/build.yml) |
| [**upg-lean**](https://github.com/dicipler-pixel/upg-lean) | For *Universal Projector Geometry*: a retained sector runs on its own exactly when its coupling vanishes, and every finite diagnostic (commutator, redistribution, zero-time memory, cross-block metric) agrees. 40 theorems. | [![check](https://github.com/dicipler-pixel/upg-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/upg-lean/actions/workflows/build.yml) |
| [**elemental-peeling-lean**](https://github.com/dicipler-pixel/elemental-peeling-lean) | For *Elemental Peeling*: what a removal takes away and what later records recover, force recovery from readings, the boundary ledger, and the exclusion certificates. 66 theorems. | [![check](https://github.com/dicipler-pixel/elemental-peeling-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/elemental-peeling-lean/actions/workflows/build.yml) |
| [**yang-mills-lean**](https://github.com/dicipler-pixel/yang-mills-lean) | For *Retained Geometry and Certified Gauge Cutoffs*: gauge-cutoff certificates, the boundary-matrix Schur certificate, and the longest finite chain from projector geometry to an allocation floor. Finite algebra only; no mass-gap claim. 77 theorems. | [![check](https://github.com/dicipler-pixel/yang-mills-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/yang-mills-lean/actions/workflows/build.yml) |

Every check builds the proofs, replays them in Lean's independent kernel checker, and audits that nothing rests on `sorry` or extra axioms.

**Upstream to Mathlib** (submitted):
[#43703](https://github.com/leanprover-community/mathlib4/pull/43703), the rank-two Coxeter group is the dihedral group ·
[#43951](https://github.com/leanprover-community/mathlib4/pull/43951), a trace identity for differences of idempotents.

---

### Papers

All 28 Zenodo records, newest version first. Each DOI always opens the latest version. Every paper has a proof repository; those marked *in progress* are being formalized paper by paper.

| Paper | Latest | DOI | Proofs / code |
| :--- | :-: | :--- | :--- |
| *What Russell Saw: Walter Russell's Universe of Paired Motion, Read Against a Century of Physics* | 2026-09-27 | [10.5281/zenodo.22986656](https://doi.org/10.5281/zenodo.22986656) | [what-russell-saw-lean](https://github.com/dicipler-pixel/what-russell-saw-lean) · 43 Lean theorems |
| *The Dirac Time of the Gigantefermion: Memory First, Projector Geometry, Retained History, and the Cost of an Arrow* | 2026-09-26 | [10.5281/zenodo.22978630](https://doi.org/10.5281/zenodo.22978630) | [dirac-time-lean](https://github.com/dicipler-pixel/dirac-time-lean) · 86 + 3 Lean theorems |
| *The Ledger Outlives the Metric: Wall Species, the Reciprocity Obstruction, and a Measured Crossing Behind an Operator-Side Reading of Entropic Gravity* | 2026-09-25 | [10.5281/zenodo.22023237](https://doi.org/10.5281/zenodo.22023237) | [gravity-ledger-lean](https://github.com/dicipler-pixel/gravity-ledger-lean) · 30 Lean theorems |
| *Five-Dimensional Non-Normal Stability Operator with Gradient-Driven Interface Coupling for Zero-Precursor Filamentary Fractures* | 2026-09-25 | [10.5281/zenodo.21184980](https://doi.org/10.5281/zenodo.21184980) | scripts in the Zenodo deposit; [filament-fracture-lean](https://github.com/dicipler-pixel/filament-fracture-lean) · proofs in progress |
| *Certified Obstructions and Exact Forcing: Thickness Bounds, Nine-Colorings, and Integer Dual Certificates for Two Open Benchmarks* | 2026-09-17 | [10.5281/zenodo.22812167](https://doi.org/10.5281/zenodo.22812167) | [earth-moon-kakeya-certificates](https://github.com/dicipler-pixel/earth-moon-kakeya-certificates) · certificates and checkers; [arithmetic-kakeya-finite-bridges](https://github.com/dicipler-pixel/arithmetic-kakeya-finite-bridges) · 33 Lean theorems |
| *Non-Normality Is Connection Energy* | 2026-09-17 | [10.5281/zenodo.22803572](https://doi.org/10.5281/zenodo.22803572) | [connection-energy-lean](https://github.com/dicipler-pixel/-connection-energy-lean) · 14 Lean theorems |
| *Compound Eye (research tool)* | 2026-09-09 | [10.5281/zenodo.22674828](https://doi.org/10.5281/zenodo.22674828) | software deposit |
| *The Offset Belongs to the Boundary: the Trace Split of the Entanglement Hamiltonian, a Measured Clausius Region, and an Offset with No Bulk* | 2026-09-06 | [10.5281/zenodo.22181748](https://doi.org/10.5281/zenodo.22181748) | [offset-lean](https://github.com/dicipler-pixel/offset-lean) · Lean proofs |
| *What Transport Keeps: Projector Selection, Conserved Pairings, and Spectral Geometry after the Ramanujan Challenge* | 2026-09-06 | [10.5281/zenodo.22543486](https://doi.org/10.5281/zenodo.22543486) | [ramanujan-normality-diagnostic](https://github.com/dicipler-pixel/ramanujan-normality-diagnostic) · diagnostic code |
| *A Subgraph Density Obstruction to Biplanarity, and the Thickness of Inflated Cycles* | 2026-09-04 | [10.5281/zenodo.22307183](https://doi.org/10.5281/zenodo.22307183) | see [earth-moon-kakeya-certificates](https://github.com/dicipler-pixel/earth-moon-kakeya-certificates) |
| *Light Keeps the Ledger: Matter, Direction, and the Wall Between Them* | 2026-08-27 | [10.5281/zenodo.22123115](https://doi.org/10.5281/zenodo.22123115) | [light-ledger-lean](https://github.com/dicipler-pixel/light-ledger-lean) · 122 Lean theorems |
| *The Permutation Coboundary Constant of the Complete Complex Is k/3 for 4 ≤ k ≤ 8* | 2026-08-25 | [10.5281/zenodo.22090958](https://doi.org/10.5281/zenodo.22090958) | [coboundary-k3-lean](https://github.com/dicipler-pixel/coboundary-k3-lean) · proofs in progress |
| *The Three-Body Problem, Operator-First: A Complete Spectral Anatomy of Relational Transport on the Shape Sphere* | 2026-08-24 | [10.5281/zenodo.20764188](https://doi.org/10.5281/zenodo.20764188) | [three-body-lean](https://github.com/dicipler-pixel/three-body-lean) · proofs in progress |
| *Universal Projector Geometry from Electrical Measurements* | 2026-08-21 | [10.5281/zenodo.21305024](https://doi.org/10.5281/zenodo.21305024) | [upg-lean](https://github.com/dicipler-pixel/upg-lean) · 40 Lean theorems |
| *Matter at a Scale: Zero, Span, and the Logarithm Between Them* | 2026-08-20 | [10.5281/zenodo.22019892](https://doi.org/10.5281/zenodo.22019892) | [matter-at-a-scale-lean](https://github.com/dicipler-pixel/matter-at-a-scale-lean) · proofs in progress |
| *Transient Structure at Solar Rigidity Interfaces and the Exceptional Point of the Dynamo Wave* | 2026-08-19 | [10.5281/zenodo.21895551](https://doi.org/10.5281/zenodo.21895551) | [suns-lean](https://github.com/dicipler-pixel/suns-lean) · proofs in progress |
| *The Operator-First Relational Atlas* | 2026-08-18 | [10.5281/zenodo.21972561](https://doi.org/10.5281/zenodo.21972561) | [relational-atlas-lean](https://github.com/dicipler-pixel/relational-atlas-lean) · proofs in progress |
| *Electron Screening in Metal Deuterides: Measurement Systematics, Evolving Target State, and an Experimental Arbitration Protocol* | 2026-08-14 | [10.5281/zenodo.21935285](https://doi.org/10.5281/zenodo.21935285) | [electron-screening-lean](https://github.com/dicipler-pixel/electron-screening-lean) · proofs in progress |
| *The Price of a Direction: Boundary Channel Budgets, Directional Capacity, and Kakeya Structure in Operator Transport* | 2026-08-13 | [10.5281/zenodo.21918463](https://doi.org/10.5281/zenodo.21918463) | [price-of-a-direction-lean](https://github.com/dicipler-pixel/price-of-a-direction-lean) · 17 Lean theorems |
| *Foundational Operator Field Theory on Stratified Manifolds* | 2026-08-09 | [10.5281/zenodo.21254648](https://doi.org/10.5281/zenodo.21254648) | [foft-lean](https://github.com/dicipler-pixel/foft-lean) · proofs in progress |
| *Beyond the Event Horizon: An Operator-First Theory of Persistent Geometry and Black Hole Dynamics* | 2026-08-09 | [10.5281/zenodo.21147366](https://doi.org/10.5281/zenodo.21147366) | [event-horizon-lean](https://github.com/dicipler-pixel/event-horizon-lean) · proofs in progress |
| *Spectral Stress on a Conservative Matrix Field* | 2026-08-08 | [10.5281/zenodo.21825872](https://doi.org/10.5281/zenodo.21825872) | [spectral-stress-lean](https://github.com/dicipler-pixel/spectral-stress-lean) · proofs in progress |
| *The Square Case: Gram Reduction and Spectral Transport for N = d + 1 Bodies* | 2026-08-08 | [10.5281/zenodo.21855590](https://doi.org/10.5281/zenodo.21855590) | [square-case-lean](https://github.com/dicipler-pixel/square-case-lean) · 63 Lean theorems |
| *Intrinsic Quantum Geometric Tensor on the Grassmannian and Spectral Lower Bounds on Dissipation* | 2026-08-05 | [10.5281/zenodo.20768258](https://doi.org/10.5281/zenodo.20768258) | [iqgt-grassmannian-lean](https://github.com/dicipler-pixel/iqgt-grassmannian-lean) · proofs in progress |
| *The Companion-Matrix Projector Diagnostic* | 2026-08-05 | [10.5281/zenodo.21787207](https://doi.org/10.5281/zenodo.21787207) | [ramanujan-normality-diagnostic](https://github.com/dicipler-pixel/ramanujan-normality-diagnostic) · diagnostic code |
| *Intrinsic Emergent Transport Geometry: Emergent Metrics from Spectral Projector Hierarchies* | 2026-07-01 | [10.5281/zenodo.21089303](https://doi.org/10.5281/zenodo.21089303) | [emergent-transport-lean](https://github.com/dicipler-pixel/emergent-transport-lean) · proofs in progress |
| *Spectral Stability Across Obstruction Interfaces in Geometric Transport Systems* | 2026-06-24 | [10.5281/zenodo.20818899](https://doi.org/10.5281/zenodo.20818899) | [spectral-stability-lean](https://github.com/dicipler-pixel/spectral-stability-lean) · proofs in progress |
| *The 5D Spectral Anatomy of Four-Body Obstructions: Kinematic Transport Geometry on Stratified Shape Manifolds* | 2026-06-23 | [10.5281/zenodo.20818168](https://doi.org/10.5281/zenodo.20818168) | [square-case-lean](https://github.com/dicipler-pixel/square-case-lean) · binary-wall proofs |

--- | :--- |
| *Certified Obstructions and Exact Forcing: Earth–Moon Graph Coloring and Arithmetic Kakeya* · [DOI 10.5281/zenodo.22812167](https://doi.org/10.5281/zenodo.22812167) | [earth-moon-kakeya-certificates](https://github.com/dicipler-pixel/earth-moon-kakeya-certificates): manuscript, certificate producers, independent checkers, re-verified on every push |
| *The Offset Belongs to the Boundary* · [DOI 10.5281/zenodo.22181748](https://doi.org/10.5281/zenodo.22181748) | [offset-lean](https://github.com/dicipler-pixel/offset-lean): the Lean proofs of its finite algebra |
| *What Russell Saw: Walter Russell's Universe of Paired Motion, Read Against a Century of Physics* · [DOI 10.5281/zenodo.22986656](https://doi.org/10.5281/zenodo.22986656) | [what-russell-saw-lean](https://github.com/dicipler-pixel/what-russell-saw-lean): 43 Lean proofs, three built on Physlib; paper, mixer, ledger and scripts in the Zenodo deposit |
| *The Dirac Time of the Gigantefermion* · [DOI 10.5281/zenodo.22978630](https://doi.org/10.5281/zenodo.22978630) | [dirac-time-lean](https://github.com/dicipler-pixel/dirac-time-lean): Lean proofs of every exact finite result in the paper |
| *Non-Normality Is Connection Energy* · [DOI 10.5281/zenodo.22803572](https://doi.org/10.5281/zenodo.22803572) | [connection-energy-lean](https://github.com/dicipler-pixel/-connection-energy-lean): Lean proofs of the identity and the normality criterion |
| *Light Keeps the Ledger* · [DOI 10.5281/zenodo.22123115](https://doi.org/10.5281/zenodo.22123115) | [light-ledger-lean](https://github.com/dicipler-pixel/light-ledger-lean): Lean proofs |
| *The Ledger Outlives the Metric* · [DOI 10.5281/zenodo.22023237](https://doi.org/10.5281/zenodo.22023237) | [gravity-ledger-lean](https://github.com/dicipler-pixel/gravity-ledger-lean): Lean proofs |
| *The Square Case: Gram Reduction and Spectral Transport for N = d + 1 Bodies* · [DOI 10.5281/zenodo.21855590](https://doi.org/10.5281/zenodo.21855590) | [square-case-lean](https://github.com/dicipler-pixel/square-case-lean): Lean proofs |
| *5D Spectral Anatomy of Four-Body Obstructions* · [DOI 10.5281/zenodo.20818168](https://doi.org/10.5281/zenodo.20818168) | [square-case-lean](https://github.com/dicipler-pixel/square-case-lean): Lean proofs of the binary-wall algebra |
| *Universal Projector Geometry from Electrical Measurements* · [DOI 10.5281/zenodo.21305024](https://doi.org/10.5281/zenodo.21305024) | [upg-lean](https://github.com/dicipler-pixel/upg-lean): Lean proofs |

---

### Tools

- [**ramanujan-normality-diagnostic**](https://github.com/dicipler-pixel/ramanujan-normality-diagnostic): builds the companion matrix of a linear recurrence and splits it into symmetric and skew parts, a quick signal for whether a simple closed form is likely to exist.

### Also

- [**rhythm-game-one**](https://github.com/dicipler-pixel/rhythm-game-one): a four-key rhythm game in plain HTML, Canvas and Web Audio.
- [**Oceans-Journey**](https://github.com/dicipler-pixel/Oceans-Journey): a small ocean adventure game.

---

Copyright (c) 2026 Jeromie Beasley. Code and proofs: [MIT](LICENSE). Written text: [CC BY 4.0](LICENSE-CC-BY-4.0.md). See [`LICENSING.md`](LICENSING.md).
