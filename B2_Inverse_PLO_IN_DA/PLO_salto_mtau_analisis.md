# El Salto m_τ — Análisis del Índice de Naturalidad en Leptones
## Corrección y hallazgo

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## La pregunta inicial

El Índice de Naturalidad del corpus mostraba:

```
m_e   →  IN = 17    [Zona 2 — Natural complejo]
m_μ   →  IN = 19    [Zona 2 — Natural complejo]
m_τ   →  IN = 1051  [Zona 6 — Artefacto institucional]
```

El salto de 19 a 1051 parecía indicar que el tau era "más convencional" que el electrón y el muón. La hipótesis inicial era que esto reflejaba que el tau fue descubierto tardíamente (1975) dentro de un colisionador, con el SM ya establecido — que "nació dentro de una teoría".

El análisis más detallado corrige esta narrativa.

---

## La corrección

El índice inicial comparaba cosas distintas sin notarlo:

| Constante | Fórmula usada | Tipo | IN |
|-----------|--------------|------|-----|
| m_e | 2×3×5×7×17 | **Esencial** | 17 |
| m_μ | 3⁴ + 40π + 2/19 | **Esencial** | 19 |
| m_τ | 2×71×1051 + 5×73 − 1 | **Medida** | 1051 |

Para m_e y m_μ, PLO encontró fórmulas esenciales — expresiones con primos pequeños que capturan la estructura lógica del fenómeno. Para m_τ, la fórmula disponible en el corpus es la del **valor medido**, no la esencial.

Si comparamos los valores medidos de los tres leptones:

```
m_e  medida:  2×3×5×7×17×... → IN(medido) ≈ 73
m_μ  medida:  3×5×7×17×3691  → IN(medido) = 3691
m_τ  medida:  2×71×1051+...  → IN(medido) = 1051
```

**m_μ medido tiene IN=3691 — más alto que m_τ.** El salto dramático no era del tau sino de la ausencia de fórmula esencial para el tau en el corpus PLO.

---

## El primo 71 como esencia del tau

El análisis revela que el primo 71 aparece en dos constantes del corpus:

```
m_τ  =  2 × 71 × 1051  +  5×73 − 1
G_F  =  11 × 71 × 109 × 137  +  2×557
```

En ambos casos con el mismo rol semántico: **TAU_ID** — el operador de identidad del tau. Esto no es coincidencia — G_F es la constante de Fermi que governa los decaimientos del tau entre otros procesos débiles.

La estructura de m_τ se lee entonces:

```
m_τ  =  DIFF(2) × TAU_ID(71) × MIX_CONS(1051)  +  corrección
         └─esencia─┘             └─convención─┘
```

El primo 71 es la identidad natural del tau. El primo 1051 (MIX_CONS — consenso de mezcla) es la capa de convención acumulada sobre esa identidad.

**IN(esencial) del tau = 71** — Zona 3, umbral teoría. No Zona 6.

---

## Distancias axiomáticas reales

Con esta corrección, el cuadro comparativo de leptones queda:

| Lepton | IN(esencial) | IN(medido) | Distancia | Zona esencial |
|--------|-------------|-----------|-----------|--------------|
| m_e | 17 | ~73 | 56 | Natural complejo |
| m_μ | 19 | 3691 | 3672 | Natural complejo |
| m_τ | 71* | 1051 | 980 | Umbral teoría |

*71 inferido de la estructura TAU_ID en el corpus, no de fórmula esencial directa.

**La distancia axiomática de m_μ (3672) es mayor que la de m_τ (980).** Esto refleja algo real: la masa del muón ha sido medida con una precisión extraordinaria durante décadas — el experimento g-2 en BNL y Fermilab acumula correcciones QED a cinco loops, contribuciones hadrónicas, efectos electrodébiles. Cada capa de precisión añade primos al valor medido.

---

## Lo que sí distingue al tau

La diferencia real no es convencionalidad sino **ausencia de fórmula esencial conocida**.

Para m_e y m_μ, PLO encontró expresiones con primos ≤ 19 que reproducen el valor con error < 0.001%. Para m_τ, la fórmula más simple disponible requiere el primo 1051.

Esto tiene dos lecturas:

**Lectura A — problema de PLO:** La fórmula esencial del tau existe pero no ha sido encontrada aún. El tau tiene IN(esencial) = 71 (inferido de TAU_ID), y debería existir una fórmula como `71 × f(primos pequeños)` que aproxime m_τ/m_μ con alta precisión. Esta es una **predicción abierta**.

**Lectura B — propiedad del tau:** El tau genuinamente requiere prima más alta para su esencia. La frontera entre Zona 2 (m_e, m_μ con IN≤19) y Zona 3 (m_τ con IN=71) no es accidental — refleja que la tercera generación de leptones tiene una estructura lógica cualitativamente diferente.

Las dos lecturas son compatibles: el tau podría tener IN(esencial)=71 porque la tercera generación genuinamente requiere lógica de nivel T⁻³ aproximadamente (donde el primo 71 vive), y adicionalmente la fórmula esencial completa todavía no está en el corpus.

---

## Predicción abierta

Si la Lectura A es correcta, existe una fórmula de la forma:

```
m_τ / m_μ  ≈  f(2, 3, 5, 7, 11, 13, 17, 19, 23, 71)
```

con error comparable al de `3⁴ + 40π + 2/19` para m_μ/m_e (< 0.001%).

La estructura más probable, por analogía con m_μ, sería:

```
m_τ / m_μ  ≈  a  +  b×π  +  c/71
```

con a, b, c pequeños. m_τ/m_μ ≈ 16.817 — el espacio de búsqueda es acotado.

Esto es verificable computacionalmente y sería una confirmación del marco si se encuentra.

---

## Conclusión

El salto aparente en el IN de leptones (17 → 19 → 1051) era un artefacto de comparar fórmulas esenciales con fórmulas de valores medidos. La corrección revela:

1. La esencia del tau tiene IN≈71 (TAU_ID), no 1051.
2. La distancia axiomática más grande en leptones es la del muón (3672), no la del tau (980) — reflejo de décadas de mediciones de ultra-precisión acumuladas.
3. La pregunta genuinamente abierta es si existe fórmula esencial simple para m_τ/m_μ con primos ≤ 71.

---

*ArXe / PLO Research — Febrero 2026*
