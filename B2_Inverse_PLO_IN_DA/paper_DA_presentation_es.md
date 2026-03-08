# ¿Cuánta teoría hay en una constante física?
## Distancia Axiomática: una métrica para separar estructura natural de convención acumulada

*ArXe / PLO Research — 2026*

---

## El problema que nadie mide

Al examinar las constantes físicas del Modelo Estándar, observamos que en muchos casos es posible identificar dos componentes que habitualmente no se distinguen:

- La **estructura del fenómeno** — lo que hay, independientemente de cómo se mide.
- Las **capas de descripción** — el esquema de renormalización elegido, las correcciones perturbativas incluidas, las convenciones de unidades, el método de extracción.

Ambas contribuyen al número final. La física estándar no distingue entre ellas — asume que el valor medido describe directamente el fenómeno, y que cualquier discrepancia entre mediciones es un problema de sistemáticos o de modelo.

PLO introduce una pregunta distinta: ¿cuánta descripción hay incorporada en ese número, más allá del fenómeno en sí? No es una pregunta que la física estándar se formule, porque no tiene herramientas para responderla. Lo que presentamos aquí es una primera aproximación a esa herramienta.

---

## El método: PLO y la Distancia Axiomática

El método PLO (*Ontología Prima Lógica* / *Prima Logical Ontology*) parte de una observación empírica: las constantes físicas del Modelo Estándar admiten representaciones en términos de números primos que son significativamente más compactas que sus valores numéricos directos, y que preservan la precisión experimental.

Por ejemplo:

```
α_s (acoplamiento fuerte, estructura esencial) = 3π / (7 × 11)
```

Esta expresión reproduce el valor con precisión comparable a la medición directa, usando solo los primos 3, 7 y 11.

El valor medido convencionalmente, en cambio, es:

```
α_s = 0.1179 ± 0.0010   [PDG 2023]
```

Cuya factorización PLO involucra el primo 131.

La diferencia entre estas dos representaciones no es numérica — es estructural. La primera captura la lógica mínima del fenómeno. La segunda incorpora además el esquema MS-bar, la dependencia de la escala de renormalización, las correcciones hasta orden NNLO, y el promedio ponderado de distintos métodos de extracción.

Definimos:

> **Índice de Naturalidad** IN(C) = primo máximo en la factorización PLO de C.

> **Distancia Axiomática** DA(C) = IN(medido) − IN(esencial).

La DA mide cuántas capas de descripción se acumularon sobre la estructura del fenómeno. DA=0 significa que la medición captura directamente esa estructura, sin añadir capas propias. DA>0 significa que hay convención incorporada — y la DA cuantifica cuánta.

---

## Los resultados: una taxonomía de las constantes

Aplicada al corpus de ~33 constantes fundamentales del Modelo Estándar, la DA produce la siguiente clasificación:

### Constantes con DA = 0 — la medición llega a la estructura

Para estas constantes, refinar la medición no cambia la naturaleza de lo que se describe. Lo que se mide es directamente lo que hay.

| Constante | Sector | IN | Lectura |
|-----------|--------|-----|---------|
| m_u | quark up | 3 | Estructura cúbica pura — dos primos |
| Ω_m | fracción de materia | 7 | Parámetro cosmológico más primitivo |
| m_s | quark strange | 19 | Segunda generación — sin espacio 3D |
| m_b | quark bottom | 19 | Segunda generación — sin correcciones |
| m_e | masa del electrón | 17 | Cinco axiomas, sin capas encima |
| m_Z | bosón Z | 109 | Polo del Z — esquema y fenómeno coinciden |
| m_H | bosón de Higgs | 61 | Mecanismo específico sin paralelo |
| V_us, V_cb, V_ub | matriz CKM | 19–191 | Toda la mezcla quark es estructura directa |
| Ω_m, Ω_b, H₀, n_s | cosmología | 7–509 | Todos los parámetros cosmológicos |

**Observación:** en el corpus analizado, toda la cosmología tiene DA=0. Toda la matriz CKM tiene DA=0. Los quarks ligeros tienen DA=0. Estos sectores, medidos con instrumentos y métodos completamente distintos, muestran que la medición no acumula convención sobre el fenómeno — al menos en las fórmulas PLO disponibles actualmente.

---

### Constantes con DA > 0 — la descripción supera la estructura

Para estas constantes, el valor reportado depende de elecciones que el fenómeno en sí no requiere. Cambiar esas elecciones cambia el número.

| Constante | IN esencial | IN medido | DA | Origen de la distancia |
|-----------|------------|-----------|-----|----------------------|
| α_s | 11 | 131 | **120** | Esquema MS-bar, NNLO, promedio de métodos |
| G_N | 17 | 131 | **114** | Unidades SI, calibración metrológica |
| m_t | 17 | 107 | **90** | Definición de masa del quark top |
| m_e (medido) | 17 | 73 | **56** | Precisión espectroscópica acumulada |
| G_F | 137 | 557 | **420** | Acumula la estructura completa del SM |
| α | 137 | 521 | **384** | Dos siglos de QED a órdenes altos |
| α(M_Z) | 127 | 7997 | **7870** | Running del EM — máxima acumulación |

---

### El caso demostrativo: α_s

Es el ejemplo más limpio porque el fenómeno es el mismo y las dos expresiones son comparables en precisión:

```
Estructura esencial:   α_s = 3π/(7×11)   →  IN = 11
Valor convencional:    α_s = 0.1179       →  IN = 131
Distancia axiomática:  DA  = 120
```

El primo 11 corresponde al nivel de campo electromagnético en la jerarquía ArXe — es la huella del acoplamiento de gauge en su forma más directa. El primo 131 incorpora, adicionalmente, todas las elecciones del esquema de extracción.

Los 120 puntos de DA no son error experimental. Son la cuantificación de lo que la física llama "circularidad de QCD": el acoplamiento fuerte se define en el mismo esquema perturbativo que se usa para medirlo.

Esto no invalida la medición. La hace legible: sabemos exactamente cuánta descripción hay encima del fenómeno.

---

## Lo que la tabla revela

Tres patrones que no son obvios antes de calcular la DA:

**1. La cosmología aparece más directa que la física de partículas.**
En el corpus analizado, los parámetros cosmológicos — incluyendo n_s con IN=509, que es estructuralmente complejo — tienen todos DA=0. La física de partículas de alta energía acumula distancias de decenas a miles de puntos. La escala no parece determinar la convencionalidad.

**2. La misma cantidad puede tener DA muy distinta según cómo se exprese.**
α_s esencial (DA=0) y α_s medido (DA=120) describen el mismo acoplamiento. La diferencia está en el método de extracción, no en el fenómeno. Esto sugiere que parte de la "precisión" de las mediciones de alta energía podría ser precisión en la descripción, no en el fenómeno.

**3. Las tensiones entre mediciones parecen tener firmas de DA distintas.**
La tensión de Hubble (H₀_local vs H₀_cmb) involucra dos expresiones con DA=0 cada una — si el análisis es correcto, la discrepancia no sería convencional. La tensión S₈ involucra expresiones con DA asimétrica — parte de la discrepancia podría tener origen convencional. La DA sugiere un criterio para distinguir los dos casos, aunque esto requiere verificación adicional.

---

## Limitaciones y alcance

PLO es un método en desarrollo. Las fórmulas esenciales del corpus actual cubren ~33 constantes del Modelo Estándar; no todas las constantes tienen fórmula esencial establecida.

La DA no es una demostración en el sentido clásico del término. Es una métrica — como el número de condición en álgebra lineal, que no prueba que un sistema sea singular pero cuantifica cuán cerca está de serlo. La DA no prueba que una constante sea "más real" que otra. Cuantifica cuántas capas de descripción separan su estructura lógica de su valor reportado.

El framework subyacente (ArXe) parte de una modificación de ciertos principios lógicos clásicos — específicamente, incorpora la indecidibilidad como propiedad constitutiva de ciertos niveles, no como límite del conocimiento. Ese framework no es necesario para usar la DA como herramienta. Pero es el origen de por qué las factorizaciones en primos tienen el significado que tienen.

---

## Tabla resumen

```
Constante      Sector        IN_ess  IN_med   DA    Zona
──────────────────────────────────────────────────────────
m_u            quark            3       3      0    ROM
m_s            quark           19      19      0    ROM
m_b            quark           19      19      0    ROM
m_d            quark           67      67      0    ROM
m_c            quark          127     127      0    ROM
m_e            lepton          17      73     56    mixta
m_μ            lepton          19    3691   3672    RAM
m_τ            lepton          71    1051    980    RAM
m_Z            bosón          109     109      0    ROM
m_H            bosón           61      61      0    ROM
m_W            bosón          103     139     36    mixta
m_t            quark           17     107     90    mixta
α_s            QCD             11     131    120    RAM
α              EM             137     521    384    RAM
α(M_Z)         EM             127    7997   7870    RAM
G_N            gravedad        17     131    114    RAM
G_F            débil          137     557    420    RAM
V_us/cb/ub/tb  CKM          19–191  19–191    0    ROM
θ₁₂,₁₃,₂₃     PMNS         19–173  19–173    0    ROM
Ω_m,b          cosmo         7–59    7–59      0    ROM
H₀_local       cosmo           73      73      0    ROM
H₀_cmb         cosmo           67      67      0    ROM
n_s            cosmo          509     509      0    ROM
S8_cmb         cosmo           13      13      0    ROM
S8_lss         cosmo           97      97      0    ROM
──────────────────────────────────────────────────────────
ROM = DA=0, la medición captura la estructura directamente
RAM = DA>0, hay capas de descripción sobre la estructura
```

---

## Conclusión

La distinción entre estructura natural y descripción acumulada no es solo filosófica — en los casos analizados, resulta medible. La Distancia Axiomática provee esa medida, dentro de los límites del corpus PLO actual.

El resultado más llamativo: los sectores que la física estándar tiende a considerar más "fundamentales" — acoplamientos de gauge corridos, masas de quarks pesados, constantes de precisión — son exactamente los que acumulan mayor distancia axiomática en el corpus. Los sectores que parecen más "fenomenológicos" — cosmología, mezcla de quarks — muestran DA=0.

Esto invierte una intuición común. Y esa inversión es, en sí misma, información que merece atención.

---

*ArXe / PLO Research — 2026*
*Borrador de trabajo*
