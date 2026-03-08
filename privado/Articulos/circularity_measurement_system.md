# Circularity in the Measurement System

**Diego Tentor**  


---

## Abstract

The 2019 redefinition of the International System of Units (SI) fixed the values of seven fundamental constants by definition, among them Planck's constant h. This article argues that this decision introduces a structural circularity into the measurement system: units are defined in terms of constants, and constants are verified with instruments calibrated in those same units. This circularity is examined as an epistemological problem — in relation to Popperian falsifiability — and as an ontological inversion — in relation to scientific realism about physical constants.

---

## 1. The SI Before and After 2019

Until 2018, the International System of Units rested on physical artifacts and natural phenomena. The kilogram was the mass of a platinum-iridium cylinder kept at the International Bureau of Weights and Measures in Sèvres. The metre was 1/299,792,458 of the distance travelled by light in vacuum in one second. Units referenced objects or phenomena external to the measurement system.

Resolution 1 of the 26th General Conference on Weights and Measures (CGPM, 2018) changed this scheme radically. Since May 20, 2019, the SI base units are defined by fixing exact numerical values of seven fundamental constants:

| Constant | Symbol | Fixed exact value |
|----------|--------|------------------|
| Planck constant | h | 6.62607015×10⁻³⁴ J·s |
| Speed of light | c | 299,792,458 m/s |
| Elementary charge | e | 1.602176634×10⁻¹⁹ C |
| Boltzmann constant | k_B | 1.380649×10⁻²³ J/K |
| Avogadro number | N_A | 6.02214076×10²³ mol⁻¹ |
| Luminous efficacy | K_cd | 683 lm/W |
| Caesium frequency | Δν_Cs | 9,192,631,770 Hz |

The kilogram is no longer an object. It is the value of h. The ampere no longer measures the force between conductors. It is the value of e. The ontology of units changed: from the real to the ideal.

---

## 2. The Structural Circularity

The Kibble balance — the primary instrument that enabled measuring h with the precision required for the redefinition — works by comparing mechanical energy with electrical energy through quantum effects. Specifically, it uses the Josephson effect and the quantum Hall effect.

The Josephson effect relates voltage and frequency through:

$$V = \frac{n f}{K_J}, \quad K_J = \frac{2e}{h}$$

The quantum Hall effect relates resistance and fundamental constants through:

$$R_K = \frac{h}{e^2}$$

To obtain h "independently" from these relations, one needs to know e. To know e precisely, one needs quantum theory that already incorporates h. The measurements that led to the adopted value of h were not independent of each other: they shared fundamental theoretical assumptions.

CODATA averaged these measurements weighting their uncertainties, but the coherence among them was, in part, the coherence of a common theoretical framework. It was not triangulation from independent points. It was convergence within the same system.

After 2019, the system closed completely:

```
h (adopted value)
    → defines the kilogram
    → kilogram calibrates the Kibble balance
    → Kibble balance "measures" h
    → confirms the adopted value
```

h is now its own standard. The system cannot produce a result that contradicts h, because any deviation is interpreted as instrumental error, not as a correction to the value of the constant.

---

## 3. The Epistemological Problem: Popper Inverted

Popper formulated falsifiability as an epistemic attitude before a demarcation criterion: the genuine disposition to admit that a theory or a value might be wrong, not to shield ideas from empirical scrutiny [1]. In that original sense, falsifiability is not a procedure but a stance toward knowledge.

A constant with an exact value by definition has the opposite structure. It cannot be wrong. No experiment can correct it. If a measurement yields a different value, the conclusion is not "h differs from what we thought" but "the experiment has systematic error." The constant is protected from evidence.

This is not a flaw of the 2019 SI. It is a coherent pragmatic decision: a measurement system needs fixed points to function. What is philosophically significant is what this decision reveals: that h, in its current form, does not describe a physical phenomenon susceptible to empirical correction. It describes a stabilization point chosen by convention.

The distinction is precise. Before 2019, h had experimental uncertainty — CODATA 2014 reported u_r(h) = 1.2×10⁻⁸ — and that uncertainty was information about reality [2]. After 2019, h has zero uncertainty by definition, and that certainty is information about the institutional decision, not about the universe.

---

## 4. The Ontological Problem: An Inversion of Direction

In classical physics, the direction of knowledge is:

$$\text{Phenomenon} \rightarrow \text{Measurement} \rightarrow \text{Number}$$

The phenomenon exists independently. Measurement approximates it. The number converges toward the true value with increasing precision.

The 2019 SI inverts this direction:

$$\text{Number (exact)} \rightarrow \text{Defines the unit} \rightarrow \text{Determines valid measurement}$$

What counts as a correct measurement of the kilogram is now what agrees with the previously fixed value of h. The definition determines which facts are acceptable. It is not that reality corrects the definition: it is that the definition selects measurable reality.

This inversion has concrete consequences. If tomorrow technology allowed a measurement of h with greater precision than that used in 2019, and that measurement yielded a value differing in the ninth digit from the adopted one, the result would not be "h is 6.62607016×10⁻³⁴." The result would be a revision of calibration standards. The value of h would remain intact.

Physics is not arbitrary for this reason. Predictions involving h are extraordinarily precise and reproducible in any laboratory in the world. The system works. But what it produces is not a description of the universe with increasing fidelity. It is an internally coherent description, anchored in conventions that sustain one another.

---

## 5. Discussion: Realism or Conventionalism?

Scientific realism holds that physical constants describe properties of the universe that exist independently of the observer, and that scientific practice converges toward their true values [3]. Under this framework, the increasing precision of h between 1900 and 2018 would be evidence of that convergence.

The 2019 SI complicates this narrative in two ways.

First, convergence stopped by decision, not by physical limit. We did not reach the "true" value of h. We chose a sufficiently precise value and declared it exact because the system required it. CODATA 2018 does not report lower uncertainty than CODATA 2014 because measurements improved dramatically. It reports zero uncertainty because the decision to fix the value was adopted [4].

Second, the coherence of the system is not evidence of correspondence with reality. A system can be internally coherent — producing precise and reproducible predictions — without its foundations describing independent properties of the world. Coherence is a necessary but not sufficient condition for realism.

Poincaré's conventionalism anticipated part of this problem by arguing that the geometry of space is not a fact but a convention [5]. The 2019 SI extends this argument to units of measurement: the magnitude of the kilogram is not a fact of the universe but a convention fixed in relation to h, which is itself a convention fixed by consensus.

This does not imply that physics is subjective. It implies that the objectivity of physical constants is of a different kind than naive realism supposes: not correspondence with independent properties, but stability under triangulation and predictive coherence.

---

## 6. Conclusion

The 2019 SI redefinition is a sound metrological decision with excellent pragmatic reasons. It is also a philosophically significant decision that deserves to be examined as such.

The circularity it introduces — h defines the kilogram, the kilogram calibrates the instruments that "measure" h — is not an error. It is the necessary structure of any measurement system that closes in on itself to guarantee internal coherence.

What this circularity reveals is that physical constants operate in two registers simultaneously: as descriptions of physical phenomena, and as conventions that constitute the system of description. Confusing these two registers — treating h as a discovered property when it is also an adopted convention — is the core of the epistemological and ontological problem this article attempts to identify.

The question that remains open is not whether the 2019 SI is correct. It is whether scientific realism, as practiced and communicated, has the conceptual resources to simultaneously maintain that h is a property of the universe and that its value was fixed by vote.

---

## References

[1] Popper, K. R. (1959). *The Logic of Scientific Discovery*. Hutchinson. (Original in German: 1934)

[2] CODATA 2014. Mohr, P. J., Newell, D. B., & Taylor, B. N. (2016). CODATA recommended values of the fundamental physical constants: 2014. *Reviews of Modern Physics*, 88(3), 035009.

[3] Psillos, S. (1999). *Scientific Realism: How Science Tracks Truth*. Routledge.

[4] BIPM (2019). *The International System of Units (SI)*, 9th edition. Bureau International des Poids et Mesures.

[5] Poincaré, H. (1902). *La Science et l'Hypothèse*. Flammarion. (English translation: *Science and Hypothesis*, 1905)

---


