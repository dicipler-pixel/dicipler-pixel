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
| [**dirac-time-lean**](https://github.com/dicipler-pixel/dirac-time-lean) | For *The Dirac Time of the Gigantefermion*: every exact finite result the paper states: the predictive quotient (Cayley–Hamilton closure and minimality), projector tangent geometry and its block formulas, the common-clock corollaries, the weak-value bound, path-ledger descent, finite return, the entropy/correlation ledger with unitary invariance of entropy proved via Physlib, the moving-frame identity, the equal-endpoint witness, friction on projector rotations and the torus-knot silence criterion. 83 theorems + 3 headline results. | [![check](https://github.com/dicipler-pixel/dirac-time-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/dirac-time-lean/actions/workflows/build.yml) |
| [**light-ledger-lean**](https://github.com/dicipler-pixel/light-ledger-lean) | For *Light Keeps the Ledger*: boundary elimination and the matrix Smith transform, the transition-window census, Gram positivity, optical response as a reweighted metric and the peel, rigidity, completion steps, the Edition 7.2 spectral bounds and oscillator realization, with the exact counterexamples that bound each claim. 115 theorems. | [![check](https://github.com/dicipler-pixel/light-ledger-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/light-ledger-lean/actions/workflows/build.yml) |
| [**gravity-ledger-lean**](https://github.com/dicipler-pixel/gravity-ledger-lean) | For *The Ledger Outlives the Metric*: projector tangents are off-diagonal, the signed metric and reciprocal determinant, the local overlap cap, and the projector-overlap Taylor bridge from differentiability alone. 30 theorems. | [![check](https://github.com/dicipler-pixel/gravity-ledger-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/gravity-ledger-lean/actions/workflows/build.yml) |
| [**square-case-lean**](https://github.com/dicipler-pixel/square-case-lean) | For *The Square Case* and *5D Spectral Anatomy of Four-Body Obstructions*: the Gram invariant, the forced transport coefficient, symmetrisation of the eigenvalue block, the eigenframe spectrum, and interlacing (exactly one eigenvalue in every gap), and the four-body binary-wall theorems. 63 theorems. | [![check](https://github.com/dicipler-pixel/square-case-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/square-case-lean/actions/workflows/build.yml) |
| [**upg-lean**](https://github.com/dicipler-pixel/upg-lean) | For *Universal Projector Geometry*: a retained sector runs on its own exactly when its coupling vanishes, and every finite diagnostic (commutator, redistribution, zero-time memory, cross-block metric) agrees. 40 theorems. | [![check](https://github.com/dicipler-pixel/upg-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/upg-lean/actions/workflows/build.yml) |
| [**elemental-peeling-lean**](https://github.com/dicipler-pixel/elemental-peeling-lean) | For *Elemental Peeling*: what a removal takes away and what later records recover, force recovery from readings, the boundary ledger, and the exclusion certificates. 66 theorems. | [![check](https://github.com/dicipler-pixel/elemental-peeling-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/elemental-peeling-lean/actions/workflows/build.yml) |
| [**yang-mills-lean**](https://github.com/dicipler-pixel/yang-mills-lean) | For *Retained Geometry and Certified Gauge Cutoffs*: gauge-cutoff certificates, the boundary-matrix Schur certificate, and the longest finite chain from projector geometry to an allocation floor. Finite algebra only; no mass-gap claim. 77 theorems. | [![check](https://github.com/dicipler-pixel/yang-mills-lean/actions/workflows/build.yml/badge.svg)](https://github.com/dicipler-pixel/yang-mills-lean/actions/workflows/build.yml) |

Every check builds the proofs, replays them in Lean's independent kernel checker, and audits that nothing rests on `sorry` or extra axioms.

**Upstream to Mathlib** (submitted):
[#43703](https://github.com/leanprover-community/mathlib4/pull/43703), the rank-two Coxeter group is the dihedral group ·
[#43951](https://github.com/leanprover-community/mathlib4/pull/43951), a trace identity for differences of idempotents.

---

### Papers with reproduction supplements

Every paper I have published, 28 records in all, is on Zenodo: [full list](https://zenodo.org/search?q=creators.name%3A%22Beasley%2C%20Jeromie%22&sort=newest). The ones below come with proofs or reproduction code.

| Paper | Supplement |
| :--- | :--- |
| *Certified Obstructions and Exact Forcing: Earth–Moon Graph Coloring and Arithmetic Kakeya* · [DOI 10.5281/zenodo.22812167](https://doi.org/10.5281/zenodo.22812167) | [earth-moon-kakeya-certificates](https://github.com/dicipler-pixel/earth-moon-kakeya-certificates): manuscript, certificate producers, independent checkers, re-verified on every push |
| *The Offset Belongs to the Boundary* · [DOI 10.5281/zenodo.22181748](https://doi.org/10.5281/zenodo.22181748) | [offset-lean](https://github.com/dicipler-pixel/offset-lean): the Lean proofs of its finite algebra |
| *What Russell Saw: Walter Russell's Universe of Paired Motion, Read Against a Century of Physics* · [DOI 10.5281/zenodo.22986656](https://doi.org/10.5281/zenodo.22986656) | [what-russell-saw-lean](https://github.com/dicipler-pixel/what-russell-saw-lean): 43 Lean proofs, three built on Physlib; paper, mixer, ledger and scripts in the Zenodo deposit |
| *The Dirac Time of the Gigantefermion* · [DOI 10.5281/zenodo.22978630](https://doi.org/10.5281/zenodo.22978630) | [dirac-time-lean](https://github.com/dicipler-pixel/dirac-time-lean): Lean proofs of every exact finite result in the paper |
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
