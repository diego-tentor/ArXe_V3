# Ontological Presupposition Structure in PLO
## Factorizations as trees of logical necessity

*Internal document — ArXe / PLO Research — February 2026*

---

## The principle

In ArXe, "I am here" does not *imply* "I exist" as a logical consequence —
it **ontologically presupposes** it. Without "I exist" already given, "I am here"
would not be false: it would be inarticulable. It would have no meaning as a statement.

The difference from logical implication is crucial:

```
Implication:     A → B    (if A is true, then B is true)
Presupposition:  A ⊏ B    (B cannot even be posed without A already given)
```

What the bottom-up analysis of the corpus reveals is that PLO factorizations
are exactly trees of ontological presupposition.

If the factorization of a constant C contains primes {p₁, p₂, p₃},
that does not mean C *implies* the corresponding axioms.
It means those axioms must already be **given** for the question
"what is the value of C?" to make sense.

---

## Evidence: pairs that differ by a single axiom

The corpus contains groups of constants that share exactly
the same primes except the maximum. These constants have
**the same ontological floor** and differ only in the last choice:

### The {2×3×5} group — five constants, five rooms

```
m_μ        {2,3,5} + 19   → second leptonic generation
α_s_meas   {2,3,5} + 131  → QCD measured with precision
V_cb       {2,3,5} + 83   → B→charm mixing
θ₂₃        {2,3,5} + 41   → second–third generation mixing
Ω_m        {2,3,5} + 7    → matter fraction of the universe
```

Five phenomena from completely different sectors —
a lepton, a coupling, a CKM mixing, a PMNS angle, a cosmological parameter —
share exactly the same presupposition base {2,3,5}.

All presuppose: differentiation (2) + cyclicity/time (3) + memory/state (5).
None presupposes 3D space. None presupposes gauge fields.
And on that common floor, each adds **a single different choice**.

This is exact ontological presupposition: same floor, different rooms.

---

## The presupposition chains

Pairs where one factorization is a strict subset of another
are **direct presupposition relations**:

### Ω_m ⊂ m_e

```
Ω_m = {2,3,5,7}
m_e = {2,3,5,7,17}
```

The electron mass ontologically presupposes the matter fraction
of the universe. And it adds exactly one axiom: prime 17 = mass/Yukawa mechanism.

In other words: you cannot ask "how heavy is the electron?"
without it already being given that matter exists in the universe.
But you can ask "how much matter is there?" without it being given
that fermionic mass through Yukawa exists.

The presupposition runs in one direction only.

### α_s_ess ⊂ α

```
α_s_ess = {3,7,11}
α       = {3,7,11,13,17,137,421,521}
```

The precise electromagnetic coupling ontologically presupposes
the strong coupling. α cannot be articulated without α_s already given.

This is counterintuitive from standard physics (where EM and QCD are
presented as independent), but it is structurally coherent in ArXe:
the EM field (T⁻⁵, prime 11) is structurally posterior to the
mass/3D-space level (T³, prime 7) that QCD also requires.

### m_b ⊂ n_s

```
m_b = {2,11,19}
n_s = {2,11,19,509}
```

The primordial spectral index presupposes the entire structure of the bottom quark.
And it adds exactly one axiom: prime 509 = the choice of the inflation model.

For the early universe to have a perturbation spectrum with
slope n_s requires that these already be given: differentiation (2),
EM field (11), and second generation of fermions (19).
Inflation as a physical phenomenon presupposes the existence of
second-generation matter.

---

## m_u as ontological atom

The constant with the shortest presupposition tree in the corpus:

```
m_u = {2,3}
```

Only two axioms: differentiation and cyclicity.
And it is a subset of at least eight constants:
m_μ, α_s_meas, V_cb, θ₂₃, Ω_m, m_e, m_Z, G_N.

The up quark is not "more fundamental" in the sense of being
more important or earlier in time.
It is that its **description** presupposes less.
It needs no 3D space. It needs no gauge fields.
It needs no generations or Yukawa mass.

It only needs that there be distinction and that there be process.

---

## The question it opens: what is {2×3×5}?

The floor shared by the largest group in the corpus
does not correspond to any specific ArXe level:

```
2 → T¹:  differentiation / unidirectional flow
3 → T⁻¹: irreversibility / time
5 → T²:  simultaneity / two-dimensional space
```

Together: the first three levels of positive and negative structure.
The minimal configuration for **a process in space** to exist.

Before 3D space (prime 7).
Before gauge fields (primes 11, 13).
Before the mass mechanism (prime 17).

Hypothesis: {2,3,5} is the signature of phenomena belonging
to "pre-gauge spacetime" — the layer where a classical physics
would in principle be possible, without quantum fields.
The constants that share this base are exactly those that
describe phenomena that *could exist* in a universe
with less structure than ours.

---

## Consequence for the Naturality Index

The NI (maximum prime) can now be read with ontological precision:

> **NI(C) = the highest axiom that had to be chosen for the
> question "what is the value of C?" to be articulable.**

It is not the number of axioms. It is the depth of the last one.
And that depth always presupposes all the previous ones —
because without them, not even the highest axiom would make sense.

```
NI = 7   → the question already requires that space be 3D
NI = 17  → already requires that a mass mechanism exist
NI = 41  → already requires that the EW vacuum have a specific VEV
NI = 109 → already requires that μ = M_Z be the reference scale
```

Each step up in NI is not "harder" or "higher energy".
It is ontologically deeper:
it presupposes everything before it plus one new choice.

---

## The complete structure as a graph

The presupposition relations form a directed acyclic graph (DAG)
where edges mean "A is a condition of possibility for B":

```
{2}
 ├── {2,3} = m_u
 │    ├── {2,3,5} = common floor
 │    │    ├── + 7  → Ω_m
 │    │    ├── + 17 → m_e  (presupposes Ω_m)
 │    │    ├── + 19 → m_μ
 │    │    ├── + 41 → θ₂₃
 │    │    └── + 131→ α_s_meas
 │    └── + 7,11 = α_s_ess
 │         └── + 13,17,137,... → α
 └── {2,11,19} = m_b = θ₁₂
      └── + 509 → n_s
```

This graph is not a mathematical curiosity.
It is the map of **ontological dependencies of the Standard Model**
read from its constants back to its axioms.

---

*ArXe / PLO Research — February 2026*
