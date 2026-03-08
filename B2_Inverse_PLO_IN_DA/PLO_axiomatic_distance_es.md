# Distancia Axiomática PLO
## Tabla sistemática: esencia vs existencia en el corpus

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## Definición

La **distancia axiomática** de una constante es la diferencia entre su Índice de Naturalidad medido y su Índice de Naturalidad esencial:

```
DA(C)  =  IN(medido) − IN(esencial)
```

Mide cuántas capas de convención separan la estructura lógica del fenómeno de su descripción científica actual. DA=0 significa que la fórmula PLO es simultáneamente la más simple posible y la que describe el valor medido — no hay separación entre esencia y existencia en ese caso.

---

## La tabla completa

| Constante | Sector | IN(ess) | IN(med) | DA | |
|-----------|--------|---------|---------|-----|---|
| α(M_Z) | EM running | 127 | 7997 | **7870** | ★★★ |
| m_μ | lepton | 19 | 3691 | **3672** | ★★★ |
| m_τ | lepton | 71* | 1051 | **980** | ★★★ |
| G_F | débil | 137 | 557 | **420** | ◆ |
| α | EM | 137 | 521 | **384** | ◆ |
| α_s | QCD | 11 | 131 | **120** | ◆ |
| G_N | gravedad | 17 | 131 | **114** | ◆ |
| m_t | quark | 17 | 107 | **90** | ◆ |
| m_e | lepton | 17 | 73 | **56** | ◆ |
| m_W | bosón EW | 103 | 139 | **36** | |
| Ω_m | cosmo | 7 | 7 | **0** | ← |
| Ω_b | cosmo | 59 | 59 | **0** | ← |
| H₀ | cosmo | 73 | 73 | **0** | ← |
| n_s | cosmo | 509 | 509 | **0** | ← |
| m_u | quark | 3 | 3 | **0** | ← |
| m_s | quark | 19 | 19 | **0** | ← |
| m_d | quark | 67 | 67 | **0** | ← |
| m_c | quark | 127 | 127 | **0** | ← |
| m_b | quark | 19 | 19 | **0** | ← |
| m_Z | bosón EW | 109 | 109 | **0** | ← |
| m_H | bosón EW | 61 | 61 | **0** | ← |
| V_us | CKM | 19 | 19 | **0** | ← |
| V_cb | CKM | 83 | 83 | **0** | ← |
| V_ub | CKM | 191 | 191 | **0** | ← |

*71 inferido de TAU_ID en corpus, no de fórmula esencial directa.

---

## Por sector

| Sector | DA promedio | DA máximo | Interpretación |
|--------|------------|-----------|----------------|
| EM running | 7870 | 7870 | Máxima acumulación de convención |
| Leptones | 1569 | 3672 | Dominado por precisión ultra-alta del muón |
| Débil | 420 | 420 | G_F acumula estructura del SM completo |
| QCD | 120 | 120 | Circularidad QCD demostrada |
| Gravedad | 114 | 114 | G_N depende de unidades y calibración |
| Quarks | 15 | 90 | Solo m_t tiene distancia significativa |
| Bosones EW | 12 | 36 | Casi sin capas extra |
| Cosmología | 0 | 0 | Sin distancia — esencia = existencia |
| CKM | 0 | 0 | Sin distancia — fórmulas ya son esenciales |

---

## Patrones principales

### 1. Catorce constantes con DA = 0

Más de la mitad del corpus tiene distancia axiomática cero. Para estas constantes la fórmula PLO es simultáneamente la más simple posible y la que describe el valor medido con precisión. No hay separación entre esencia y existencia.

Esto incluye todos los quarks ligeros, todos los parámetros CKM, toda la cosmología (incluyendo n_s con IN=509 — su esencia ya es compleja, pero no se le agregan más capas). Y los bosones Z e Higgs.

**Interpretación:** Para estas constantes el proceso de medición no ha añadido convención sobre la estructura natural. Lo que se mide es directamente lo que hay.

---

### 2. El EM running es el caso extremo (DA = 7870)

α(M_Z) tiene DA=7870 — la más alta del corpus. Su IN esencial es 127 (el primo HIER_1, referencia de primera generación), pero el valor medido requiere el primo compuesto 7997.

Esto refleja que α(M_Z) no es simplemente α medido a otra escala — es α *redefinido* dentro del esquema MS-bar, con running explícito, en un contexto donde la teoría de renormalización está completamente incrustada en el valor. La distancia de 7870 es la huella numérica de toda esa maquinaria teórica.

---

### 3. La circularidad QCD es cuantificable

```
α_s esencial  =  3π/(7×11)   →  IN = 11
α_s medido    =  0.1179       →  IN = 131
DA(α_s)  =  120
```

Los 120 puntos de distancia son exactamente las capas de convención que QCD acumula al declarar que su acoplamiento es fundamental y luego medirlo con precisión creciente dentro del mismo marco teórico. El fenómeno existe (IN=11), pero la medición lo entierra en convención (IN=131).

---

### 4. El muón es el lepton más "procesado"

DA(m_μ) = 3672 — más alta que m_τ (980) y mucho más que m_e (56).

Esto parece paradójico: el muón es más simple que el tau. Pero la distancia no mide complejidad del fenómeno sino acumulación de capas de medición. El experimento g-2 del muón (BNL/Fermilab) ha impulsado la precisión de m_μ durante décadas, añadiendo correcciones QED a cinco loops, contribuciones hadrónicas, efectos electrodébiles — cada capa añade primos al valor medido.

La masa del muón es la constante más "trabajada" del corpus en términos de esfuerzo metrológico acumulado. DA es una medida de ese esfuerzo.

---

### 5. Cosmología: DA = 0 en todos los casos

Sin excepción — ni siquiera n_s (que tiene IN=509) acumula distancia axiomática. Las fórmulas PLO de las constantes cosmológicas ya son sus expresiones más simples.

Esto es coherente con el carácter de la cosmología: los parámetros como Ω_m, H₀, n_s se extraen directamente de los datos observacionales con relativamente pocas capas de teoría intermedia. Lo que se mide es lo que hay, sin el procesamiento adicional que caracteriza a las constantes de física de partículas.

---

### 6. Quarks ligeros vs quark top

Cinco quarks tienen DA=0. El quark top tiene DA=90.

El top se descubrió dentro del Tevatron en 1995, extrayendo su masa de eventos de decaimiento con el SM completamente establecido. Como el tau, "nació dentro de una teoría". Los quarks ligeros tienen masas que en su mayor parte se extraen de espectroscopía hadrónica con métodos más directos.

---

## La DA como herramienta diagnóstica

**Pregunta:** ¿Qué tan "limpio" es este valor medido?
→ DA=0: lo que se mide es directamente la estructura.
→ DA alto: el valor está envuelto en muchas capas de teoría.

**Pregunta:** ¿Dónde están las mayores oportunidades de simplificación?
→ Las constantes con DA alto son candidatas a tener fórmulas esenciales más simples aún no encontradas.
→ Prioridad: m_μ (DA=3672), G_F (DA=420), α (DA=384).

**Pregunta:** ¿Dos constantes del mismo fenómeno son comparables?
→ Solo si tienen DA similar. Comparar α(M_Z) con α es comparar dos objetos con DA muy distinto — no son el mismo tipo de descripción.

**Pregunta:** ¿Una tensión experimental es tensión en la naturaleza o en la convención?
→ Si las constantes en tensión tienen DA alto, la tensión puede ser un artefacto de las capas de convención, no del fenómeno.
→ H₀: DA=0 en ambas expresiones (local y CMB). La tensión es real — no es un artefacto de convención acumulada.

---

## Nota metodológica

La DA depende de que exista una fórmula esencial identificada en PLO. Para constantes donde PLO solo tiene la fórmula del valor medido (como m_τ sin fórmula esencial directa), la DA calculada es un límite superior — la distancia real puede ser menor si existe una fórmula esencial más simple aún no encontrada.

Las constantes con DA=0 son las más robustas: no dependen de identificar una fórmula esencial separada.

---

*ArXe / PLO Research — Febrero 2026*
