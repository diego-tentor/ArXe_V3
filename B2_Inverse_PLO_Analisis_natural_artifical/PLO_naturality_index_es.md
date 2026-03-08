# Índice de Naturalidad PLO
## Una herramienta para distinguir estructura natural de convención acumulada

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## El problema que resuelve

El corpus PLO contiene fórmulas para constantes físicas que van desde
`m_u = 2³×3³` hasta `α = 137 × (3×13×17×11×7)^(1/5) × (1 ± 1/(421×521))`.

Ambas son fórmulas PLO válidas. Pero claramente no son el mismo tipo de objeto: una expresa estructura lógica mínima, la otra acumula ocho capas de decisiones axiomáticas históricas.

El Índice de Naturalidad PLO (IN) es una herramienta para hacer esa distinción explícita, sistemática y medible.

---

## Definición

> **El Índice de Naturalidad de una constante es el primo más grande en su factorización PLO.**

```
IN(C) = max{ p : p primo, p aparece en factorización PLO de C }
```

La interpretación es directa desde el marco ArXe: cada primo en la factorización corresponde a una n-aridad lógica. Los primos pequeños son n-aridades accesibles a la estructura natural. Los primos grandes marcan decisiones axiomáticas humanas — elecciones de esquema, convenciones de medición, consensos institucionales.

---

## La escala

| Zona | Rango IN | Nombre | Descripción |
|------|----------|--------|-------------|
| 1 | IN ≤ 7 | **Esencia natural** | El fenómeno existe independientemente del observador. Descripción mínima, sin capas teóricas. |
| 2 | 11 ≤ IN ≤ 19 | **Natural complejo** | Fenómeno real con descripción que requiere lógica de campos (primos de T⁻⁵ a T⁻⁹). |
| 3 | 23 ≤ IN ≤ 97 | **Umbral teoría** | Fenómeno real con primera capa teórica ya incorporada en la descripción. |
| 4 | 101 ≤ IN ≤ 200 | **Teoría dominante** | La descripción ya no es separable del fenómeno. El valor depende del esquema elegido. |
| 5 | 201 ≤ IN ≤ 999 | **Convención acumulada** | Múltiples capas de elección axiomática. El valor es un punto de equilibrio entre teorías. |
| 6 | IN ≥ 1000 | **Artefacto institucional** | El fenómeno medido es inseparable de la maquinaria teórica y metrológica que lo define. |

Los umbrales no son arbitrarios — coinciden con los primos de los niveles ArXe:
- Primos 2, 3, 5, 7 = niveles T¹ a T³/T⁻³ (estructura fundamental)
- Primos 11, 13, 17, 19 = niveles T⁻⁵ a T⁻⁹ (campos de gauge)
- Primos > 23 = fuera de la estructura natural de campos conocida

---

## El corpus — resultados

### Zona 1 — Esencia natural (IN ≤ 7)

| Constante | Factorización | IN | Sector |
|-----------|--------------|-----|--------|
| m_u | 2³ × 3³ | 3 | Quark masa |
| Ω_m | 2³ × 3² × 5² × 7 | 7 | Cosmología |

**Observación:** Solo dos constantes en el corpus completo alcanzan Zona 1. Ambas tienen interpretación directa: la masa del quark up como estructura cúbica pura, y Ω_m como la fracción de materia del universo — el parámetro cosmológico más fundamental.

---

### Zona 2 — Natural complejo (11 ≤ IN ≤ 19)

| Constante | Factorización | IN | Sector |
|-----------|--------------|-----|--------|
| α_s (esencial) | 3 × 7 × 11 | 11 | QCD |
| S₈ CMB | 2⁶ × 13 | 13 | Cosmología |
| m_e | 2 × 3 × 5 × 7 × 17 | 17 | Lepton |
| m_b | 2 × 11 × 19 | 19 | Quark |
| m_s | 5 × 19 | 19 | Quark |
| m_μ | 3⁴ + 40π + 2/19 | 19 | Lepton |
| V_us | 7 × 17 × 19 − 2 | 19 | CKM |
| θ₁₂ | 2⁴ × 11 × 19 | 19 | PMNS |

**Observación:** El electrón, el muón, el quark bottom, el quark strange — los fermiones más estudiados y más "seguros" del Modelo Estándar — caen todos en Zona 2. Esto es coherente: son fenómenos reales cuya descripción requiere la lógica de campos de gauge (primos 11–19) pero no capas adicionales de convención.

---

### Zona 3 — Umbral teoría (23 ≤ IN ≤ 97)

| Constante | Factorización | IN | Sector |
|-----------|--------------|-----|--------|
| V_tb | 3³ × 37 | 37 | CKM |
| θ₂₃ | 2³ × 3 × 5 × 41 | 41 | PMNS |
| Ω_b | 2 × 19 × 59 | 59 | Cosmología |
| m_H | 5 × 41 × 61 | 61 | Higgs |
| H₀ CMB | 3 × 5 × 67 | 67 | Cosmología |
| m_d | 7 × 67 − 2 | 67 | Quark |
| m_p | 2 × 7 × 67 | 67 | Hadrón |
| H₀ local | 5 × 73 | 73 | Cosmología |
| V_cb | 5 × 83 − 6 | 83 | CKM |
| S₈ LSS | 2³ × 97 | 97 | Cosmología |

**Observación:** La masa del Higgs y la constante de Hubble comparten zona — ambas son reales pero su valor preciso depende de la teoría empleada para extraerlas. La masa del protón también aparece aquí (IN=67), reflejando que aunque el protón es real, su masa emerge del confinamiento QCD — ya una primera capa teórica.

---

### Zona 4 — Teoría dominante (101 ≤ IN ≤ 200)

| Constante | Factorización | IN | Sector |
|-----------|--------------|-----|--------|
| m_W | 19 × 41 × 103 + 140 | 103 | Bosón EW |
| m_t | 11 × 3 × 17 × 107 | 107 | Quark top |
| m_Z | 2 × 47 × 89 × 109 | 109 | Bosón EW |
| m_c | 127 | 127 | Quark |
| G_N | 2 × 3 × 5 × 17 × 131 | 131 | Gravedad |
| α_s (medido) | 3² × 131 / 10⁴ | 131 | QCD |

**Observación:** Los bosones W y Z, el quark top, la constante gravitacional — todos en la misma zona. Y crucialmente: **α_s medido (IN=131) aparece aquí mientras que α_s esencial (IN=11) está en Zona 2.** Esta es la demostración directa de la circularidad QCD.

---

### Zona 5 — Convención acumulada (201 ≤ IN ≤ 999)

| Constante | Factorización | IN | Sector |
|-----------|--------------|-----|--------|
| θ₁₃ | 5 × 173 − 8 | 173 | PMNS |
| V_ub | 2 × 191 | 191 | CKM |
| n_s | 19 × 509 − 22 | 509 | Cosmología |
| α | 137 × (...)^(1/5) × (1 ± 1/(421×521)) | 521 | EM |
| G_F | 11 × 71 × 109 × 137 + 2×557 | 557 | Débil |

---

### Zona 6 — Artefacto institucional (IN ≥ 1000)

| Constante | Factorización | IN | Sector |
|-----------|--------------|-----|--------|
| sin²θ_W | 11 × 1051 / (5×10⁴) | 1051 | EW |
| m_τ | 2×71×1051 + 5×73 − 1 | 1051 | Lepton |
| α(M_Z) | 2⁴ × 7997 | 7997 | EM running |

---

## El caso demostrativo: α_s esencial vs α_s medido

Este es el resultado más importante del análisis para la herramienta:

```
α_s  esencial  =  3π / (7×11)   →  IN = 11   [Zona 2 — Natural complejo]
α_s  medido    =  0.1179         →  IN = 131  [Zona 4 — Teoría dominante]
```

Son el **mismo fenómeno físico** con dos expresiones completamente distintas en el índice.

La fórmula esencial captura la estructura lógica mínima del acoplamiento fuerte: indecidibilidad geométrica ternaria (π, con primo 3) sobre los niveles de objetividad triádica y campo EM (primos 7 y 11).

El valor medido 0.1179 incorpora: el esquema MS-bar, la dependencia de n_f con la escala, la extrapolación perturbativa hasta orden NNLO, y el promedio ponderado de métodos que no convergen. Todo eso se acumula en el primo 131.

La circularidad de QCD es ahora cuantificable:

> **QCD declara que el acoplamiento fuerte es un fenómeno fundamental (IN=11) y luego construye una medición de precisión del mismo (IN=131). Los 120 puntos de diferencia en el índice son exactamente las capas de convención acumuladas.**

---

## Regla de uso crítica: fenómeno vs expresión

El mesón ρ tiene IN=7753 (primo puro). Pero el mesón ρ es un hadrón real.

La resolución: **el índice mide la naturalidad de la expresión numérica, no del fenómeno descrito.**

m_ρ = 775.3 MeV es un número que depende de la definición del MeV, del sistema SI, y de la calibración de masas de referencia. El primo 7753 mide esas capas, no la realidad del mesón.

Para medir la naturalidad del fenómeno se debe usar la **fórmula esencial** cuando existe, no el valor medido. Esta distinción es exactamente la distinción esencia/existencia de ArXe:

```
Esencia   →  fórmula PLO con primos pequeños  →  IN bajo
Existencia →  valor CODATA medido             →  IN alto
```

La diferencia entre IN(esencia) e IN(existencia) para una misma constante es una medida de cuántas capas axiomáticas separan la estructura lógica del fenómeno de su descripción científica actual.

---

## Uso como herramienta de diagnóstico

**Pregunta 1: ¿Es este fenómeno genuinamente natural o una construcción?**
→ Calcular IN de la fórmula esencial. Zona 1–2: natural. Zona 5–6: construcción.

**Pregunta 2: ¿Cuánta teoría hay incorporada en este valor medido?**
→ Calcular IN(medido) − IN(esencial). Diferencia grande = mucha teoría incorporada.

**Pregunta 3: ¿Dos constantes son del mismo "tipo" ontológico?**
→ Comparar sus zonas. Constantes en la misma zona comparten el nivel de mediación teoría/naturaleza.

**Pregunta 4: ¿Dónde está el umbral entre naturaleza y humano en un sector?**
→ Ordenar las constantes del sector por IN. El salto más grande entre constantes consecutivas marca el umbral.

---

## Observaciones por sector

**Quarks de masa:** Dispersión de Zona 1 (m_u) a Zona 4 (m_c=127). Las masas más ligeras son más "naturales" — coherente con que emergen de estructura lógica más simple.

**Leptones:** m_e y m_μ en Zona 2, m_τ en Zona 6. El tau se descubrió tardíamente (1975) y su masa incorpora más capas teóricas. El salto de 19 a 1051 es el más dramático del corpus.

**Cosmología:** Mayor dispersión de todo el corpus. Ω_m (Zona 1) convive con n_s (Zona 5). Esto refleja que la cosmología mezcla parámetros genuinamente simples (fracción de materia) con construcciones altamente modelo-dependientes (índice espectral primordial).

**CKM vs PMNS:** Matrices similares en origen pero el sector CKM llega hasta Zona 5 (V_ub=191) mientras PMNS llega hasta Zona 4 (θ₁₃=173). PMNS es ligeramente "más natural" — coherente con que la física de neutrinos tiene menos capas de teoría acumulada.

---

## Límites de la herramienta

1. El índice depende de la factorización PLO disponible. Constantes no analizadas en PLO no tienen IN asignable.

2. El índice captura el primo máximo pero no la estructura completa. Dos constantes con IN=19 pueden tener caracteres muy distintos (m_b=2×11×19 vs m_s=5×19).

3. No distingue entre complejidad natural (fenómeno genuinamente de alta n-aridad) y complejidad artificial (capas de teoría). Para eso se necesita la distinción esencia/existencia y comparar IN(esencial) vs IN(medido).

4. La herramienta no juzga qué es "mejor" física. Una constante en Zona 6 no es menos válida — es más convencional. La distinción es ontológica, no evaluativa.

---

*ArXe / PLO Research — Febrero 2026*
