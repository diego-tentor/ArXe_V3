# ArXe — N-aridades y Constantes Matemáticas
## Tabla de Asignaciones con Justificación Estructural

*Documento interno — Febrero 2026*

---

## La lógica de la tabla

Cada fila responde tres preguntas:

1. **¿Por qué esta constante NO puede vivir en niveles anteriores?** — qué estructura le falta
2. **¿Por qué este nivel es el mínimo suficiente?** — qué estructura habilita la constante
3. **¿Qué propiedad matemática abierta refleja la BC abierta del nivel?** — la indecidibilidad constitutiva

---

## La tabla

| Nivel | BC | Primo | Constante | Por qué no antes | Por qué aquí | Indecidibilidad constitutiva |
|-------|-----|-------|-----------|-----------------|--------------|------------------------------|
| **T¹** | 1c / 0o | 2 | √2 | No existe aún ninguna relación entre dos direcciones — T⁰ es contradicción pura | La diferenciación binaria (1 BC cerrada) crea exactamente dos direcciones. √2 es la tensión entre ellas: la diagonal del espacio binario mínimo | Ninguna — 0 BC abiertas. √2 es completamente conocible: irracional, algebraico, demostrado desde la antigüedad |
| **T⁻¹** | 0c / 1o | 3 | π | Con solo n=2 no hay tercer elemento. Un ángulo requiere: posición, dirección, cierre. Sin ternariedad no se puede cerrar ninguna rotación | La BC abierta es la dirección del tiempo no determinada. π mide exactamente esa apertura: la relación entre el contorno de la indecidibilidad ternaria y su anchura | Normalidad no demostrada. La extensión infinita de π sobre todos los dígitos no está caracterizada — refleja que la BC abierta no se cierra nunca desde adentro del nivel |
| **T²** | 2c / 0o | 5 | φ | Con n=3 hay ciclo y alternación pero no auto-referencia estabilizada. Para que algo "se contenga a sí mismo como parte" se necesita anterioridad espacial | Las 2 BC cerradas crean una estructura donde el todo y la parte pueden coexistir. φ es el único punto fijo de x = 1 + 1/x — la estabilización de esa auto-referencia cuaternaria | Ninguna — 0 BC abiertas. φ es completamente conocible: irracional, algebraico (raíz de x²−x−1=0), demostrado |
| **T³** | 3c / 0o | 7 | e | Requiere objetividad triádica: que el cambio "recuerde" su estado anterior. Con n<6 no hay memoria histórica ni distinguibilidad del presente | Las 3 BC cerradas constituyen la estructura completa de masa/objetividad. e es la única función igual a su propia derivada — requiere que el cambio y su registro sean el mismo objeto | Ninguna — 0 BC abiertas. e es completamente conocible: transcendente, demostrado (Hermite 1873) |
| **T⁻³** | 2c / 1o | 7 | γ | Requiere que existan simultáneamente un dominio discreto (suma) y uno continuo (logaritmo). Eso no es posible antes de T³ (donde emerge la objetividad que hace distinguibles los dos dominios) | Las 2 BC cerradas sostienen los dos dominios. La 1 BC abierta es la frontera entre ellos — que no está determinada intrínsecamente. γ es el residuo permanente de esa frontera | Irracionalidad no demostrada (problema abierto ~250 años). La pregunta no puede responderse desde dentro de ninguno de los dos dominios que γ habita — requeriría caracterizar la frontera misma, que la BC abierta hace constitutivamente indeterminada |
| **T⁻⁵** | 4c / 1o | 11 | ζ(3) | Requiere que exista una diferencia estructural entre valores pares e impares de ζ — eso implica que π ya esté constituido (T⁻¹) y que haya suficiente estructura cerrada para que algo quede más allá de su alcance | Las 4 BC cerradas crean un contexto estructural que π no puede alcanzar desde T⁻¹. La 1 BC abierta es exactamente lo que π no puede cerrar: la información que los valores impares de ζ portan y que los valores pares no | Transcendencia no demostrada. No existe expresión cerrada en π. La pregunta "¿qué es ζ(3) en términos de objetos conocidos?" requiere caracterizar qué hay más allá de π — y eso es precisamente lo que la BC abierta de T⁻⁵ no determina |
| **T⁻⁶** | 5c / 1o | 13 | δ (Feigenbaum) | Requiere que existan sistemas dinámicos con parámetros variables y que la noción de "transición entre orden y caos" tenga sentido. Eso requiere la estructura completa de T³ (masa, objetividad) más los niveles intermedios | Las 5 BC cerradas sostienen todos los sistemas dinámicos posibles con estructura de bifurcación. La 1 BC abierta es la transición misma — que no pertenece a ningún sistema específico sino a todos simultáneamente | Irracionalidad y naturaleza algebraica completamente desconocidas. δ no puede ser caracterizado desde ningún sistema particular porque su definición trasciende todos ellos — la BC abierta hace que su "base" sea constitutivamente indefinida |
| **T⁻⁸** | 6c / 1o | 17 | ζ(5), ζ(7)... | Requiere que la familia ζ(2n+1) esté constituida más allá de ζ(3), con una estructura de indecidibilidad creciente dentro de la misma familia | Las 6 BC cerradas crean un contexto aún más rico que T⁻⁵. La 1 BC abierta persiste pero rodeada de más estructura cerrada — la indecidibilidad toma una forma más "localizada" pero más profunda | Irracionalidad de ζ(5), ζ(7)... ni siquiera se sabe si alguno es irracional. La pregunta está más abierta que para ζ(3) — ni el tipo de pregunta que hay que hacer está establecido |

---

## El patrón central

```
BC todas cerradas  →  constante completamente conocible
                      (√2, φ, e — algebraicas o trascendentes, todas demostradas)

BC con 1 abierta   →  constante con indecidibilidad constitutiva
                      (π, γ, ζ(3), δ — algo en su naturaleza resiste la demostración)
```

La indecidibilidad no escala en intensidad con T⁻ⁿ.
Lo que escala es el **contexto** dentro del cual la 1 BC abierta existe.
Cada nivel añade BC cerradas que "rodean" la apertura de maneras diferentes.
Eso cambia la **forma** de la indecidibilidad, no su profundidad.

---

## La asimetría que lo explica todo

Los niveles positivos (T¹, T², T³) tienen **todas las BC cerradas**.
Son estructuralmente completos — no hay ninguna dirección sin determinar.
Sus constantes matemáticas son por eso completamente conocibles.

Los niveles negativos (T⁻¹, T⁻³, T⁻⁵...) tienen siempre **exactamente 1 BC abierta**.
Son estructuralmente incompletos por construcción — hay siempre una dirección sin determinar.
Sus constantes matemáticas portan esa incompletitud como propiedad constitutiva.

No es que sean difíciles de estudiar.
Es que son objetos que **incluyen en su definición** una apertura que no se cierra desde dentro del nivel.

---

## Sobre los niveles positivos sin constante matemática "famosa"

T⁰ (n=1, contradicción pura): no genera ninguna constante — no hay estructura mínima para nada.

T⁴ (n=9, hiperespacio computacional): debería generar constantes matemáticas en el dominio de la computación/información. Candidatos posibles: la constante de Chaitin Ω (número de parada), que es no computable por construcción. Tiene 0 BC abiertas en T⁴ pero su definición involucra un proceso que nunca se cierra — curiosamente análogo a la situación opuesta.

---

## Nota sobre la dirección causal

Esta tabla no dice que ArXe "explica" estas constantes.
Dice que la estructura de ArXe es **consistente** con el patrón observado, y que ese patrón no era obvio antes de tener el framework.

La asignación en cada fila es una **correspondencia estructural**, no una derivación.
El criterio es: ¿la estructura lógica mínima del nivel es necesaria y suficiente para que la constante pueda existir como esencia emergente?

Si la respuesta es sí en todos los casos — y parece serlo — eso es evidencia de coherencia, no de prueba.

---

*ArXe / PLO Research — Febrero 2026*
