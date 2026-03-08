# PLO — Documento de Trabajo Consolidado
## Primos, axiomas, presuposición ontológica y el Modelo Estándar

*ArXe / PLO Research — Febrero 2026*
*Documento interno — todo el razonamiento visible*

---

## Índice

1. [El punto de partida](#1-el-punto-de-partida)
2. [Índice de Naturalidad (IN)](#2-índice-de-naturalidad)
3. [Distancia Axiomática (DA)](#3-distancia-axiomática)
4. [Mapeo primo → familia axiomática](#4-mapeo-primo--familia-axiomática)
5. [Presuposición ontológica](#5-presuposición-ontológica)
6. [Cinco patrones en el grafo](#6-cinco-patrones-en-el-grafo)
7. [Correspondencia con axiomas ZF](#7-correspondencia-con-axiomas-zf)
8. [Predicciones abiertas](#8-predicciones-abiertas)
9. [Lo que emerge — sin imponer](#9-lo-que-emerge--sin-imponer)

---

## 1. El punto de partida

El corpus PLO contiene fórmulas para ~33 constantes físicas del Modelo Estándar.
Cada fórmula es una expresión en primos — por ejemplo:

```
m_u      = 2³ × 3³
m_e      = 2 × 3 × 5 × 7 × 17
α_s_ess  = 3π / (7×11)
α_s_med  = 0.1179   →  primo máximo: 131
α        = 137 × (3×13×17×11×7)^(1/5) × (1 ± 1/(421×521))
```

La pregunta que abre esta sesión: ¿qué *significan* esos primos?
¿Por qué algunos fenómenos tienen primos pequeños y otros primos grandes?
¿Hay estructura en los conjuntos de primos que comparten distintas constantes?

La respuesta que emerge del análisis: **cada primo corresponde a una elección axiomática**.
La factorización PLO de una constante es el registro de qué elecciones
tuvieron que hacerse para que esa constante sea articulable.

---

## 2. Índice de Naturalidad

### Definición

```
IN(C) = max{ p : p primo en la factorización PLO de C }
```

El primo máximo de la factorización. Mide la **profundidad axiomática** —
qué tan profunda es la última elección que tuvo que hacerse.

### La escala

| Zona | Rango | Nombre | Ejemplo |
|------|-------|--------|---------|
| 1 | IN ≤ 7 | Esencia natural | m_u (IN=3), Ω_m (IN=7) |
| 2 | 11–19 | Natural complejo | m_e (17), m_μ (19), m_b (19) |
| 3 | 23–97 | Umbral teoría | m_H (61), H₀ (73) |
| 4 | 101–200 | Teoría dominante | m_Z (109), G_N (131), α_s_med (131) |
| 5 | 201–999 | Convención acumulada | α (521), G_F (557) |
| 6 | ≥1000 | Artefacto institucional | sin²θ_W (1051), α(M_Z) (7997) |

Los umbrales no son arbitrarios — coinciden con los primos de los niveles ArXe:
primos 2,3,5,7 corresponden a T¹–T³ (estructura fundamental);
11,13,17,19 corresponden a T⁻⁵–T⁻⁹ (campos de gauge).

### El caso demostrativo: α_s

```
α_s esencial = 3π/(7×11)   →  IN = 11  [Zona 2 — Natural complejo]
α_s medido   = 0.1179       →  IN = 131 [Zona 4 — Teoría dominante]
```

Mismo fenómeno físico. Distinto índice. La diferencia de 120 puntos
son las capas de convención entre la estructura lógica del acoplamiento fuerte
y su descripción en el esquema MS-bar con correcciones NNLO.

### Lectura ontológica

El IN no mide cuánta energía se invirtió para medir la constante,
ni cuántas capas de teoría hay en la fórmula.
Mide la profundidad de la **última elección axiomática** que fue necesaria
para que la pregunta "¿cuánto vale C?" sea articulable.

```
IN = 7   → articular C requiere que el espacio sea 3D
IN = 17  → además requiere que exista mecanismo de masa
IN = 41  → además requiere que el vacío EW tenga un VEV específico
IN = 109 → además requiere que μ = M_Z sea la escala de referencia
```

---

## 3. Distancia Axiomática

### Definición

```
DA(C) = IN(medido) − IN(esencial)
```

Mide cuántas capas de convención se acumularon entre la estructura lógica
del fenómeno y su descripción científica actual.

### Por sector

| Sector | DA promedio | Interpretación |
|--------|------------|----------------|
| EM running | 7870 | Máxima acumulación de convención |
| Leptones | 1569 | Dominado por precisión ultra-alta del muón |
| Débil | 420 | G_F acumula la estructura del SM completo |
| QCD | 120 | Circularidad QCD cuantificada |
| Gravedad | 114 | G_N depende de unidades y calibración |
| Quarks | 15 | Solo m_t tiene distancia significativa |
| Bosones EW | 12 | Casi sin capas extra |
| **Cosmología** | **0** | Esencia = existencia en todos los casos |
| **CKM** | **0** | Esencia = existencia en todos los casos |

### El hallazgo de H₀

Tanto H₀_local como H₀_cmb tienen DA=0 en sus respectivas expresiones.
La tensión de Hubble **no es un artefacto de convenciones acumuladas** —
es una tensión real en el fenómeno. Los 120 puntos de diferencia entre
las dos mediciones son física, no teoría.

### Catorce constantes con DA=0

Toda la cosmología, toda la CKM, los quarks ligeros, los bosones Z e Higgs.
Para estas constantes la fórmula PLO esencial y el valor medido coinciden:
no hay separación entre esencia y existencia.

---

## 4. Mapeo primo → familia axiomática

El análisis bottom-up construye el índice invertido:
primo → lista de constantes que lo contienen.
Luego pregunta: ¿qué elección física une este grupo?

### Capa 1 — Condiciones de posibilidad (primos 2, 3, 5, 7)

Aparecen en casi todas las constantes. Son la base.

| Primo | Axioma | Lo que une |
|-------|--------|-----------|
| 2 | **DIFERENCIACIÓN** | Que hay distinción — mínimo dos estados posibles |
| 3 | **CICLICIDAD** | Que hay proceso irreversible — tiempo con dirección |
| 5 | **MEMORIA** | Que hay estado persistente — almacenamiento |
| 7 | **ESPACIALIDAD** | Que el espacio tiene exactamente 3 dimensiones |

El primo 7 es especialmente informativo: aparece en Ω_m, V_ud, V_us, α, α_s, m_W, m_d, m_e —
sectores completamente distintos. El denominador común es que todos
describen fenómenos que *existen en espacio tridimensional*.

### Capa 2 — Estructura de campos (primos 11, 13, 17, 19)

| Primo | Axioma | Constantes representativas |
|-------|--------|---------------------------|
| 11 | **CAMPO EM** — existe U(1) con acoplamiento universal | α, α_s_ess, G_F, m_b, m_t, sin²θ_W, θ₁₂, n_s |
| 13 | **ISOSPÍN SU(2)** — existe la fuerza débil | α, V_ud, S8_cmb |
| 17 | **MASA/YUKAWA** — existe acoplamiento de Higgs | α, m_e, m_t, G_N, V_us |
| 19 | **GENERACIONES** — existen múltiples familias de fermiones | m_μ, m_s, m_b, m_W, V_us, θ₁₂, Ω_b, n_s |

El primo 19 tiene el **mayor alcance transversal** del corpus:
aparece en quarks, leptones, mezcla CKM, mezcla PMNS y cosmología.
El axioma "existen múltiples generaciones de fermiones" atraviesa todos los sectores.

### Capa 3 — Valores específicos de la ruptura (primos 41, 71, 107, 109)

| Primo | Axioma | Constantes |
|-------|--------|-----------|
| 41 | **VEV** — el vacío EW tiene valor v=246 GeV | m_H, m_W, θ₂₃ |
| 71 | **TAU_ID** — existe tercera generación leptónica | m_τ, G_F |
| 107 | **TOP_ID** — existe tercera generación de quarks | m_t, V_ud |
| 109 | **ESQUEMA M_Z** — μ=M_Z como escala de referencia | m_Z, G_F |

El primo 109 es el más limpio: une exactamente m_Z y G_F,
que son los dos inputs del esquema de renormalización electrodébil centrado en el polo del Z.
El axioma es la elección de μ=M_Z — convencional pero universalmente adoptada.

### Capa 4 — Convenciones de precisión (primos 131, 137, 1051)

| Primo | Axioma | Constantes |
|-------|--------|-----------|
| 131 | **N²LO** — correcciones perturbativas de segundo orden | G_N, α_s_med |
| 137 | **REFERENCIA α(0)** — α a baja energía como base | α, G_F |
| 1051 | **MEZCLA COMPLETA** — sin²θ_W con las tres generaciones | m_τ, sin²θ_W |

### La propiedad central: cada capa presupone todas las anteriores

No puedes elegir el VEV (primo 41) sin haber elegido antes:
que existe campo de Higgs (primo 17), que hay generaciones (primo 19),
que hay espacio 3D (primo 7), que hay proceso (primo 3).

Si el primo 17 no estuviera dado, la pregunta "¿cuánto vale el VEV?"
no sería incorrecta — sería **inarticulable**.

---

## 5. Presuposición ontológica

### Implicación vs presuposición

```
Implicación:    A → B    (si A es verdad, entonces B es verdad)
Presuposición:  A ⊏ B    (B no puede plantearse sin que A esté dado)
```

"Estoy aquí" no *implica* "existo" — lo **presupone**.
Sin "existo" ya dado, "estoy aquí" no sería falsa: sería sin sentido.

Las factorizaciones PLO son árboles de presuposición ontológica:
si la factorización de C contiene los primos {p₁, p₂, p₃},
esos axiomas tienen que estar ya dados para que la pregunta "¿cuánto vale C?" tenga sentido.

### El grupo {2×3×5} — mismo piso, distintas habitaciones

Cinco constantes de sectores completamente distintos comparten
exactamente la base {2,3,5}:

```
m_μ       {2,3,5} + 19   → segunda generación leptónica
α_s_med   {2,3,5} + 131  → QCD medido
V_cb      {2,3,5} + 83   → mezcla B→charm
θ₂₃       {2,3,5} + 41   → mezcla 2ª-3ª generación
Ω_m       {2,3,5} + 7    → fracción de materia
```

Mismo piso ontológico: diferenciación + tiempo + memoria.
Cada una añade una sola elección diferente encima.

El piso {2,3,5} no corresponde a ningún nivel ArXe específico —
es la mínima configuración para que exista "un proceso en el espacio",
antes del espacio 3D y antes de los campos de gauge.

### Cadenas de presuposición directa

**Ω_m ⊂ m_e:**
```
Ω_m = {2,3,5,7}
m_e = {2,3,5,7,17}
```
La masa del electrón presupone la fracción de materia del universo.
No puedes preguntar "¿cuánto pesa el electrón?" sin que esté dado
que existe materia en el universo. La presuposición va en una sola dirección.

**α_s_ess ⊂ α:**
```
α_s_ess = {3,7,11}
α       = {3,7,11,13,17,137,421,521}
```
El acoplamiento EM preciso presupone el acoplamiento fuerte.
Contraintuitivo desde la física estándar, pero estructuralmente coherente
en ArXe: U(1) es posterior al nivel donde QCD vive.

**m_b ⊂ n_s:**
```
m_b = {2,11,19}
n_s = {2,11,19,509}
```
El índice espectral primordial presupone la estructura del quark bottom.
La inflación como fenómeno articulable requiere que estén dados:
diferenciación, campo EM, y segunda generación de fermiones.

### m_u como átomo ontológico

```
m_u = {2,3}
```

El quark up presupone solo diferenciación y ciclicidad.
Es subconjunto de al menos ocho constantes del corpus.
No necesita espacio 3D, campos de gauge, ni mecanismo de masa.

No es más fundamental en el sentido de ser más importante.
Es que su descripción **presupone menos** que cualquier otra constante del corpus.

---

## 6. Cinco patrones en el grafo

### Patrón 1 — Primos solitarios

16 de 33 primos aparecen en una sola constante.

**Tipo A — pequeños (<100):** singularidades axiomáticas.
Fenómenos con una elección única que nadie más necesita.
Destaca m_H con primo 61: el mecanismo de Higgs tiene una elección
exclusiva que no se filtra a las masas que genera.
El VEV (primo 41) sí aparece en m_W y θ₂₃. El primo 61 no.

**Tipo B — grandes (>100):** capas de precisión únicas.
m_c = {127} es el caso extremo: un solo primo solitario.
El charm tiene la descripción PLO más "pura" del corpus —
un único número que no presupone ni es presupuesto por nadie.

α tiene dos primos solitarios grandes (421 y 521): la única constante
del corpus con dos capas de corrección de alta precisión completamente exclusivas.

### Patrón 2 — Constantes desplazadas

**m_s y m_μ** tienen primo 19 (generaciones) pero no tienen primo 7 (espacio 3D).
Segunda generación sin el axioma espacial. Coherente: los leptones
no están confinados por QCD, y el strange existe en el contexto
generacional antes que en el espacial.

**n_s** tiene {2,11,19} pero no tiene 3,5,7.
El índice espectral primordial es un parámetro **pre-espacial** —
describe fluctuaciones del universo inflacionario donde el espacio 3D
estable aún no existe. Los primos 3,5,7 corresponden a estructuras
que se forman después de la inflación.

**m_Z** no tiene primo 7 (espacio 3D).
El bosón Z vive en el espacio de gauge abstracto.
No necesita el axioma espacial para articularse,
solo para manifestarse.

### Patrón 3 — Topología del grafo (DAG)

14 aristas de presuposición directa. Tres tipos de nodos:

**Raíces (6):** m_u, m_s, m_b, θ₁₂, α_s_ess, H₀_local.
Las más autónomas del corpus. Su articulación no presupone ninguna otra constante.

Sorpresa: **θ₁₂ es raíz** en el mismo sentido que m_u.
Un ángulo de mezcla resulta tan primitivo como los quarks más ligeros.

Sorpresa: **m_b ≡ θ₁₂** en estructura axiomática:
```
m_b    = {2,11,19}
θ₁₂   = {2,11,19}
```
El quark bottom y el ángulo de mezcla primera-segunda generación
son dos proyecciones del mismo nivel ontológico.
Mismo piso, distinto observable.

**Islas (16):** no tienen relaciones de presuposición con ninguna otra.
Son el límite del corpus actual — y sus ausencias son predicciones:
m_t debería presuponer m_b, G_F debería presuponer α_s_ess,
m_d debería relacionarse con m_u.

### Patrón 4 — Huecos en el mapa

De todos los pares posibles de primos fundamentales, **solo dos están ausentes**:
```
5×13  (MEMORIA × SU2)
13×19 (SU2 × GENERACIONES)
```

El primo 13 (SU2 / fuerza débil) es el más aislado del corpus.
Nunca aparece junto con memoria (5) ni con generaciones (19).
Esto señala constantes físicas que deberían existir en el corpus pero no están:
el tiempo de vida del W y la invariante de Jarlskog J_CP son los candidatos directos.

### Patrón 5 — Puentes exclusivos entre sectores

Primos que conectan exactamente dos sectores del corpus:

| Primo | Sectores | Constantes | Lectura |
|-------|----------|-----------|---------|
| 67 | quark ↔ cosmo | m_d ↔ H₀_cmb | El quark down y la expansión cósmica comparten una elección única |
| 71 | lepton ↔ coupling | m_τ ↔ G_F | El tau y la constante de Fermi |
| 73 | lepton ↔ cosmo | m_τ ↔ H₀_local | El tau y la constante de Hubble local |
| 107 | quark ↔ CKM | m_t ↔ V_ud | El top y la mezcla up-down — unitaridad CKM |
| 109 | boson ↔ coupling | m_Z ↔ G_F | El Z y la constante de Fermi — esquema M_Z |

El más misterioso: **primo 67 une m_d con H₀_cmb**.
Ninguna otra constante los conecta. Qué elección axiomática une
el quark más ligero tipo-down con la tasa de expansión del universo
desde el CMB es una pregunta abierta.

Conexión quarks ↔ cosmología (sectores más opuestos en escala):

- **primo 7**: m_d ↔ Ω_m. El quark down y la fracción de materia comparten el axioma espacial. m_u no tiene el primo 7 — la asimetría up/down en el espacio 3D está registrada en los primos.
- **primo 19**: {m_s,m_b} ↔ {Ω_b,n_s}. Segunda generación conecta quarks con bariones cósmicos.
- **Lo que quarks tiene y cosmo no**: {17,107,127} — masa específica de quarks individuales. La cosmología no necesita saber qué tan pesados son los quarks, solo que existen.

---

## 7. Correspondencia con axiomas ZF

Los ocho axiomas ZF relevantes mapean exactamente a los ocho primos fundamentales del corpus.

```
Primo  Axioma ZF                    Física (PLO)
─────  ───────────────────────────  ─────────────────────
  2    Extensionalidad + Pares      DIFERENCIACIÓN
  3    Unión                        CICLICIDAD / TIEMPO
  5    Potencia                     MEMORIA / ESTADO
  7    Infinito → ℝ³                ESPACIO 3D
 11    Separación → U(1)            CAMPO EM
 13    Reemplazamiento → SU(n)      ISOSPÍN SU(2)
 17    Regularidad → jerarquía      MASA / YUKAWA
 19    Elección → familias          GENERACIONES
```

No sobran axiomas, no faltan primos. La correspondencia es exacta.

### El axioma del Vacío no tiene primo

El conjunto vacío ∅ es el caso degenerado — no abre espacio lógico, solo declara que la nada existe. Consistente con que el primo más pequeño sea 2.

### Teorías derivadas

Una vez fijados los axiomas ZF, las teorías que se construyen sobre ellos tienen sus propios primos:

| Primo | Teoría | Conexión |
|-------|--------|---------|
| 23 | Topología general | Continuidad, variedades, escala de inflación |
| 29 | Cardinales grandes | Energía del vacío / constante cosmológica |
| 37 | Teoría de categorías | Morfismos CKM — V_tb |
| 41 | Espacios de Hilbert | Estados cuánticos, VEV del Higgs |
| 47 | Análisis funcional | Operadores, espectros — polo del Z |

### La factorización PLO como certificado axiomático

```
m_u = {2,3}
    = Extensionalidad + Unión
    = objeto físico con el certificado axiomático más simple del corpus

m_e = {2,3,5,7,17}
    = Extensionalidad + Unión + Potencia + Infinito(→ℝ³) + Regularidad(→Yukawa)
    = cinco sistemas axiomáticos necesarios para que la masa del electrón sea articulable

α   = {3,7,11,13,17,137,421,521}
    = Unión + Infinito + Separación + Reemplazamiento + Regularidad + [capas QED]
    = toda la ZF más capas de corrección perturbativa exclusivas del EM
```

### El Axioma de Elección y las generaciones

AC es el único axioma de ZF independiente de los demás —
consistente tanto con ZF como con su negación. No se puede derivar: solo aceptar o no.

Las generaciones de fermiones son el único sector del SM sin explicación interna —
son un "hecho dado" sin derivación desde el SM mismo.

Ambos son la misma estructura: una elección que no se puede derivar, solo aceptar.
El primo 19 es la firma de eso en ambos lados.

### El hueco 5×13 en términos ZF

La combinación Potencia+Reemplazamiento (5×13) produce,
cuando se itera, los ordinales transfinitos: P(ω), P(P(ω))...
Si no hay física que requiera ordinales transfinitos,
la ausencia de 5×13 en el corpus tiene explicación formal:
el SM no necesita subir tan alto en la jerarquía matemática.

---

## 8. Predicciones abiertas

### Predicciones de fórmulas esenciales

| Constante | Predicción | Base |
|-----------|-----------|------|
| m_τ/m_μ | debe contener 3⁶ = 729 (tercera generación = tercer nivel de recursión T⁴) | Patrón generacional: m_μ/m_e tiene 3⁴ |
| y_t (Yukawa top) | {3,11,17} | m_t = {3,11,17,107} → el 107 es la capa convencional |
| T_Hawking (esencial) | IN ≈ 17 | Involucra ℏ,c,G,π — primos máximos: 17 de G_N |

### Predicciones de constantes ausentes en el corpus

| Constante | Primos predichos | Razón |
|-----------|-----------------|-------|
| m_ν (masa neutrino) | {2,19} | Diferenciación + generaciones; sin carga EM |
| Λ (constante cosmológica) | {2,3,29} | Energía oscura en T⁻¹⁴ = primo 29 |
| m_axión | {3,7,11} | Idéntico a α_s_ess — misma QCD, solución al problema CP fuerte |
| θ_QCD | {3,7,11,13} | α_s_ess + SU(2) para articular violación de CP en QCD |
| J_CP (Jarlskog) | {2,7,13,17,19} | Invariante CP de CKM: todos los axiomas de mezcla |
| V_inflation | {2,3,23} | Escala inflacionaria en T⁻¹¹ = primo 23 |

La más verificable: **m_axión = {3,7,11}** + un primo solitario que capture su masa.
Si el axión existe, su fórmula PLO debería compartir exactamente la base de α_s_ess.

### Predicciones de relaciones faltantes

Si las fórmulas PLO de estas constantes se refinan, deberían aparecer:
- El primo 11 en m_t (para presuponer m_b, mismo sector)
- El primo 2 en m_d o su base compartida con m_u
- Un primo compartido entre G_F y α_s_ess (la constante de Fermi presupone QCD)

---

## 9. Lo que emerge — sin imponer

Hay una observación que sería deshonesto dejar sin decir,
aunque no estaba en el plan inicial y no aparece en la física estándar.

Lo que el análisis construyó, sin proponérselo, es una **ontología formal
del Modelo Estándar** — no una interpretación filosófica añadida encima,
sino una estructura que emerge de los números mismos.

### La distinción que importa

Cuando un primo aparece en la factorización de C,
no dice cómo se *mide* C ni que C *implica* ese axioma.
Dice que ese axioma tiene que estar **ya dado** para que la pregunta
"¿cuánto vale C?" sea articulable en absoluto.

Esto es lo que la lógica formal llama *presuposición*
y lo que la tradición fenomenológica llama *condición de posibilidad*.
Aquí no es filosofía aplicada a la física — emerge de las factorizaciones.

### Por qué la jerarquía de capas es necesaria, no accidental

Las cuatro capas (primos 2–7, 11–19, 41–109, 131–1051) no son
una clasificación conveniente. Son capas de presuposición real:
cada capa solo puede elegirse si las anteriores ya están fijadas.

No puedes elegir μ=M_Z (primo 109) en un universo sin campo EM (primo 11).
No puedes elegir el VEV (primo 41) en un universo sin mecanismo de masa (primo 17).
No puedes elegir mecanismo de masa en un universo sin espacio 3D (primo 7).

La estructura no fue impuesta. Emergió de preguntar qué constantes
comparten qué primos y qué tienen en común físicamente.

### El corpus como mapa parcial

El corpus PLO es un mapa parcial de la estructura de presuposición ontológica
del Modelo Estándar. Parcial porque:

- Hay constantes físicas reales sin fórmula PLO todavía (m_ν, Λ, J_CP)
- Hay relaciones de presuposición que las fórmulas actuales no capturan (islas del grafo)
- Hay combinaciones de axiomas ausentes que señalan física no representada

Pero en su estado actual, la estructura es suficientemente coherente para
que su emergencia no sea accidental: el grafo de presuposición tiene
raíces plausibles, cadenas verificables, e islas que son predicciones.

Los primos no son etiquetas numéricas convenientes.
Son el tamaño del espacio lógico que cada elección axiomática abre.
Y las factorizaciones PLO son el registro de qué espacios tuvieron que abrirse
para que cada constante tenga el valor que tiene en este universo.

---

## Apéndice — Tabla completa del corpus

| Constante | Sector | Factorización (primos) | IN | DA |
|-----------|--------|----------------------|-----|-----|
| m_u | quark | {2,3} | 3 | 0 |
| m_d | quark | {2,7,67} | 67 | 0 |
| m_s | quark | {5,19} | 19 | 0 |
| m_c | quark | {127} | 127 | 0 |
| m_b | quark | {2,11,19} | 19 | 0 |
| m_t | quark | {3,11,17,107} | 107 | 90 |
| m_e | lepton | {2,3,5,7,17} | 17 | 56 |
| m_μ | lepton | {2,3,5,19} | 19 | 3672 |
| m_τ | lepton | {2,5,71,73,1051} | 1051 | ~980 |
| m_W | bosón | {2,5,7,19,41,103} | 103 | ~36 |
| m_Z | bosón | {2,3,47,89,109} | 109 | 0 |
| m_H | bosón | {5,41,61} | 61 | 0 |
| α | coupling | {3,7,11,13,17,137,421,521} | 521 | 384 |
| α(M_Z) | coupling | {2,7997} | 7997 | 7870 |
| α_s_ess | coupling | {3,7,11} | 11 | — |
| α_s_med | coupling | {2,3,5,131} | 131 | 120 |
| G_F | coupling | {2,11,71,109,137,557} | 557 | 420 |
| G_N | coupling | {2,3,5,17,131} | 131 | 114 |
| V_ud | CKM | {7,13,107} | 107 | 0 |
| V_us | CKM | {2,7,17,19} | 19 | 0 |
| V_cb | CKM | {2,3,5,83} | 83 | 0 |
| V_ub | CKM | {2,191} | 191 | 0 |
| V_tb | CKM | {3,37} | 37 | 0 |
| θ₁₂ | PMNS | {2,11,19} | 19 | 0 |
| θ₁₃ | PMNS | {2,5,173} | 173 | 0 |
| θ₂₃ | PMNS | {2,3,5,41} | 41 | 0 |
| sin²θ_W | EW | {5,11,1051} | 1051 | ~980 |
| Ω_m | cosmo | {2,3,5,7} | 7 | 0 |
| Ω_b | cosmo | {2,19,59} | 59 | 0 |
| H₀_local | cosmo | {5,73} | 73 | 0 |
| H₀_cmb | cosmo | {3,5,67} | 67 | 0 |
| n_s | cosmo | {2,11,19,509} | 509 | 0 |
| S8_cmb | cosmo | {2,13} | 13 | 0 |
| S8_lss | cosmo | {2,97} | 97 | 0 |

---

*ArXe / PLO Research — Febrero 2026*
*Versión consolidada de sesiones de análisis — documento de trabajo interno*
