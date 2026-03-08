# PLO Axiomatic Distance
## Systematic table: essence vs existence in the corpus

*Internal document — ArXe / PLO Research — February 2026*

---

## Definition

The **axiomatic distance** of a constant is the difference between its measured Naturality Index and its essential Naturality Index:

```
AD(C)  =  NI(measured) − NI(essential)
```

It measures how many convention layers separate the logical structure of the phenomenon from its current scientific description. AD=0 means the PLO formula is simultaneously the simplest possible and the one that describes the measured value — there is no separation between essence and existence in that case.

---

## Complete table

| Constant | Sector | NI(ess) | NI(meas) | AD | |
|----------|--------|---------|---------|-----|---|
| α(M_Z) | Running EM | 127 | 7997 | **7870** | ★★★ |
| m_μ | lepton | 19 | 3691 | **3672** | ★★★ |
| m_τ | lepton | 71* | 1051 | **980** | ★★★ |
| G_F | weak | 137 | 557 | **420** | ◆ |
| α | EM | 137 | 521 | **384** | ◆ |
| α_s | QCD | 11 | 131 | **120** | ◆ |
| G_N | gravity | 17 | 131 | **114** | ◆ |
| m_t | quark | 17 | 107 | **90** | ◆ |
| m_e | lepton | 17 | 73 | **56** | ◆ |
| m_W | EW boson | 103 | 139 | **36** | |
| Ω_m | cosmo | 7 | 7 | **0** | ← |
| Ω_b | cosmo | 59 | 59 | **0** | ← |
| H₀ | cosmo | 73 | 73 | **0** | ← |
| n_s | cosmo | 509 | 509 | **0** | ← |
| m_u | quark | 3 | 3 | **0** | ← |
| m_s | quark | 19 | 19 | **0** | ← |
| m_d | quark | 67 | 67 | **0** | ← |
| m_c | quark | 127 | 127 | **0** | ← |
| m_b | quark | 19 | 19 | **0** | ← |
| m_Z | EW boson | 109 | 109 | **0** | ← |
| m_H | EW boson | 61 | 61 | **0** | ← |
| V_us | CKM | 19 | 19 | **0** | ← |
| V_cb | CKM | 83 | 83 | **0** | ← |
| V_ub | CKM | 191 | 191 | **0** | ← |

*71 inferred from TAU_ID in corpus, not from a direct essential formula.

---

## By sector

| Sector | Average AD | Maximum AD | Interpretation |
|--------|-----------|-----------|----------------|
| Running EM | 7870 | 7870 | Maximum convention accumulation |
| Leptons | 1569 | 3672 | Dominated by ultra-high muon precision |
| Weak | 420 | 420 | G_F accumulates complete SM structure |
| QCD | 120 | 120 | QCD circularity quantified |
| Gravity | 114 | 114 | G_N depends on units and calibration |
| Quarks | 15 | 90 | Only m_t has significant distance |
| EW bosons | 12 | 36 | Almost no extra layers |
| Cosmology | 0 | 0 | No distance — essence = existence |
| CKM | 0 | 0 | No distance — formulas are already essential |

---

## Main patterns

### 1. Fourteen constants with AD = 0

More than half the corpus has zero axiomatic distance. For these constants the PLO formula is simultaneously the simplest possible and the one that describes the measured value with precision. There is no separation between essence and existence.

This includes all light quarks, all CKM parameters, all of cosmology (including n_s with NI=509 — its essence is already complex, but no further layers are added to it), and the Z and Higgs bosons.

**Interpretation:** For these constants the measurement process has not added convention over the natural structure. What is measured is directly what is there.

---

### 2. Running EM is the extreme case (AD = 7870)

α(M_Z) has AD=7870 — the highest in the corpus. Its essential NI is 127 (the HIER_1 prime, first-generation reference), but the measured value requires the composite prime 7997.

This reflects that α(M_Z) is not simply α measured at a different scale — it is α *redefined* within the MS-bar scheme, with explicit running, in a context where renormalization theory is completely embedded in the value. The distance of 7870 is the numerical imprint of all that theoretical machinery.

---

### 3. QCD circularity is quantifiable

```
α_s essential  =  3π/(7×11)   →  NI = 11
α_s measured   =  0.1179       →  NI = 131
AD(α_s)  =  120
```

The 120 points of distance are exactly the convention layers that QCD accumulates by declaring its coupling fundamental and then measuring it with increasing precision within the same theoretical framework. The phenomenon exists (NI=11), but the measurement buries it in convention (NI=131).

---

### 4. The muon is the most "processed" lepton

AD(m_μ) = 3672 — higher than m_τ (980) and far higher than m_e (56).

This seems paradoxical: the muon is simpler than the tau. But the distance does not measure the complexity of the phenomenon — it measures the accumulation of measurement layers. The muon g-2 experiment (BNL/Fermilab) has driven the precision of m_μ for decades, adding five-loop QED corrections, hadronic contributions, electroweak effects — each layer adds primes to the measured value.

The muon mass is the most "worked" constant in the corpus in terms of accumulated metrological effort. AD is a measure of that effort.

---

### 5. Cosmology: AD = 0 in all cases

Without exception — not even n_s (which has NI=509) accumulates axiomatic distance. The PLO formulas of cosmological constants are already their simplest expressions.

This is consistent with the nature of cosmology: parameters such as Ω_m, H₀, n_s are extracted directly from observational data with relatively few intermediate theory layers. What is measured is what is there, without the additional processing that characterizes particle physics constants.

---

### 6. Light quarks vs top quark

Five quarks have AD=0. The top quark has AD=90.

The top was discovered at the Tevatron in 1995, with its mass extracted from decay events using the fully established SM. Like the tau, it "was born inside a theory." Light quark masses are largely extracted from hadronic spectroscopy using more direct methods.

---

## AD as a diagnostic tool

**Question:** How "clean" is this measured value?
→ AD=0: what is measured is directly the structure.
→ High AD: the value is wrapped in many theory layers.

**Question:** Where are the greatest opportunities for simplification?
→ Constants with high AD are candidates for having simpler essential formulas not yet found.
→ Priority: m_μ (AD=3672), G_F (AD=420), α (AD=384).

**Question:** Are two constants describing the same phenomenon comparable?
→ Only if they have similar AD. Comparing α(M_Z) with α means comparing two objects with very different AD — they are not the same type of description.

**Question:** Is an experimental tension a tension in nature or in convention?
→ If the constants in tension have high AD, the tension may be an artifact of the convention layers, not of the phenomenon.
→ H₀: AD=0 in both expressions (local and CMB). The tension is real — it is not an artifact of accumulated convention.

---

## Methodological note

The AD depends on the existence of an identified essential formula in PLO. For constants where PLO only has the measured-value formula (such as m_τ without a direct essential formula), the calculated AD is an upper bound — the actual distance may be smaller if a simpler essential formula exists but has not yet been found.

Constants with AD=0 are the most robust: they do not depend on identifying a separate essential formula.

---

*ArXe / PLO Research — February 2026*
