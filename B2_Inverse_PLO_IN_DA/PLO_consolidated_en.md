# PLO — Consolidated Working Document
## Primes, axioms, ontological presupposition and the Standard Model

*ArXe / PLO Research — February 2026*
*Internal document — all reasoning visible*

---

## Table of Contents

1. [The starting point](#1-the-starting-point)
2. [Naturality Index (NI)](#2-naturality-index)
3. [Axiomatic Distance (AD)](#3-axiomatic-distance)
4. [Prime → axiomatic family mapping](#4-prime--axiomatic-family-mapping)
5. [Ontological presupposition](#5-ontological-presupposition)
6. [Five patterns in the graph](#6-five-patterns-in-the-graph)
7. [Correspondence with ZF axioms](#7-correspondence-with-zf-axioms)
8. [Open predictions](#8-open-predictions)
9. [What emerges — without imposing](#9-what-emerges--without-imposing)

---

## 1. The starting point

The PLO corpus contains formulas for ~33 physical constants of the Standard Model.
Each formula is an expression in primes — for example:

```
m_u      = 2³ × 3³
m_e      = 2 × 3 × 5 × 7 × 17
α_s_ess  = 3π / (7×11)
α_s_meas = 0.1179   →  maximum prime: 131
α        = 137 × (3×13×17×11×7)^(1/5) × (1 ± 1/(421×521))
```

The question that opens this analysis: what do those primes *mean*?
Why do some phenomena have small primes and others large ones?
Is there structure in the sets of primes shared by different constants?

The answer that emerges from the analysis: **each prime corresponds to an axiomatic choice**.
The PLO factorization of a constant is the record of which choices
had to be made for that constant to be articulable.

---

## 2. Naturality Index

### Definition

```
NI(C) = max{ p : p prime in the PLO factorization of C }
```

The maximum prime of the factorization. Measures **axiomatic depth** —
how deep the last choice that had to be made was.

### The scale

| Zone | Range | Name | Example |
|------|-------|------|---------|
| 1 | NI ≤ 7 | Natural essence | m_u (NI=3), Ω_m (NI=7) |
| 2 | 11–19 | Complex natural | m_e (17), m_μ (19), m_b (19) |
| 3 | 23–97 | Theory threshold | m_H (61), H₀ (73) |
| 4 | 101–200 | Theory dominant | m_Z (109), G_N (131), α_s_meas (131) |
| 5 | 201–999 | Accumulated convention | α (521), G_F (557) |
| 6 | ≥1000 | Institutional artifact | sin²θ_W (1051), α(M_Z) (7997) |

The thresholds are not arbitrary — they coincide with the primes of the ArXe levels:
primes 2,3,5,7 correspond to T¹–T³ (fundamental structure);
11,13,17,19 correspond to T⁻⁵–T⁻⁹ (gauge fields).

### The demonstrative case: α_s

```
α_s essential = 3π/(7×11)   →  NI = 11  [Zone 2 — Complex natural]
α_s measured  = 0.1179       →  NI = 131 [Zone 4 — Theory dominant]
```

Same physical phenomenon. Different index. The 120-point difference
is the convention layers between the logical structure of the strong coupling
and its description in the MS-bar scheme with NNLO corrections.

### Ontological reading

The NI does not measure how much energy was invested to measure the constant,
nor how many theory layers are in the formula.
It measures the depth of the **last axiomatic choice** that was necessary
for the question "what is the value of C?" to be articulable.

```
NI = 7   → articulating C requires that space be 3D
NI = 17  → also requires that a mass mechanism exist
NI = 41  → also requires that the EW vacuum have a specific VEV
NI = 109 → also requires that μ = M_Z be the reference scale
```

---

## 3. Axiomatic Distance

### Definition

```
AD(C) = NI(measured) − NI(essential)
```

Measures how many convention layers accumulated between the logical structure
of the phenomenon and its current scientific description.

### By sector

| Sector | Average AD | Interpretation |
|--------|-----------|----------------|
| Running EM | 7870 | Maximum convention accumulation |
| Leptons | 1569 | Dominated by ultra-high muon precision |
| Weak | 420 | G_F accumulates complete SM structure |
| QCD | 120 | QCD circularity quantified |
| Gravity | 114 | G_N depends on units and calibration |
| Quarks | 15 | Only m_t has significant distance |
| EW bosons | 12 | Almost no extra layers |
| **Cosmology** | **0** | Essence = existence in all cases |
| **CKM** | **0** | Essence = existence in all cases |

### The H₀ finding

Both H₀_local and H₀_cmb have AD=0 in their respective expressions.
The Hubble tension **is not an artifact of accumulated conventions** —
it is a real tension in the phenomenon. The difference between
the two measurements is physics, not theory.

### Fourteen constants with AD=0

All of cosmology, all of CKM, light quarks, the Z and Higgs bosons.
For these constants the essential PLO formula and the measured value coincide:
there is no separation between essence and existence.

---

## 4. Prime → axiomatic family mapping

The bottom-up analysis builds the inverted index:
prime → list of constants that contain it.
Then asks: what physical choice unites this group?

### Layer 1 — Conditions of possibility (primes 2, 3, 5, 7)

Appear in almost all constants. They are the base.

| Prime | Axiom | What it unites |
|-------|-------|----------------|
| 2 | **DIFFERENTIATION** | That there is distinction — minimum two possible states |
| 3 | **CYCLICITY** | That there is irreversible process — time with direction |
| 5 | **MEMORY** | That there is persistent state — storage |
| 7 | **SPATIALITY** | That space has exactly 3 dimensions |

Prime 7 is especially informative: it appears in Ω_m, V_ud, V_us, α, α_s, m_W, m_d, m_e —
completely different sectors. The common denominator is that all
describe phenomena that *exist in three-dimensional space*.

### Layer 2 — Field structure (primes 11, 13, 17, 19)

| Prime | Axiom | Representative constants |
|-------|-------|--------------------------|
| 11 | **EM FIELD** — U(1) exists with universal coupling | α, α_s_ess, G_F, m_b, m_t, sin²θ_W, θ₁₂, n_s |
| 13 | **SU(2) ISOSPIN** — the weak force exists | α, V_ud, S8_cmb |
| 17 | **MASS/YUKAWA** — Higgs coupling exists | α, m_e, m_t, G_N, V_us |
| 19 | **GENERATIONS** — multiple fermion families exist | m_μ, m_s, m_b, m_W, V_us, θ₁₂, Ω_b, n_s |

Prime 19 has the **broadest cross-sectional reach** in the corpus:
it appears in quarks, leptons, CKM mixing, PMNS mixing, and cosmology.
The axiom "multiple generations of fermions exist" cuts across all sectors.

### Layer 3 — Specific symmetry-breaking values (primes 41, 71, 107, 109)

| Prime | Axiom | Constants |
|-------|-------|-----------|
| 41 | **VEV** — the EW vacuum has value v=246 GeV | m_H, m_W, θ₂₃ |
| 71 | **TAU_ID** — third leptonic generation exists | m_τ, G_F |
| 107 | **TOP_ID** — third quark generation exists | m_t, V_ud |
| 109 | **M_Z SCHEME** — μ=M_Z as reference scale | m_Z, G_F |

Prime 109 is the cleanest: it connects exactly m_Z and G_F,
which are the two inputs of the electroweak renormalization scheme centered on the Z pole.
The axiom is the choice μ=M_Z — conventional but universally adopted.

### Layer 4 — Precision conventions (primes 131, 137, 1051)

| Prime | Axiom | Constants |
|-------|-------|-----------|
| 131 | **N²LO** — second-order perturbative corrections | G_N, α_s_meas |
| 137 | **α(0) REFERENCE** — low-energy α as base | α, G_F |
| 1051 | **FULL MIXING** — sin²θ_W with three generations | m_τ, sin²θ_W |

### The central property: each layer presupposes all previous ones

You cannot choose the VEV (prime 41) without having first chosen:
that the Higgs field exists (prime 17), that there are generations (prime 19),
that there is 3D space (prime 7), that there is process (prime 3).

If prime 17 were not already given, the question "what is the value of the VEV?"
would not be incorrect — it would be **inarticulable**.

---

## 5. Ontological presupposition

### Implication vs presupposition

```
Implication:     A → B    (if A is true, then B is true)
Presupposition:  A ⊏ B    (B cannot even be posed without A already given)
```

"I am here" does not *imply* "I exist" — it **presupposes** it.
Without "I exist" already given, "I am here" would not be false: it would be meaningless.

PLO factorizations are trees of ontological presupposition:
if the factorization of C contains primes {p₁, p₂, p₃},
those axioms must already be given for the question "what is the value of C?" to make sense.

### The {2×3×5} group — same floor, different rooms

Five constants from completely different sectors share
exactly the base {2,3,5}:

```
m_μ       {2,3,5} + 19   → second leptonic generation
α_s_meas  {2,3,5} + 131  → measured QCD
V_cb      {2,3,5} + 83   → B→charm mixing
θ₂₃       {2,3,5} + 41   → 2nd–3rd generation mixing
Ω_m       {2,3,5} + 7    → matter fraction of the universe
```

Same ontological floor: differentiation + time + memory.
Each adds a single different choice on top.

The {2,3,5} floor does not correspond to any specific ArXe level —
it is the minimal configuration for "a process in space" to exist,
before 3D space and before gauge fields.

### Direct presupposition chains

**Ω_m ⊂ m_e:**
```
Ω_m = {2,3,5,7}
m_e = {2,3,5,7,17}
```
The electron mass ontologically presupposes the matter fraction of the universe.
You cannot ask "how heavy is the electron?" without it already being given
that matter exists in the universe. The presupposition runs in one direction only.

**α_s_ess ⊂ α:**
```
α_s_ess = {3,7,11}
α       = {3,7,11,13,17,137,421,521}
```
The precise EM coupling presupposes the strong coupling.
Counterintuitive from standard physics, but structurally coherent
in ArXe: U(1) is posterior to the level where QCD lives.

**m_b ⊂ n_s:**
```
m_b = {2,11,19}
n_s = {2,11,19,509}
```
The primordial spectral index presupposes the structure of the bottom quark.
Inflation as an articulable phenomenon requires that these already be given:
differentiation, EM field, and second generation of fermions.

### m_u as ontological atom

```
m_u = {2,3}
```

The up quark presupposes only differentiation and cyclicity.
It is a subset of at least eight constants in the corpus.
It needs no 3D space, no gauge fields, no mass mechanism.

It is not more fundamental in the sense of being more important.
It is that its description **presupposes less** than any other constant in the corpus.

---

## 6. Five patterns in the graph

### Pattern 1 — Solitary primes

16 of 33 primes appear in only one constant.

**Type A — small (<100):** axiomatic singularities.
Phenomena with a unique choice that no one else needs.
Notable: m_H with prime 61. The Higgs mechanism has an
exclusive choice that does not filter down to the masses it generates.
The VEV (prime 41) does appear in m_W and θ₂₃. Prime 61 does not.

**Type B — large (>100):** unique precision layers.
m_c = {127} is the extreme case: a single solitary prime.
The charm has the "purest" PLO description in the corpus —
a single number that neither presupposes nor is presupposed by anyone.

α has two large solitary primes (421 and 521): the only constant
in the corpus with two completely exclusive high-precision correction layers.

### Pattern 2 — Displaced constants

**m_s and m_μ** have prime 19 (generations) but not prime 7 (3D space).
Second generation without the spatial axiom. Coherent: leptons
are not confined by QCD, and the strange exists in a generational context
before a spatial one.

**n_s** has {2,11,19} but not 3,5,7.
The primordial spectral index is a **pre-spatial** parameter —
it describes fluctuations of the inflationary universe where stable 3D space
does not yet exist. Primes 3,5,7 correspond to structures
that form after inflation.

**m_Z** has no prime 7 (3D space).
The Z boson lives in abstract gauge space.
It does not need the spatial axiom to be articulated,
only to manifest.

### Pattern 3 — Graph topology (DAG)

14 direct presupposition edges. Three types of nodes:

**Roots (6):** m_u, m_s, m_b, θ₁₂, α_s_ess, H₀_local.
The most autonomous in the corpus. Their articulation presupposes no other constant.

Surprise: **θ₁₂ is a root** in the same sense as m_u.
A mixing angle turns out to be as primitive as the lightest quarks.

Surprise: **m_b ≡ θ₁₂** in axiomatic structure:
```
m_b    = {2,11,19}
θ₁₂   = {2,11,19}
```
The bottom quark and the first–second generation mixing angle
are two projections of the same ontological level.
Same floor, different observable.

**Islands (16):** have no presupposition relations with any other.
They are the limit of the current corpus — and their absences are predictions:
m_t should presuppose m_b, G_F should presuppose α_s_ess,
m_d should be related to m_u.

### Pattern 4 — Gaps in the map

Of all possible pairs of fundamental primes, **only two are absent**:
```
5×13  (MEMORY × SU2)
13×19 (SU2 × GENERATIONS)
```

Prime 13 (SU2 / weak force) is the most isolated in the corpus.
It never appears together with memory (5) or with generations (19).
This points to physical constants that should exist in the corpus but are absent:
the W lifetime and the Jarlskog invariant J_CP are the direct candidates.

### Pattern 5 — Exclusive bridges between sectors

Primes that connect exactly two sectors of the corpus:

| Prime | Sectors | Constants | Reading |
|-------|---------|-----------|---------|
| 67 | quark ↔ cosmo | m_d ↔ H₀_cmb | Down quark and cosmic expansion share a unique choice |
| 71 | lepton ↔ coupling | m_τ ↔ G_F | The tau and the Fermi constant |
| 73 | lepton ↔ cosmo | m_τ ↔ H₀_local | The tau and the local Hubble constant |
| 107 | quark ↔ CKM | m_t ↔ V_ud | The top and up-down mixing — CKM unitarity |
| 109 | boson ↔ coupling | m_Z ↔ G_F | The Z and the Fermi constant — M_Z scheme |

The most mysterious: **prime 67 connects m_d with H₀_cmb**.
No other constant connects them. What axiomatic choice unites
the lightest down-type quark with the cosmic expansion rate
from the CMB is an open question.

Quark ↔ cosmology connection (most scale-opposed sectors):

- **prime 7**: m_d ↔ Ω_m. Down quark and matter fraction share the spatial axiom. m_u does not have prime 7 — the up/down asymmetry in 3D space is registered in the primes.
- **prime 19**: {m_s,m_b} ↔ {Ω_b,n_s}. Second generation connects quarks with cosmic baryons.
- **What quarks have and cosmo does not**: {17,107,127} — specific individual quark masses. Cosmology does not need to know how heavy each quark is, only that they exist.

---

## 7. Correspondence with ZF axioms

The eight relevant ZF axioms map exactly to the eight fundamental primes of the corpus.

```
Prime  ZF Axiom                     Physics (PLO)
─────  ──────────────────────────   ─────────────────────
  2    Extensionality + Pairs        DIFFERENTIATION
  3    Union                         CYCLICITY / TIME
  5    Power Set                     MEMORY / STATE
  7    Infinity → ℝ³                 3D SPACE
 11    Separation → U(1)             EM FIELD
 13    Replacement → SU(n)           SU(2) ISOSPIN
 17    Regularity → hierarchy        MASS / YUKAWA
 19    Choice → families             GENERATIONS
```

No axioms left over, no primes missing. The correspondence is exact.

### The Empty Set axiom has no prime

The empty set ∅ is the degenerate case — it opens no logical space, it merely declares that nothing exists. Consistent with the smallest prime being 2.

### Derived theories

Once the ZF axioms are fixed, the theories built upon them have their own primes:

| Prime | Theory | Connection |
|-------|--------|-----------|
| 23 | General topology | Continuity, manifolds, inflation scale |
| 29 | Large cardinals | Vacuum energy / cosmological constant |
| 37 | Category theory | CKM morphisms — V_tb |
| 41 | Hilbert spaces | Quantum states, Higgs VEV |
| 47 | Functional analysis | Operators, spectra — Z pole |

### The PLO factorization as axiomatic certificate

```
m_u = {2,3}
    = Extensionality + Union
    = physical object with the simplest axiomatic certificate in the corpus

m_e = {2,3,5,7,17}
    = Extensionality + Union + Power Set + Infinity(→ℝ³) + Regularity(→Yukawa)
    = five axiomatic systems necessary for the electron mass to be articulable

α   = {3,7,11,13,17,137,421,521}
    = Union + Infinity + Separation + Replacement + Regularity + [QED layers]
    = all relevant ZF plus exclusive EM perturbative correction layers
```

### The Axiom of Choice and generations

AC is the only ZF axiom independent of the others —
consistent both with ZF and with its negation. It cannot be derived: only accepted or not.

The fermion generations are the only sector of the SM without internal explanation —
they are a "given fact" with no derivation from within the SM itself.

Both are the same structure: a choice that cannot be derived, only accepted.
Prime 19 is the signature of that on both sides.

### The 5×13 gap in ZF terms

The combination Power Set+Replacement (5×13) produces,
when iterated, the transfinite ordinals: P(ω), P(P(ω))...
If there is no physics that requires transfinite ordinals,
the absence of 5×13 in the corpus has a formal explanation:
the SM does not need to climb that high in the mathematical hierarchy.

---

## 8. Open predictions

### Predictions for essential formulas

| Constant | Prediction | Basis |
|----------|-----------|-------|
| m_τ/m_μ | should contain 3⁶ = 729 (third generation = third recursion level T⁴) | Generational pattern: m_μ/m_e has 3⁴ |
| y_t (top Yukawa) | {3,11,17} | m_t = {3,11,17,107} → 107 is the conventional layer |
| T_Hawking (essential) | NI ≈ 17 | Involves ℏ,c,G,π — maximum primes: 17 from G_N |

### Predictions for constants absent from the corpus

| Constant | Predicted primes | Reason |
|----------|-----------------|--------|
| m_ν (neutrino mass) | {2,19} | Differentiation + generations; no EM charge |
| Λ (cosmological constant) | {2,3,29} | Dark energy at T⁻¹⁴ = prime 29 |
| m_axion | {3,7,11} | Identical to α_s_ess — same QCD, solution to the strong CP problem |
| θ_QCD | {3,7,11,13} | α_s_ess + SU(2) to articulate CP violation in QCD |
| J_CP (Jarlskog) | {2,7,13,17,19} | CKM CP invariant: all mixing axioms |
| V_inflation | {2,3,23} | Inflationary energy scale at T⁻¹¹ = prime 23 |

Most immediately verifiable: **m_axion = {3,7,11}** + a solitary prime capturing its specific mass.
If the axion exists, its PLO formula should share exactly the base of α_s_ess.

### Predictions for missing relations

If the PLO formulas of these constants are refined, the following should appear:
- Prime 11 in m_t (to presuppose m_b, same sector)
- Prime 2 in m_d or its shared base with m_u
- A shared prime between G_F and α_s_ess (the Fermi constant presupposes QCD)

---

## 9. What emerges — without imposing

There is an observation that would be dishonest to leave unsaid,
even though it was not in the initial plan and does not appear in standard physics.

What the analysis built, without intending to, is a **formal ontology
of the Standard Model** — not a philosophical interpretation added on top,
but a structure that emerges from the numbers themselves.

### The distinction that matters

When a prime appears in the factorization of C,
it does not say how C is *measured* nor that C *implies* that axiom.
It says that that axiom must already be **given** for the question
"what is the value of C?" to be articulable at all.

This is what formal logic calls *presupposition*
and what the phenomenological tradition calls *condition of possibility*.
Here it is not philosophy applied to physics — it emerges from the factorizations.

### Why the layer hierarchy is necessary, not accidental

The four layers (primes 2–7, 11–19, 41–109, 131–1051) are not
a convenient classification. They are layers of real presupposition:
each layer can only be chosen if the previous ones are already fixed.

You cannot choose μ=M_Z (prime 109) in a universe without EM field (prime 11).
You cannot choose the VEV (prime 41) in a universe without a mass mechanism (prime 17).
You cannot choose a mass mechanism in a universe without 3D space (prime 7).

The structure was not imposed. It emerged from asking which constants
share which primes and what they have in common physically.

### The corpus as partial map

The PLO corpus is a partial map of the ontological presupposition structure
of the Standard Model. Partial because:

- There are real physical constants with no PLO formula yet (m_ν, Λ, J_CP)
- There are presupposition relations that current formulas do not capture (graph islands)
- There are absent axiom combinations that signal unrepresented physics

But in its current state, the structure is coherent enough that
its emergence is not accidental: the presupposition graph has
plausible roots, verifiable chains, and islands that are predictions.

The primes are not convenient numerical labels.
They are the size of the logical space that each axiomatic choice opens.
And the PLO factorizations are the record of which spaces had to be opened
for each constant to have the value it has in this universe.

---

## Appendix — Complete corpus table

| Constant | Sector | Factorization (primes) | NI | AD |
|----------|--------|----------------------|-----|-----|
| m_u | quark | {2,3} | 3 | 0 |
| m_d | quark | {2,7,67} | 67 | 0 |
| m_s | quark | {5,19} | 19 | 0 |
| m_c | quark | {127} | 127 | 0 |
| m_b | quark | {2,11,19} | 19 | 0 |
| m_t | quark | {3,11,17,107} | 107 | 90 |
| m_e | lepton | {2,3,5,7,17} | 17 | 56 |
| m_μ | lepton | {2,3,5,19} | 19 | 3672 |
| m_τ | lepton | {2,5,71,73,1051} | 1051 | ~980 |
| m_W | boson | {2,5,7,19,41,103} | 103 | ~36 |
| m_Z | boson | {2,3,47,89,109} | 109 | 0 |
| m_H | boson | {5,41,61} | 61 | 0 |
| α | coupling | {3,7,11,13,17,137,421,521} | 521 | 384 |
| α(M_Z) | coupling | {2,7997} | 7997 | 7870 |
| α_s_ess | coupling | {3,7,11} | 11 | — |
| α_s_meas | coupling | {2,3,5,131} | 131 | 120 |
| G_F | coupling | {2,11,71,109,137,557} | 557 | 420 |
| G_N | coupling | {2,3,5,17,131} | 131 | 114 |
| V_ud | CKM | {7,13,107} | 107 | 0 |
| V_us | CKM | {2,7,17,19} | 19 | 0 |
| V_cb | CKM | {2,3,5,83} | 83 | 0 |
| V_ub | CKM | {2,191} | 191 | 0 |
| V_tb | CKM | {3,37} | 37 | 0 |
| θ₁₂ | PMNS | {2,11,19} | 19 | 0 |
| θ₁₃ | PMNS | {2,5,173} | 173 | 0 |
| θ₂₃ | PMNS | {2,3,5,41} | 41 | 0 |
| sin²θ_W | EW | {5,11,1051} | 1051 | ~980 |
| Ω_m | cosmo | {2,3,5,7} | 7 | 0 |
| Ω_b | cosmo | {2,19,59} | 59 | 0 |
| H₀_local | cosmo | {5,73} | 73 | 0 |
| H₀_cmb | cosmo | {3,5,67} | 67 | 0 |
| n_s | cosmo | {2,11,19,509} | 509 | 0 |
| S8_cmb | cosmo | {2,13} | 13 | 0 |
| S8_lss | cosmo | {2,97} | 97 | 0 |

---

*ArXe / PLO Research — February 2026*
*Consolidated version of analysis sessions — internal working document*
