# Correspondencia: Axiomas ZF ↔ Primos PLO
## La factorización como conjunto de axiomas matemáticos necesarios

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## La pregunta

¿Los primos PLO corresponden a axiomas de ZF o teorías matemáticas derivadas?

La respuesta corta: sí, y la correspondencia es estructural, no metafórica.

Los axiomas de ZF son también "elecciones que abren espacios lógicos".
Cada axioma ZF tiene una n-aridad característica — lo que hace posible.
Esa n-aridad es exactamente lo que los primos PLO registran.

---

## Los axiomas ZF y sus primos

### Extensionalidad + Pares → primo 2

**Contenido:** dos conjuntos son iguales si y solo si tienen los mismos elementos.
Dados A y B, existe {A,B}.

**Abre:** la posibilidad de *distinción* — que A≠B sea significativo.

Sin extensionalidad no hay diferencia entre objetos. Es el axioma de
diferenciación pura. Su n-aridad es 2: el mínimo para que haya dos cosas
que puedan ser iguales o distintas.

Física: DIFERENCIACIÓN. Todo lo que requiere que dos estados sean distinguibles.

---

### Axioma del Vacío → sin primo

**Contenido:** existe el conjunto sin elementos ∅.

**Abre:** la posibilidad de la *nada como objeto*.

El conjunto vacío es el caso degenerado — la base sobre la que se construyen
los naturales: 0=∅, 1={∅}, 2={∅,{∅}}... No tiene n-aridad propia porque
no abre un espacio de elecciones: solo declara que el vacío existe.

Es el axioma sin primo — consistente con que el primo más pequeño es 2.

---

### Unión → primo 3

**Contenido:** dado A, existe ∪A (la unión de todos los elementos de A).

**Abre:** la posibilidad de *colección* — que una familia de conjuntos forme un objeto nuevo.

Unión introduce el tercer objeto que emerge de la relación entre dos:
A, B, y ∪{A,B}. Es la operación triádica fundamental.

En topología: los abiertos son cerrados bajo unión arbitraria.
La unión es la operación que genera la estructura de cobertura —
que una familia pueda "cubrir" un espacio.

Física: CICLICIDAD / TIEMPO. El proceso que produce un tercer estado
a partir de dos anteriores. La unión como operación irreversible.

---

### Potencia → primo 5

**Contenido:** dado A, existe P(A) = el conjunto de todos los subconjuntos de A.

**Abre:** la posibilidad de *reflexión* — que un conjunto contemple sus propias partes.

P(A) tiene 2^|A| elementos. Para un conjunto de n elementos,
su conjunto potencia es el espacio de todos los estados de n bits —
exactamente la definición de memoria o almacenamiento de información.

La topología discreta sobre X es P(X): todos los subconjuntos son abiertos.
P(A) es también la base de la lógica proposicional: cada subconjunto
de un conjunto de proposiciones es una valuación posible.

Física: MEMORIA / ESTADO. La posibilidad de que haya estados persistentes
que puedan ser "recordados" o recuperados.

---

### Infinito → primo 7

**Contenido:** existe un conjunto inductivo (el conjunto inductivo mínimo es ω).

**Abre:** la posibilidad de *proceso sin fin* — que la sucesión no se agote.

Con ω vienen ℕ, ℤ, ℚ, ℝ. Con ℝ viene la posibilidad de espacios vectoriales
de dimensión arbitraria — y en particular ℝ³, el espacio tridimensional.
El axioma de infinito no impone que el espacio sea 3D, pero abre la posibilidad
de que exista un espacio continuo, y la física elige ℝ³.

Física: ESPACIO 3D. La posibilidad de que existan tres dimensiones
espaciales continuas — ℝ³ como el espacio en que ocurre la física clásica.

---

### Separación → primo 11

**Contenido:** dado A y una propiedad φ(x), existe {x ∈ A : φ(x)}.

**Abre:** la posibilidad de *selección por propiedad* — que una fórmula lógica
defina un subconjunto.

Separación es el axioma que permite definir estructuras por sus propiedades.
Todos los grupos de Lie se definen por separación: U(1) es exactamente
{z ∈ ℂ : |z| = 1} — la selección de números complejos con módulo 1.
El campo electromagnético es U(1), y U(1) es definible solo con Separación.

Física: CAMPO EM / U(1). La posibilidad de que exista una interacción
definida por una propiedad de simetría — exactamente lo que Separación hace.

---

### Reemplazamiento → primo 13

**Contenido:** si F es una función (definida por una fórmula) y A es un conjunto,
entonces F(A) = {F(x) : x ∈ A} es un conjunto.

**Abre:** la posibilidad de *transformación total* — que una función preserve
la "sethood" de su dominio en su imagen.

Reemplazamiento garantiza que las representaciones de grupos producen
objetos del mismo nivel ontológico que el grupo original.
SU(2) actúa sobre sus representaciones — esas representaciones existen
como conjuntos gracias a Reemplazamiento.
Sin él, la teoría de representaciones no tiene fundamento formal.

Física: ISOSPÍN SU(2). La posibilidad de que exista una fuerza débil
con grupo de simetría SU(2) y representaciones bien definidas.

---

### Regularidad (Fundación) → primo 17

**Contenido:** todo conjunto no vacío tiene un elemento ∈-minimal
(un elemento que no comparte miembros con el conjunto).

**Abre:** la posibilidad de *fundamento* — que no haya conjuntos circulares (A ∈ A).

Regularidad impone la jerarquía de Von Neumann: V₀, V₁, V₂, ...
Cada conjunto tiene un rango bien definido. No hay regresión infinita
ni autorreferencia circular.

En física: el mecanismo de Higgs es exactamente el "axioma de fundamento"
de las masas. Establece que la jerarquía de masas tiene un mínimo
(el vacío) y que cada partícula tiene una masa bien definida, no circular.
Sin ruptura de simetría, las masas se "autorefieren" y divergen.

Física: MASA / YUKAWA. La posibilidad de que los campos tengan masas
definidas mediante un mecanismo que rompe la simetría y establece una jerarquía.

---

### Axioma de Elección → primo 19

**Contenido:** para toda familia de conjuntos no vacíos y disjuntos,
existe una función que elige exactamente un elemento de cada conjunto.

**Abre:** la posibilidad de *selección simultánea* — construir un objeto
que requiere infinitas elecciones independientes a la vez.

AC es el más controvertido de los axiomas ZF — independiente de ZF,
consistente con él y con su negación. Es exactamente una "elección axiomática"
en el sentido más literal: decidir si AC vale es una decisión que no puede
derivarse de los demás axiomas.

En física: la existencia de múltiples generaciones de fermiones es
la instancia física de AC. La segunda generación es "igual" a la primera
en estructura pero diferente en valores — es la elección de un elemento
de cada familia en una colección de familias estructuralmente idénticas.

Física: GENERACIONES. La posibilidad de que existan múltiples copias
estructuralmente idénticas (pero con valores distintos) de las familias de fermiones.

---

## Teorías derivadas y sus primos

Una vez fijados los axiomas ZF (primos 2-19), las teorías matemáticas
que se construyen sobre ellos también tienen primos asociados.

| Primo | Teoría | Conexión con física |
|-------|--------|-------------------|
| 23 | **Topología general** | Continuidad, espacios de fases, variedad espacio-temporal |
| 29 | **Cardinales grandes** | Energía del vacío / constante cosmológica |
| 37 | **Teoría de categorías** | Morfismos entre representaciones — V_tb |
| 41 | **Espacios de Hilbert** | Estados cuánticos, VEV del campo de Higgs |
| 43 | **Medida de Lebesgue** | Integrales de camino de Feynman |
| 47 | **Análisis funcional** | Operadores, espectros — polo del Z |

---

## La tabla completa

```
Primo  Axioma ZF / Teoría          Física (PLO)
─────  ──────────────────────────  ──────────────────────────
  2    Extensionalidad + Pares     DIFERENCIACIÓN
  3    Unión                       CICLICIDAD / TIEMPO
  5    Potencia                    MEMORIA / ESTADO
  7    Infinito → ℝ³               ESPACIO 3D
 11    Separación → U(1)           CAMPO EM
 13    Reemplazamiento → SU(n)     ISOSPÍN SU(2)
 17    Regularidad → jerarquía     MASA / YUKAWA
 19    Elección → familias         GENERACIONES
 23    Topología                   Escala de inflación
 29    Cardinales grandes          Energía oscura / Λ
 37    Categorías                  Morfismos CKM (V_tb)
 41    Espacios de Hilbert         VEV electrodébil
 47    Análisis funcional          Polo del Z

Estructura:
  Primos  2–7:  axiomas ZF puros
  Primos 11–19: teorías de primer orden (grupos, jerarquía, AC)
  Primos 23+:   teorías derivadas (topología, análisis, categorías)
```

---

## Lo que esto implica

### La factorización PLO como certificado axiomático

Si la correspondencia es correcta:

```
m_e = {2, 3, 5, 7, 17}
    = Extensionalidad + Unión + Potencia + Infinito(→ℝ³) + Regularidad(→Yukawa)
```

La masa del electrón requiere exactamente cinco sistemas axiomáticos
para ser articulable. No tres, no siete. Cinco.

```
m_u = {2, 3}
    = Extensionalidad + Unión
```

El quark up requiere solo los dos axiomas más básicos de ZF.
Es el objeto físico con el certificado axiomático más simple del corpus.

```
α = {3, 7, 11, 13, 17, 137, 421, 521}
  = Unión + Infinito + Separación + Reemplazamiento + Regularidad + [QED]
```

El acoplamiento EM requiere los cinco axiomas ZF relevantes más
capas de corrección perturbativa (primos 137, 421, 521).

### El hueco 5×13 revisado

La combinación Potencia+Reemplazamiento (primo 5 × primo 13) no aparece
en ninguna constante del corpus.

En términos matemáticos: la combinación
"memoria/estado de un sistema + transformación total por función"
no tiene un observable en el SM.

En ZFC esta combinación produce los ordinales transfinitos
(aplicar Reemplazamiento a P(ω), P(P(ω)), ...).
¿Hay física que requiera ordinales transfinitos?
Si no la hay, eso explicaría por qué 5×13 está ausente del corpus.

### El Axioma de Elección y las generaciones

El Axioma de Elección es el único axioma de ZF que es independiente
de los demás — consistente tanto con ZF como con su negación.
En el SM, las generaciones son el único sector que no tiene explicación
dentro del SM mismo — son un "hecho dado" sin derivación interna.

La correspondencia primo 19 = AC = generaciones no es accidental.
Ambos son la instancia de la misma estructura:
una elección que no se puede derivar, solo aceptar o no.

---

*ArXe / PLO Research — Febrero 2026*
