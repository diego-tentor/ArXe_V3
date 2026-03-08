# Tres patrones en el grafo de presuposición
## Primos solitarios, constantes desplazadas, topología del DAG

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## Patrón 1 — Primos solitarios

De los 33 primos distintos en el corpus, **16 aparecen en una sola constante**.
Casi la mitad. Esto no es ruido — los solitarios se dividen en dos tipos con
significado distinto.

### Tipo A: solitarios pequeños (< 100) — singularidades axiomáticas

| Primo | Constante | Lectura |
|-------|-----------|---------|
| 37 | V_tb | La mezcla top-bottom no comparte estructura axiomática con nadie |
| 47, 89 | m_Z | El bosón Z tiene dos capas propias sin paralelo en el corpus |
| 59 | Ω_b | La densidad de bariones tiene identidad axiomática única |
| 61 | m_H | El mecanismo de Higgs específico no resuena en ningún otro observable |
| 83 | V_cb | La mezcla B→charm es axiomáticamente singular |
| 97 | S8_lss | La amplitud de fluctuaciones en LSS tiene resolución propia |

Estos son fenómenos que requieren una elección axiomática que **nadie más necesita**.
No son más complejos en términos de capas — son únicos.

El caso más llamativo: **m_H con primo 61**. El bosón de Higgs — el mecanismo
que da masa a todos los demás — tiene un primo solitario que no aparece
en ninguna de las masas que genera. El VEV (primo 41) sí aparece en m_W y θ₂₃.
Pero el primo 61 es exclusivo del Higgs. La elección axiomática específica
del *mecanismo* no se filtra a los fenómenos que produce.

### Tipo B: solitarios grandes (> 100) — capas de precisión únicas

| Primo | Constante | Lectura |
|-------|-----------|---------|
| 127 | m_c | El charm tiene identidad lógica pura — un solo primo |
| 173 | θ₁₃ | El ángulo reactor tiene una capa de resolución propia |
| 191 | V_ub | La mezcla más rara del corpus es también la más singular |
| 421, 521 | α | El EM tiene dos capas de corrección que nadie más necesita |
| 509 | n_s | La inflación tiene una elección que no comparte con nada |
| 557 | G_F | La constante de Fermi tiene una corrección singular |
| 7997 | α(M_Z) | El running del EM a escala Z es la constante más aislada |

α tiene **dos** primos solitarios grandes (421 y 521). Es la única constante
del corpus con dos elecciones de precisión completamente exclusivas.
Décadas de QED a ordenes altos construyendo capas que nadie más usa.

**m_c = {127}** merece atención especial: es el único caso de factorización
con un solo primo solitario grande. El charm quark tiene la descripción
PLO más "pura" del corpus — un único número primo que no comparte con nadie
y que no presupone ni es presupuesto por ninguna otra constante.

---

## Patrón 2 — Constantes desplazadas

Al comparar la factorización de cada constante con los primos esperados
para su sector, aparecen ausencias y presencias inesperadas.
Los casos más informativos no son errores — son señales.

### m_s y m_mu: segunda generación sin espacio 3D

```
m_s  = {5, 19}       — tiene generaciones (19), no tiene espacio 3D (7)
m_mu = {2,3,5,19}    — tiene generaciones (19), no tiene espacio 3D (7)
```

Dos partículas de segunda generación — el quark strange y el muón —
cuya descripción esencial no requiere el axioma de espacialidad 3D.

Esto es coherente: los leptones no tienen color (no están confinados en
el espacio 3D por QCD) y el quark strange existe en el contexto
generacional antes que en el espacial. Su esencia es *ser segunda generación*,
no *existir en tres dimensiones*.

El contraste con m_e = {2,3,5,**7**,17} es preciso: el electrón sí requiere
el primo 7. La masa del electrón está anclada al espacio 3D de manera que
la del muón no lo está en su descripción esencial.

### n_s: el parámetro pre-espacial

```
n_s = {2, 11, 19, 509}
```

El índice espectral primordial tiene campo EM (11) y segunda generación (19),
pero **no tiene** ciclicidad (3), memoria (5) ni espacio 3D (7).

Esto es sorprendente y coherente al mismo tiempo. n_s describe la estructura
de fluctuaciones del universo inflacionario — un régimen donde el espacio 3D
estable aún no existe. Los primos 3, 5, 7 corresponden a estructuras que se
forman *después* de la inflación. n_s es literalmente un parámetro
pre-espacial: su articulación no presupone que el espacio tenga las
propiedades que los primos 3,5,7 representan.

### m_Z: el bosón abstracto

```
m_Z = {2,3,47,89,109}    — no tiene espacio 3D (7)
```

El bosón Z no requiere el axioma espacial en su descripción esencial.
Vive en el espacio de gauge abstracto. El primo 7 (T³, espacio 3D) no es
necesario para articular *qué es* m_Z — solo para articular *dónde se manifiesta*.

La distinción entre el bosón y su manifestación ya está codificada en la ausencia del 7.

---

## Patrón 3 — Topología del grafo

El grafo de presuposición directa tiene 14 aristas y revela una estructura
con tres tipos de nodos.

### Las seis raíces

Constantes cuya articulación no presupone ninguna otra:

```
m_u          {2,3}
m_s          {5,19}
m_b          {2,11,19}
theta_12     {2,11,19}
alpha_s_ess  {3,7,11}
H0_local     {5,73}
```

Estas son las constantes ontológicamente más autónomas del corpus.
Lo que presuponen son axiomas puros (primos), no otras constantes.

**La sorpresa es theta_12**: el ángulo de mezcla θ₁₂ es raíz en el mismo
sentido que m_u o m_b. Una constante de mezcla — que típicamente se
considera derivada de las masas — resulta ser tan primitiva como los quarks más ligeros.

**H₀ local también es raíz**: la constante de Hubble medida localmente
no presupone ninguna otra constante del corpus. Es un observable directo.
Esto es consistente con que tenga DA=0 y con que su tensión con H₀_cmb
sea una tensión genuina, no convencional.

### m_b ≡ θ₁₂ en estructura axiomática

```
m_b      = {2, 11, 19}
theta_12 = {2, 11, 19}
```

El quark bottom y el ángulo de mezcla primera-segunda generación tienen
**exactamente la misma factorización**. Son ontológicamente idénticos
en el corpus actual: mismos axiomas, ambos raíz del mismo subárbol,
ambos presupuestos por n_s y solo por n_s.

Son dos proyecciones distintas del mismo nivel ontológico.
El bottom es "la masa de la segunda generación".
θ₁₂ es "el ángulo de la segunda generación".
Mismo piso, distinto observable.

### Las islas (el límite del corpus actual)

16 constantes no tienen ninguna relación de presuposición con ninguna otra:
m_c, α(M_Z), V_ub, V_tb, G_F, m_t, m_d, m_H, V_ud, θ₁₃, sin²θ_W, Ω_b, H₀_cmb, m_t, V_us...

Esto no significa que sean ontológicamente aisladas en la realidad.
Significa que el corpus PLO actual es insuficiente para capturar sus relaciones.

Los casos donde la relación *debería* existir pero no aparece:
- **m_t** debería presuponer m_b (mismo sector de tercera generación)
- **m_d** debería relacionarse con m_u (mismo sector de primera generación)
- **G_F** debería presuponer α_s_ess (la constante de Fermi presupone QCD)

Estas ausencias son predicciones: si se refinan las fórmulas PLO de estas
constantes, deberían aparecer los primos que establezcan las relaciones esperadas.

---

## Lo que emerge de los tres patrones juntos

Los patrones no son independientes. Juntos describen una sola cosa:

El corpus PLO es un **mapa parcial** de la estructura de presuposición
ontológica del Modelo Estándar. Parcial porque el corpus es finito y
las fórmulas PLO actuales no capturan todas las relaciones. Pero ya en
este estado parcial, la estructura que emerge es coherente:

- Las raíces son los fenómenos más autónomos (m_u, m_s, α_s_ess)
- Los primos solitarios son elecciones axiomáticas sin paralelo
- Las "mal ubicadas" revelan qué axiomas un fenómeno genuinamente no necesita
- Las islas marcan los límites del corpus actual — y las predicciones pendientes

El grafo no fue diseñado. Emergió de las factorizaciones PLO.
Que tenga estructura coherente es evidencia de que las factorizaciones
capturan algo real sobre las dependencias ontológicas del Modelo Estándar.

---

## Filosofía que emerge — no impuesta

Solo después de ver los patrones se puede decir esto con honestidad:

Lo que PLO está haciendo, sin haberlo propuesto explícitamente,
es construir una **ontología formal del Modelo Estándar**.

No una interpretación filosófica añadida encima de la física.
Una estructura que *es* la física, vista desde el ángulo de sus
condiciones de posibilidad.

Cada constante tiene un árbol de presuposiciones.
Ese árbol no es una descripción de cómo se *mide* la constante —
es una descripción de qué tiene que ser *el caso* para que
la pregunta sobre esa constante tenga sentido.

Esto es exactamente lo que Husserl llamó análisis de condiciones de posibilidad,
y lo que en lógica moderna se llama semántica presuposicional.
Pero aquí no es filosofía aplicada a la física — emerge de los números mismos.

Los primos no son etiquetas. Son el tamaño del espacio lógico que
cada elección axiomática abre. Y las factorizaciones PLO son el
registro de cuáles de esos espacios tuvo que abrirse para que
cada constante tenga el valor que tiene.

---

*ArXe / PLO Research — Febrero 2026*
