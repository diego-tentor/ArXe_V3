# PLO Naturality Index
## A tool to distinguish natural structure from accumulated convention

*Internal document — ArXe / PLO Research — February 2026*

---

## The problem it solves

The PLO corpus contains formulas for physical constants ranging from
`m_u = 2³×3³` to `α = 137 × (3×13×17×11×7)^(1/5) × (1 ± 1/(421×521))`.

Both are valid PLO formulas. But they are clearly not the same type of object: one expresses minimal logical structure, the other accumulates eight layers of historical axiomatic decisions.

The PLO Naturality Index (NI) is a tool to make that distinction explicit, systematic and measurable.

---

## Definition

> **The Naturality Index of a constant is the largest prime in its PLO factorization.**

```
NI(C) = max{ p : p prime, p appears in PLO factorization of C }
```

The interpretation follows directly from the ArXe framework: each prime in the factorization corresponds to a logical n-arity. Small primes are n-arities accessible to natural structure. Large primes mark human axiomatic decisions — scheme choices, measurement conventions, institutional consensus.

---

## The scale

| Zone | NI range | Name | Description |
|------|----------|------|-------------|
| 1 | NI ≤ 7 | **Natural essence** | The phenomenon exists independently of the observer. Minimal description, no theory layers. |
| 2 | 11 ≤ NI ≤ 19 | **Complex natural** | Real phenomenon whose description requires field logic (primes from T⁻⁵ to T⁻⁹). |
| 3 | 23 ≤ NI ≤ 97 | **Theory threshold** | Real phenomenon with a first theory layer already incorporated in the description. |
| 4 | 101 ≤ NI ≤ 200 | **Theory dominant** | The description is no longer separable from the phenomenon. The value depends on the chosen scheme. |
| 5 | 201 ≤ NI ≤ 999 | **Accumulated convention** | Multiple layers of axiomatic choice. The value is an equilibrium point between theories. |
| 6 | NI ≥ 1000 | **Institutional artifact** | The measured phenomenon is inseparable from the theoretical and metrological machinery that defines it. |

The thresholds are not arbitrary — they coincide with the primes of the ArXe levels:
- Primes 2, 3, 5, 7 = levels T¹ to T³/T⁻³ (fundamental structure)
- Primes 11, 13, 17, 19 = levels T⁻⁵ to T⁻⁹ (gauge fields)
- Primes > 23 = outside the known natural field structure

---

## The corpus — results

### Zone 1 — Natural essence (NI ≤ 7)

| Constant | Factorization | NI | Sector |
|----------|--------------|-----|--------|
| m_u | 2³ × 3³ | 3 | Quark mass |
| Ω_m | 2³ × 3² × 5² × 7 | 7 | Cosmology |

**Observation:** Only two constants in the full corpus reach Zone 1. Both have direct interpretation: the up quark mass as pure cubic structure, and Ω_m as the matter fraction of the universe — the most fundamental cosmological parameter.

---

### Zone 2 — Complex natural (11 ≤ NI ≤ 19)

| Constant | Factorization | NI | Sector |
|----------|--------------|-----|--------|
| α_s (essential) | 3 × 7 × 11 | 11 | QCD |
| S₈ CMB | 2⁶ × 13 | 13 | Cosmology |
| m_e | 2 × 3 × 5 × 7 × 17 | 17 | Lepton |
| m_b | 2 × 11 × 19 | 19 | Quark |
| m_s | 5 × 19 | 19 | Quark |
| m_μ | 3⁴ + 40π + 2/19 | 19 | Lepton |
| V_us | 7 × 17 × 19 − 2 | 19 | CKM |
| θ₁₂ | 2⁴ × 11 × 19 | 19 | PMNS |

**Observation:** The electron, the muon, the bottom quark, the strange quark — the most studied and most "secure" fermions of the Standard Model — all fall in Zone 2. This is coherent: they are real phenomena whose description requires gauge field logic (primes 11–19) but no additional convention layers.

---

### Zone 3 — Theory threshold (23 ≤ NI ≤ 97)

| Constant | Factorization | NI | Sector |
|----------|--------------|-----|--------|
| V_tb | 3³ × 37 | 37 | CKM |
| θ₂₃ | 2³ × 3 × 5 × 41 | 41 | PMNS |
| Ω_b | 2 × 19 × 59 | 59 | Cosmology |
| m_H | 5 × 41 × 61 | 61 | Higgs |
| H₀ CMB | 3 × 5 × 67 | 67 | Cosmology |
| m_d | 7 × 67 − 2 | 67 | Quark |
| m_p | 2 × 7 × 67 | 67 | Hadron |
| H₀ local | 5 × 73 | 73 | Cosmology |
| V_cb | 5 × 83 − 6 | 83 | CKM |
| S₈ LSS | 2³ × 97 | 97 | Cosmology |

**Observation:** The Higgs mass and the Hubble constant share a zone — both are real but their precise value depends on the theory used to extract them. The proton mass also appears here (NI=67), reflecting that although the proton is real, its mass emerges from QCD confinement — already a first theory layer.

---

### Zone 4 — Theory dominant (101 ≤ NI ≤ 200)

| Constant | Factorization | NI | Sector |
|----------|--------------|-----|--------|
| m_W | 19 × 41 × 103 + 140 | 103 | EW boson |
| m_t | 11 × 3 × 17 × 107 | 107 | Top quark |
| m_Z | 2 × 47 × 89 × 109 | 109 | EW boson |
| m_c | 127 | 127 | Quark |
| G_N | 2 × 3 × 5 × 17 × 131 | 131 | Gravity |
| α_s (measured) | 3² × 131 / 10⁴ | 131 | QCD |

**Observation:** The W and Z bosons, the top quark, the gravitational constant — all in the same zone. And crucially: **measured α_s (NI=131) appears here while essential α_s (NI=11) is in Zone 2.** This is the direct demonstration of QCD circularity.

---

### Zone 5 — Accumulated convention (201 ≤ NI ≤ 999)

| Constant | Factorization | NI | Sector |
|----------|--------------|-----|--------|
| θ₁₃ | 5 × 173 − 8 | 173 | PMNS |
| V_ub | 2 × 191 | 191 | CKM |
| n_s | 19 × 509 − 22 | 509 | Cosmology |
| α | 137 × (...)^(1/5) × (1 ± 1/(421×521)) | 521 | EM |
| G_F | 11 × 71 × 109 × 137 + 2×557 | 557 | Weak |

---

### Zone 6 — Institutional artifact (NI ≥ 1000)

| Constant | Factorization | NI | Sector |
|----------|--------------|-----|--------|
| sin²θ_W | 11 × 1051 / (5×10⁴) | 1051 | EW |
| m_τ | 2×71×1051 + 5×73 − 1 | 1051 | Lepton |
| α(M_Z) | 2⁴ × 7997 | 7997 | Running EM |

---

## The demonstrative case: essential α_s vs measured α_s

This is the most important result of the analysis for the tool:

```
α_s  essential  =  3π / (7×11)   →  NI = 11   [Zone 2 — Complex natural]
α_s  measured   =  0.1179         →  NI = 131  [Zone 4 — Theory dominant]
```

They are the **same physical phenomenon** with two completely different index values.

The essential formula captures the minimal logical structure of the strong coupling: ternary geometric undecidability (π, with prime 3) over the levels of triadic objectivity and EM field (primes 7 and 11).

The measured value 0.1179 incorporates: the MS-bar scheme, the n_f dependence on scale, perturbative extrapolation up to NNLO order, and the weighted average of methods that do not converge. All of that accumulates in prime 131.

QCD circularity is now quantifiable:

> **QCD declares that the strong coupling is a fundamental phenomenon (NI=11) and then constructs a precision measurement of it (NI=131). The 120-point difference in the index is exactly the accumulated convention layers.**

---

## Critical usage rule: phenomenon vs expression

The ρ meson has NI=7753 (pure prime). But the ρ meson is a real hadron.

The resolution: **the index measures the naturality of the numerical expression, not of the phenomenon described.**

m_ρ = 775.3 MeV is a number that depends on the definition of the MeV, the SI system, and the calibration of reference masses. Prime 7753 measures those layers, not the reality of the meson.

To measure the naturality of the phenomenon, one must use the **essential formula** when it exists, not the measured value. This distinction is exactly the essence/existence distinction of ArXe:

```
Essence    →  PLO formula with small primes  →  low NI
Existence  →  measured CODATA value          →  high NI
```

The difference between NI(essence) and NI(existence) for the same constant is a measure of how many axiomatic layers separate the logical structure of the phenomenon from its current scientific description.

---

## Use as a diagnostic tool

**Question 1: Is this phenomenon genuinely natural or a construction?**
→ Compute NI of the essential formula. Zone 1–2: natural. Zone 5–6: construction.

**Question 2: How much theory is incorporated in this measured value?**
→ Compute NI(measured) − NI(essential). Large difference = much theory incorporated.

**Question 3: Are two constants of the same ontological "type"?**
→ Compare their zones. Constants in the same zone share the same level of theory/nature mediation.

**Question 4: Where is the threshold between nature and human convention in a sector?**
→ Order the sector's constants by NI. The largest gap between consecutive constants marks the threshold.

---

## Observations by sector

**Quark masses:** Spread from Zone 1 (m_u) to Zone 4 (m_c=127). Lighter masses are more "natural" — coherent with them emerging from simpler logical structure.

**Leptons:** m_e and m_μ in Zone 2, m_τ in Zone 6. The tau was discovered late (1975) and its mass incorporates more theory layers. The jump from 19 to 1051 is the most dramatic in the corpus.

**Cosmology:** Greatest spread in the entire corpus. Ω_m (Zone 1) coexists with n_s (Zone 5). This reflects that cosmology mixes genuinely simple parameters (matter fraction) with highly model-dependent constructions (primordial spectral index).

**CKM vs PMNS:** Similar matrices in origin, but the CKM sector reaches Zone 5 (V_ub=191) while PMNS reaches Zone 4 (θ₁₃=173). PMNS is slightly "more natural" — coherent with neutrino physics having fewer accumulated theory layers.

---

## Limits of the tool

1. The index depends on the available PLO factorization. Constants not analyzed in PLO cannot be assigned an NI.

2. The index captures the maximum prime but not the complete structure. Two constants with NI=19 can have very different characters (m_b=2×11×19 vs m_s=5×19).

3. It does not distinguish between natural complexity (phenomenon genuinely of high n-arity) and artificial complexity (theory layers). For that, the essence/existence distinction is needed, comparing NI(essential) vs NI(measured).

4. The tool does not judge what is "better" physics. A constant in Zone 6 is not less valid — it is more conventional. The distinction is ontological, not evaluative.

---

*ArXe / PLO Research — February 2026*
