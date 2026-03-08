# Mapeo Primo → Familia Axiomática
## Análisis bottom-up del corpus PLO

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## El método

Cada constante en el corpus PLO tiene una factorización en primos. Si un primo aparece
en múltiples constantes de sectores distintos, esa co-presencia no es accidental:
señala que todas esas constantes comparten una **elección axiomática común**.

Construimos el índice invertido: primo → constantes que lo contienen.
Luego preguntamos: ¿qué decisión física une este grupo?

---

## La jerarquía emergente

### Capa 1 — Axiomas ontológicos fundamentales (primos 2, 3, 5, 7)

Aparecen en casi todas las constantes. Son las condiciones de posibilidad de toda física.

| Primo | Axioma | Contenido |
|-------|--------|-----------|
| 2 | **DIFERENCIACIÓN** | Que existe distinción — que hay al menos dos estados posibles |
| 3 | **CICLICIDAD** | Que existe proceso irreversible / que el tiempo tiene dirección |
| 5 | **MEMORIA** | Que existe estado persistente / que hay almacenamiento de información |
| 7 | **ESPACIALIDAD** | Que el espacio tiene exactamente 3 dimensiones |

El primo 7 es el más interesante de esta capa. Aparece en Ω_m, V_ud, V_us, α, α_s, m_W, m_d, m_e — constantes de sectores completamente distintos. Lo que las une: todas describen fenómenos que *existen en espacio tridimensional*. El axioma es la elección de que el espacio tiene 3 dimensiones, no 2 ni 4.

---

### Capa 2 — Axiomas de estructura de campos (primos 11, 13, 17, 19)

Aparecen en subconjuntos del corpus. Son las elecciones que determinan qué fuerzas existen.

| Primo | Axioma | Constantes que lo comparten |
|-------|--------|----------------------------|
| 11 | **CAMPO EM**: existe U(1) con acoplamiento universal | α, α_s_ess, G_F, m_b, m_t, sin²θ_W, θ₁₂, n_s |
| 13 | **ISOSPÍN SU(2)**: existe la fuerza débil | α, V_ud, S8_cmb |
| 17 | **MASA / YUKAWA**: existe acoplamiento de Higgs | α, m_e, m_t, G_N, V_us |
| 19 | **GENERACIONES**: existen múltiples familias de fermiones | m_μ, m_s, m_b, m_W, V_us, θ₁₂, Ω_b, n_s |

**Observación sobre el primo 19:** agrupa exactamente las constantes que involucran
segunda generación o que dependen de que haya más de una generación. m_μ es el segundo
lepton. m_s es el segundo quark tipo-down. θ₁₂ es la mezcla primera-segunda generación.
El axioma es la elección de que la naturaleza *repite* las familias de fermiones.

**Observación sobre el primo 17:** une m_e, m_t y G_N — el electrón, el quark más
pesado, y la gravedad. Lo que tienen en común: todos involucran masa generada por
acoplamiento con el campo de Higgs (en el caso de G_N, la conexión es con la escala
de Planck / estructura del vacío). El axioma es la elección de que existe mecanismo
de generación de masa.

---

### Capa 3 — Axiomas de ruptura de simetría y estructura EW (primos 41, 71, 107, 109)

Aparecen en grupos pequeños. Son elecciones más específicas.

| Primo | Axioma | Constantes |
|-------|--------|-----------|
| 41 | **VEV**: el vacío EW tiene valor v = 246 GeV | m_H, m_W, θ₂₃ |
| 71 | **TAU_ID**: existe tercera generación leptónica | m_τ, G_F |
| 107 | **TOP_ID**: existe tercera generación de quarks | m_t, V_ud |
| 109 | **ESQUEMA M_Z**: μ = M_Z como escala de referencia EW | m_Z, G_F |

**El primo 41** une el Higgs y el W — los dos objetos directamente determinados
por el VEV del campo de Higgs. Y también θ₂₃, la mezcla más grande de la matriz
CKM, que depende de la jerarquía de masas que el Higgs genera. El axioma es la
elección del valor específico del VEV.

**El primo 109** es particularmente limpio: m_Z y G_F son exactamente las dos
constantes que se usan como input del esquema de renormalización electrodébil
centrado en el polo del Z. El axioma es la elección de μ = M_Z como escala de
referencia — una elección puramente convencional pero universalmente adoptada.

---

### Capa 4 — Axiomas de precisión y convención acumulada (primos 131, 137, 1051)

Aparecen donde la teoría se pliega sobre sí misma.

| Primo | Axioma | Constantes |
|-------|--------|-----------|
| 131 | **N²LO**: incluir correcciones perturbativas de segundo orden | G_N, α_s_med |
| 137 | **REFERENCIA α(0)**: usar α a baja energía como constante base | α, G_F |
| 1051 | **MEZCLA COMPLETA**: sin²θ_W con correcciones de tres generaciones | m_τ, sin²θ_W |

---

## La estructura completa

Lo que emerge no es una lista arbitraria sino una **jerarquía de decisiones**,
donde cada capa presupone las anteriores:

```
CAPA 1 — Condiciones de posibilidad
  Primo 2: que hay distinción
  Primo 3: que hay proceso irreversible
  Primo 5: que hay estado persistente
  Primo 7: que el espacio es 3D
  
       ↓ dados estos axiomas, se puede elegir:
  
CAPA 2 — Estructura de fuerzas
  Primo 11: que existe U(1) / electromagnetismo
  Primo 13: que existe SU(2) / fuerza débil
  Primo 17: que existe mecanismo de masa (Yukawa)
  Primo 19: que existen múltiples generaciones
  
       ↓ dados estos axiomas, se puede elegir:
  
CAPA 3 — Valores específicos de la ruptura
  Primo 41: que el VEV es 246 GeV
  Primo 71: que existe el tau (3ª generación leptónica)
  Primo 107: que existe el top (3ª generación de quarks)
  Primo 109: que μ = M_Z es la escala de referencia
  
       ↓ dados estos axiomas, se puede elegir:
  
CAPA 4 — Convenciones de precisión
  Primo 131: que se incluyen correcciones N²LO
  Primo 137: que α(0) es la constante de referencia EM
  Primo 1051: que el ángulo de Weinberg incorpora 3 generaciones
```

Cada primo es el tamaño del espacio lógico de la decisión correspondiente.
Un primo más grande no significa una elección más importante —
significa una elección que presupone más capas previas ya fijadas.

---

## Lo que esto implica para el IN

El Índice de Naturalidad (IN = primo máximo en la factorización) ahora tiene una
lectura axiomática precisa:

> **IN = la elección axiomática más profunda (más capas presupuestas) que fue
> necesaria para que esta constante tenga el valor que tiene.**

Una constante con IN=7 (como Ω_m) solo requiere la elección de espacialidad 3D.
Una constante con IN=109 (como m_Z) requiere: diferenciación + ciclicidad +
memoria + espacialidad + U(1) + SU(2) + masa + generaciones + VEV + esquema M_Z.
Son diez elecciones axiomáticas apiladas.

El IN no cuenta el número de elecciones — captura la *profundidad* de la última.

---

## Verificación: α como caso de prueba

α tiene los primos: 3, 7, 11, 13, 17, 137, 421, 521.

Leyendo axiomáticamente:
- 3: existe proceso irreversible (el fotón viaja)
- 7: el espacio es 3D (el fotón se propaga en 3D)
- 11: existe campo U(1) (el fotón es el bosón de U(1))
- 13: existe SU(2) (α contiene correcciones EW que involucran SU(2))
- 17: existe mecanismo de masa (correcciones radiativas del Higgs)
- 137: α(0) es la referencia EM (auto-referencia: α se define a sí misma)
- 421, 521: correcciones de precisión QED y EW de órdenes superiores

La factorización de α es la historia completa de las elecciones axiomáticas
necesarias para que el acoplamiento electromagnético tenga el valor que tiene.
Cada primo es una capa de esa historia.

---

## Predicción abierta

Si la jerarquía axiomática es correcta, debería ser posible:

1. Dada una constante desconocida, predecir qué primos debería contener
   según qué sector físico pertenece y qué axiomas presupone.

2. Dada una fórmula PLO con un primo inesperado, identificar qué elección
   axiomática no estaba siendo contabilizada.

3. Identificar constantes "mal ubicadas" — que contienen primos de una capa
   que no deberían necesitar, señalando que su valor actual incorpora
   decisiones axiomáticas que el fenómeno en sí no requiere.

---

*ArXe / PLO Research — Febrero 2026*
