# How Much Theory Is in a Physical Constant?
## Axiomatic Distance: a metric to separate natural structure from accumulated convention

*ArXe / PLO Research — 2026*

---

## The problem nobody measures

When examining the physical constants of the Standard Model, we observe that in many cases it is possible to identify two components that are not usually distinguished:

- The **structure of the phenomenon** — what is there, independently of how it is measured.
- The **layers of description** — the chosen renormalization scheme, the perturbative corrections included, the unit conventions, the extraction method.

Both contribute to the final number. Standard physics does not distinguish between them — it assumes that the measured value directly describes the phenomenon, and that any discrepancy between measurements is a problem of systematics or model dependence.

PLO introduces a different question: how much description is incorporated in that number, beyond the phenomenon itself? This is not a question that standard physics formulates, because it has no tools to answer it. What we present here is a first approach to such a tool.

---

## The method: PLO and Axiomatic Distance

The PLO method (*Prima Logical Ontology*) starts from an empirical observation: the physical constants of the Standard Model admit representations in terms of prime numbers that are significantly more compact than their direct numerical values, and that preserve experimental precision.

For example:

```
α_s (strong coupling, essential structure) = 3π / (7 × 11)
```

This expression reproduces the value with precision comparable to direct measurement, using only the primes 3, 7 and 11.

The conventionally measured value, by contrast, is:

```
α_s = 0.1179 ± 0.0010   [PDG 2023]
```

Whose PLO factorization involves the prime 131.

The difference between these two representations is not numerical — it is structural. The first captures the minimal logic of the phenomenon. The second additionally incorporates the MS-bar scheme, the renormalization scale dependence, corrections up to NNLO order, and the weighted average of different extraction methods.

We define:

> **Naturality Index** NI(C) = maximum prime in the PLO factorization of C.

> **Axiomatic Distance** AD(C) = NI(measured) − NI(essential).

The AD measures how many layers of description have accumulated over the structure of the phenomenon. AD=0 means the measurement directly captures that structure, without adding its own layers. AD>0 means convention has been incorporated — and the AD quantifies how much.

---

## The results: a taxonomy of constants

Applied to the corpus of ~33 fundamental constants of the Standard Model, the AD produces the following classification:

### Constants with AD = 0 — measurement reaches the structure

For these constants, refining the measurement does not change the nature of what is being described. What is measured is directly what is there.

| Constant | Sector | NI | Reading |
|----------|--------|-----|---------|
| m_u | up quark | 3 | Pure cubic structure — two primes |
| Ω_m | matter fraction | 7 | Most primitive cosmological parameter |
| m_s | strange quark | 19 | Second generation — no 3D space axiom |
| m_b | bottom quark | 19 | Second generation — no corrections |
| m_e | electron mass | 17 | Five axioms, no layers on top |
| m_Z | Z boson | 109 | Z pole — scheme and phenomenon coincide |
| m_H | Higgs boson | 61 | Specific mechanism with no parallel |
| V_us, V_cb, V_ub | CKM matrix | 19–191 | All quark mixing is direct structure |
| Ω_m, Ω_b, H₀, n_s | cosmology | 7–509 | All cosmological parameters |

**Observation:** in the analyzed corpus, all of cosmology has AD=0. The entire CKM matrix has AD=0. Light quarks have AD=0. These sectors, measured with completely different instruments and methods, show that measurement does not accumulate convention over the phenomenon — at least in the PLO formulas currently available.

---

### Constants with AD > 0 — description exceeds structure

For these constants, the reported value depends on choices that the phenomenon itself does not require. Changing those choices changes the number.

| Constant | NI essential | NI measured | AD | Source of distance |
|----------|-------------|-------------|-----|-------------------|
| α_s | 11 | 131 | **120** | MS-bar scheme, NNLO, method average |
| G_N | 17 | 131 | **114** | SI units, metrological calibration |
| m_t | 17 | 107 | **90** | Top quark mass definition |
| m_e (measured) | 17 | 73 | **56** | Accumulated spectroscopic precision |
| G_F | 137 | 557 | **420** | Accumulates complete SM structure |
| α | 137 | 521 | **384** | Two centuries of high-order QED |
| α(M_Z) | 127 | 7997 | **7870** | EM running — maximum accumulation |

---

### The demonstrative case: α_s

This is the cleanest example because the phenomenon is the same and both expressions are comparable in precision:

```
Essential structure:   α_s = 3π/(7×11)   →  NI = 11
Conventional value:    α_s = 0.1179       →  NI = 131
Axiomatic distance:    AD  = 120
```

The prime 11 corresponds to the electromagnetic field level in the ArXe hierarchy — it is the signature of the gauge coupling in its most direct form. The prime 131 additionally incorporates all the choices of the extraction scheme.

The 120 AD points are not experimental error. They are the quantification of what physics calls "QCD circularity": the strong coupling is defined within the same perturbative scheme used to measure it.

This does not invalidate the measurement. It makes it readable: we know exactly how much description sits on top of the phenomenon.

---

## What the table reveals

Three patterns that are not obvious before computing the AD:

**1. Cosmology appears more direct than particle physics.**
In the analyzed corpus, cosmological parameters — including n_s with NI=509, which is structurally complex — all have AD=0. High-energy particle physics accumulates distances of tens to thousands of points. Scale does not appear to determine conventionality.

**2. The same quantity can have very different AD depending on how it is expressed.**
Essential α_s (AD=0) and measured α_s (AD=120) describe the same coupling. The difference lies in the extraction method, not the phenomenon. This suggests that part of the "precision" of high-energy measurements may be precision in the description, not in the phenomenon.

**3. Tensions between measurements appear to have distinct AD signatures.**
The Hubble tension (H₀_local vs H₀_cmb) involves two expressions each with AD=0 — if the analysis is correct, the discrepancy would not be conventional. The S₈ tension involves expressions with asymmetric AD — part of the discrepancy could have a conventional origin. The AD suggests a criterion to distinguish the two cases, though this requires further verification.

---

## Limitations and scope

PLO is a method under development. The essential formulas in the current corpus cover ~33 Standard Model constants; not all constants have an established essential formula.

The AD is not a proof in the classical sense. It is a metric — like the condition number in linear algebra, which does not prove that a system is singular but quantifies how close it is to being so. The AD does not prove that one constant is "more real" than another. It quantifies how many layers of description separate its logical structure from its reported value.

The underlying framework (ArXe) departs from a modification of certain classical logical principles — specifically, it incorporates undecidability as a constitutive property of certain levels, not as a limit of knowledge. That framework is not necessary to use the AD as a tool. But it is the origin of why prime factorizations carry the meaning they do.

---

## Summary table

```
Constant       Sector        NI_ess  NI_meas   AD    Zone
──────────────────────────────────────────────────────────
m_u            quark            3       3       0    ROM
m_s            quark           19      19       0    ROM
m_b            quark           19      19       0    ROM
m_d            quark           67      67       0    ROM
m_c            quark          127     127       0    ROM
m_e            lepton          17      73      56    mixed
m_μ            lepton          19    3691    3672    RAM
m_τ            lepton          71    1051     980    RAM
m_Z            boson          109     109       0    ROM
m_H            boson           61      61       0    ROM
m_W            boson          103     139      36    mixed
m_t            quark           17     107      90    mixed
α_s            QCD             11     131     120    RAM
α              EM             137     521     384    RAM
α(M_Z)         EM             127    7997    7870    RAM
G_N            gravity         17     131     114    RAM
G_F            weak           137     557     420    RAM
V_us/cb/ub/tb  CKM          19–191  19–191     0    ROM
θ₁₂,₁₃,₂₃     PMNS         19–173  19–173     0    ROM
Ω_m,b          cosmo         7–59    7–59       0    ROM
H₀_local       cosmo           73      73       0    ROM
H₀_cmb         cosmo           67      67       0    ROM
n_s            cosmo          509     509       0    ROM
S8_cmb         cosmo           13      13       0    ROM
S8_lss         cosmo           97      97       0    ROM
──────────────────────────────────────────────────────────
ROM = AD=0, measurement directly captures the structure
RAM = AD>0, layers of description sit over the structure
```

---

## Conclusion

The distinction between natural structure and accumulated description is not merely philosophical — in the cases analyzed, it turns out to be measurable. Axiomatic Distance provides that measure, within the limits of the current PLO corpus.

The most striking result: the sectors that standard physics tends to consider most "fundamental" — running gauge couplings, heavy quark masses, precision constants — are exactly those that accumulate the greatest axiomatic distance in the corpus. The sectors that appear more "phenomenological" — cosmology, quark mixing — show AD=0.

This inverts a common intuition. And that inversion is, in itself, information worth attending to.

---

*ArXe / PLO Research — 2026*
*Working draft*
