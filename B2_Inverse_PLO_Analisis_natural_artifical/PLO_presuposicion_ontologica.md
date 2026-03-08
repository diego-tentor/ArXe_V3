# Estructura de Presuposición Ontológica en PLO
## Las factorizaciones como árboles de necesidad lógica

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## El principio

En ArXe, "estoy aquí" no *implica* "existo" como consecuencia lógica —
lo **presupone ontológicamente**. Sin "existo" ya dado, "estoy aquí"
no sería falsa: sería inarticulable. No tendría sentido como afirmación.

La diferencia con la implicación lógica es crucial:

```
Implicación:    A → B    (si A es verdad, entonces B es verdad)
Presuposición:  A ⊏ B    (B no puede ni plantearse sin A ya dado)
```

Lo que el análisis bottom-up del corpus revela es que las factorizaciones
PLO son exactamente árboles de presuposición ontológica.

Si la factorización de una constante C contiene los primos {p₁, p₂, p₃},
eso no significa que C *implica* los axiomas correspondientes.
Significa que esos axiomas tienen que estar **ya dados** para que la
pregunta "¿cuánto vale C?" tenga sentido.

---

## Evidencia: pares que difieren en un solo axioma

El corpus contiene grupos de constantes que comparten exactamente
los mismos primos excepto el máximo. Estas constantes tienen
**el mismo piso ontológico** y difieren solo en la última elección:

### El grupo {2×3×5} — cinco constantes, cinco habitaciones

```
m_μ       {2,3,5} + 19   → segunda generación leptónica
α_s_med   {2,3,5} + 131  → QCD medido con precisión
V_cb      {2,3,5} + 83   → mezcla B→charm
θ₂₃       {2,3,5} + 41   → mezcla segunda-tercera generación
Ω_m       {2,3,5} + 7    → fracción de materia del universo
```

Cinco fenómenos de sectores completamente distintos —
un lepton, un acoplamiento, una mezcla CKM, un ángulo PMNS, un parámetro cosmológico —
comparten exactamente la misma base de presuposiciones {2,3,5}.

Todos presuponen: diferenciación (2) + ciclicidad/tiempo (3) + memoria/estado (5).
Ninguno presupone espacio 3D. Ninguno presupone campos de gauge.
Y sobre ese piso común, cada uno añade **una sola elección** diferente.

Esto es presuposición ontológica exacta: mismo piso, distintas habitaciones.

---

## Las cadenas de presuposición

Los pares donde una factorización es subconjunto estricto de otra
son **relaciones de presuposición directa**:

### Ω_m ⊂ m_e

```
Ω_m = {2,3,5,7}
m_e = {2,3,5,7,17}
```

La masa del electrón presupone ontológicamente la fracción de materia
del universo. Y añade exactamente un axioma: primo 17 = mecanismo de masa/Yukawa.

Dicho de otro modo: no puedes preguntar "¿cuánto pesa el electrón?"
sin que ya esté dado que existe materia en el universo.
Pero sí puedes preguntar "¿cuánta materia hay?" sin que esté dado
que existe masa fermiónica por Yukawa.

La presuposición va en una sola dirección.

### α_s_ess ⊂ α

```
α_s_ess = {3,7,11}
α       = {3,7,11,13,17,137,421,521}
```

El acoplamiento electromagnético preciso presupone ontológicamente
el acoplamiento fuerte. α no puede articularse sin que α_s ya esté dado.

Esto es contraintuitivo desde la física estándar (donde EM y QCD se
presentan como independientes), pero tiene sentido en ArXe:
el campo EM (T⁻⁵, primo 11) es estructuralmente posterior al nivel
de masa/espacio 3D (T³, primo 7) que QCD también requiere.

### m_b ⊂ n_s

```
m_b = {2,11,19}
n_s = {2,11,19,509}
```

El índice espectral primordial presupone toda la estructura del quark bottom.
Y añade exactamente un axioma: primo 509 = la elección del modelo de inflación.

Que el universo temprano tenga un espectro de perturbaciones con
pendiente n_s requiere que ya estén dados: diferenciación (2),
campo EM (11), y segunda generación de fermiones (19).
La inflación como fenómeno físico presupone la existencia de
materia de segunda generación.

---

## m_u como átomo ontológico

La constante con el árbol de presuposiciones más corto del corpus:

```
m_u = {2,3}
```

Solo dos axiomas: diferenciación y ciclicidad.
Y es subconjunto de al menos ocho constantes:
m_μ, α_s_med, V_cb, θ₂₃, Ω_m, m_e, m_Z, G_N.

El quark up no es "más fundamental" en el sentido de ser
más importante o más primero en el tiempo.
Es que su **descripción** presupone menos.
No necesita espacio 3D. No necesita campos de gauge.
No necesita generaciones ni masa por Yukawa.

Solo necesita que haya distinción y que haya proceso.

---

## La pregunta que abre: ¿qué es {2×3×5}?

El piso compartido por el grupo más numeroso del corpus
no corresponde a ningún nivel ArXe específico:

```
2 → T¹:  diferenciación / flujo unidireccional
3 → T⁻¹: irreversibilidad / tiempo
5 → T²:  simultaneidad / espacio bidimensional
```

Juntos: los tres primeros niveles de estructura positiva y negativa.
La mínima configuración para que exista **un proceso en el espacio**.

Antes del espacio 3D (primo 7).
Antes de los campos de gauge (primos 11, 13).
Antes del mecanismo de masa (primo 17).

Hipótesis: {2,3,5} es la firma de fenómenos que pertenecen
al "espacio-tiempo pre-gauge" — la capa donde sería posible
en principio una física clásica, sin campos cuánticos.
Las constantes que comparten esta base son exactamente las que
describen fenómenos que *podrían existir* en un universo
con menos estructura que el nuestro.

---

## Consecuencia para el Índice de Naturalidad

El IN (primo máximo) ahora se puede leer con precisión ontológica:

> **IN(C) = el axioma más alto que tuvo que ser elegido para que
> la pregunta "¿cuánto vale C?" sea articulable.**

No es el número de axiomas. Es la profundidad del último.
Y esa profundidad siempre presupone todos los anteriores —
porque sin ellos, ni siquiera el axioma superior tendría sentido.

```
IN = 7   → la pregunta ya requiere que el espacio sea 3D
IN = 17  → ya requiere que exista mecanismo de masa
IN = 41  → ya requiere que el vacío EW tenga un VEV específico
IN = 109 → ya requiere que μ = M_Z sea la escala de referencia
```

Cada salto en el IN no es "más difícil" ni "más energético".
Es ontológicamente más profundo:
presupone todo lo anterior más una elección nueva.

---

## La estructura completa como grafo

Las relaciones de presuposición forman un grafo dirigido acíclico (DAG)
donde las aristas son "A es condición de posibilidad de B":

```
{2}
 ├── {2,3} = m_u
 │    ├── {2,3,5} = piso común
 │    │    ├── + 7  → Ω_m
 │    │    ├── + 17 → m_e  (presupone Ω_m)
 │    │    ├── + 19 → m_μ
 │    │    ├── + 41 → θ₂₃
 │    │    └── + 131→ α_s_med
 │    └── + 7,11 = α_s_ess
 │         └── + 13,17,137,... → α
 └── {2,11,19} = m_b = θ₁₂
      └── + 509 → n_s
```

Este grafo no es una curiosidad matemática.
Es el mapa de **dependencias ontológicas del Modelo Estándar**
leído desde sus constantes hacia sus axiomas.

---

*ArXe / PLO Research — Febrero 2026*
