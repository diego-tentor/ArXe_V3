# IN vs Energía de Producción y Capas Teóricas
## Verificación de correlación — Corpus PLO

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## La hipótesis

Si los primos altos marcan complejidad lógica acumulada, y los experimentos de alta energía son los más complejos tecnológicamente, debería existir correlación entre el Índice de Naturalidad (IN) y la energía invertida en medir la constante.

---

## Resultado: correlación real pero no donde se esperaba

### Correlación con energía de producción: r = 0.57

Al correlacionar IN con el logaritmo de la energía de producción del experimento que estableció cada constante (solo sector de física de partículas, n=17):

```
r(IN, log₁₀ E_producción) = 0.57    moderada
```

Hay señal, pero no es fuerte. Y los casos anómalos son los más informativos.

### Correlación con capas teóricas de extracción: r = 0.80

Al correlacionar IN con el número de capas teóricas necesarias para extraer el valor de los datos brutos:

```
r(IN, capas_teóricas) = 0.80    fuerte
```

| Capas | Constantes representativas | IN promedio |
|-------|---------------------------|-------------|
| 1 | m_e, m_μ (medición directa) | 18 |
| 2 | m_s, m_b, m_W, m_Z, α_s esencial | 61 |
| 3 | m_H, m_c, m_t, V_cb, α | 103 |
| 4 | V_ub, α_s medido | 161 |
| 5 | n_s (inflación + MCMC) | 509 |

**El IN no mide la energía invertida. Mide las capas teóricas necesarias para interpretar los datos.**

---

## Las anomalías son la demostración

### m_H: alta energía, IN bajo (61)

El bosón de Higgs requirió 8.000 GeV — la energía más alta jamás empleada. Su IN es 61, más bajo que G_N medido con una balanza de torsión en 1798.

La razón: la extracción de m_H es relativamente directa. Una vez que el pico aparece en los datos de ATLAS/CMS, la masa se lee del espectro con pocas capas de teoría intermedia. Alta energía para producirlo, baja complejidad para interpretarlo.

### m_c: energía moderada, IN alto (127)

El quark charm se descubrió en el J/ψ a 3.1 GeV — energía modest. Su IN es 127, más alto que m_W o m_Z descubiertos a 540 GeV.

La razón: extraer la masa del quark charm del J/ψ requiere mecánica cuántica no relativista del charmonio, QCD perturbativa, el modelo de quarks, y hoy también QCD en el retículo. Cada capa añade primos. La energía de producción es baja; la complejidad de interpretación es alta.

### m_b: alta energía, IN bajo (19)

El quark bottom se descubrió en la resonancia Υ a 9.5 GeV. Su IN es 19 — igual que m_s descubierta en física de kaones a 0.5 GeV.

La razón: la Υ es una resonancia limpia. La masa del bottom se extrae con pocas capas teóricas, a pesar de la alta energía necesaria para producirla.

---

## La distinción física que emerge

Los datos separan naturalmente dos conceptos que la física experimental suele mezclar:

**Umbral de producción** — la energía mínima para crear la partícula. Depende de la masa. Refleja el nivel ontológico del fenómeno en la jerarquía de materia.

**Complejidad de extracción** — las capas teóricas necesarias para ir de los datos brutos al valor de la constante. Depende de cómo está embebida la constante en la fenomenología. Refleja cuánta teoría media entre el dato y el número.

El IN mide principalmente la segunda. Que ambas correlacionen moderadamente (r=0.57) refleja que en general las partículas más masivas son también más difíciles de interpretar — pero hay excepciones sistemáticas en ambas direcciones.

---

## La población que rompe el esquema: sin acelerador, IN alto

Hay constantes con IN alto que no requirieron ningún acelerador:

| Constante | IN | Método | Razón del IN alto |
|-----------|-----|--------|-------------------|
| α | 137 | Espectroscopía óptica | Siglos de precisión acumulada |
| n_s | 509 | Satélite CMB | Modelo de inflación + MCMC |
| H₀ | 73 | Cepheidas / CMB | Cadena de distancias calibradas |
| m_d | 67 | Espectroscopía hadrónica | Extracción QCD indirecta |

Estas constantes confirman que el IN no es una función de la energía: es una función de la **mediación teórica**. α tiene IN=137 porque dos siglos de física de precisión han construido un edificio teórico enorme alrededor de ese número, no porque requiera un acelerador.

---

## Reformulación de la hipótesis

La hipótesis original — correlación IN ~ energía — es parcialmente correcta pero necesita precisarse:

> **El IN correlaciona con la energía de producción de manera moderada (r=0.57) porque en promedio los fenómenos de alta energía son también más difíciles de interpretar. Pero la causa directa es la complejidad teórica de extracción (r=0.80), no la energía per se.**

En términos ArXe: la energía refleja el nivel ontológico del fenómeno (qué nivel T^k lo genera). La complejidad de extracción refleja cuántas decisiones axiomáticas adicionales se toman al describir ese fenómeno desde el exterior. Son cosas distintas, aunque correlacionadas.

---

## Predicción verificable

Si la distinción es correcta, debería ser posible encontrar:

1. **Constantes de alta energía con IN bajo** — fenómenos masivos pero de extracción directa. El Higgs (m_H=61 a 8 TeV) ya es un ejemplo.

2. **Constantes de baja energía con IN alto** — fenómenos accesibles pero profundamente embebidos en teoría. α=137 y m_c=127 son ejemplos.

3. **Al factorizar la DA por capas teóricas**, la varianza residual debería ser pequeña — es decir, DA/capas debería ser aproximadamente constante. Si esto se cumple, la DA sería una medida directa del número de capas × complejidad media de cada capa.

---

*ArXe / PLO Research — Febrero 2026*
