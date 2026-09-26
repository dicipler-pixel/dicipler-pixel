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
| [**acwindow-lean**](https://github.com/dicipler-pixel/acwindow-lean) | Andrews–Curtis moves for the SAIR challenge: the fold AK(n) → AK(−n−1) for every integer n, a nine-move path, and detour widths stated against the official competition definitions. | [![check](https://github.com/dicipler-pixel/acwindow-lean/actions/workflows/acwindow.yml/badge.svg)](https://github.com/dicipler-pixel/acwindow-lean/actions/workflows/acwindow.yml) |

Every check builds the proofs, replays them in Lean's independent kernel checker, and audits that nothing rests on `sorry` or extra axioms.

**Upstream to Mathlib** (submitted):
[#43703](https://github.com/leanprover-community/mathlib4/pull/43703), the rank-two Coxeter group is the dihedral group ·
[#43951](https://github.com/leanprover-community/mathlib4/pull/43951), a trace identity for differences of idempotents.

---

### Papers with reproduction supplements

| Paper | Supplement |
| :--- | :--- |
| *Certified Obstructions and Exact Forcing: Earth–Moon Graph Coloring and Arithmetic Kakeya* · [DOI 10.5281/zenodo.22812168](https://doi.org/10.5281/zenodo.22812168) | [earth-moon-kakeya-certificates](https://github.com/dicipler-pixel/earth-moon-kakeya-certificates): manuscript, certificate producers, independent checkers, re-verified on every push |
| *The Offset Belongs to the Boundary* · [DOI 10.5281/zenodo.22555919](https://doi.org/10.5281/zenodo.22555919) | [offset-lean](https://github.com/dicipler-pixel/offset-lean): the Lean proofs of its finite algebra |

---

### Tools

- [**ramanujan-normality-diagnostic**](https://github.com/dicipler-pixel/ramanujan-normality-diagnostic): builds the companion matrix of a linear recurrence and splits it into symmetric and skew parts, a quick signal for whether a simple closed form is likely to exist.

### Also

- [**rhythm-game-one**](https://github.com/dicipler-pixel/rhythm-game-one): a four-key rhythm game in plain HTML, Canvas and Web Audio.
- [**Oceans-Journey**](https://github.com/dicipler-pixel/Oceans-Journey): a small ocean adventure game.
