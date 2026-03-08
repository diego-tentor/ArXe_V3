# Circularidad en el sistema de medidas

**Diego Tentor**  
*LLMPhysics, 2026*

---

## Resumen

La redefinición del Sistema Internacional de Unidades (SI) en 2019 fijó el valor de siete constantes fundamentales por definición, entre ellas la constante de Planck h. Este artículo argumenta que dicha decisión introduce una circularidad estructural en el sistema de medición: las unidades se definen en términos de constantes, y las constantes se verifican con instrumentos calibrados en esas mismas unidades. Se examina esta circularidad como problema epistemológico —en relación con la falsabilidad popperiana— y como inversión ontológica —en relación con el realismo científico sobre las constantes físicas.

---

## 1. El SI antes y después de 2019

Hasta 2018, el Sistema Internacional de Unidades reposaba sobre artefactos físicos y fenómenos naturales. El kilogramo era la masa de un cilindro de platino-iridio conservado en la Oficina Internacional de Pesas y Medidas en Sèvres. El metro era 1/299.792.458 de la distancia recorrida por la luz en el vacío en un segundo. Las unidades referenciaban objetos o fenómenos externos al sistema de medición.

La Resolución 1 de la 26ª Conferencia General de Pesas y Medidas (CGPM, 2018) cambió este esquema de manera radical. Desde el 20 de mayo de 2019, las unidades base del SI se definen fijando valores numéricos exactos de siete constantes fundamentales:

| Constante | Símbolo | Valor exacto fijado |
|-----------|---------|-------------------|
| Constante de Planck | h | 6.62607015×10⁻³⁴ J·s |
| Velocidad de la luz | c | 299.792.458 m/s |
| Carga elemental | e | 1.602176634×10⁻¹⁹ C |
| Constante de Boltzmann | k_B | 1.380649×10⁻²³ J/K |
| Número de Avogadro | N_A | 6.02214076×10²³ mol⁻¹ |
| Eficacia luminosa | K_cd | 683 lm/W |
| Frecuencia del cesio | Δν_Cs | 9.192.631.770 Hz |

El kilogramo ya no es un objeto. Es el valor de h. El ampere ya no mide la fuerza entre conductores. Es el valor de e. La ontología de las unidades cambió: de lo real a lo ideal.

---

## 2. La circularidad estructural

La balanza de Kibble —el instrumento principal que permitió medir h con la precisión necesaria para la redefinición— funciona comparando energía mecánica con energía eléctrica mediante efectos cuánticos. Específicamente, utiliza el efecto Josephson y el efecto Hall cuántico.

El efecto Josephson relaciona voltaje y frecuencia mediante:

$$V = \frac{n f}{K_J}, \quad K_J = \frac{2e}{h}$$

El efecto Hall cuántico relaciona resistencia y constantes fundamentales mediante:

$$R_K = \frac{h}{e^2}$$

Para obtener h de manera "independiente" a partir de estas relaciones, se necesita conocer e. Para conocer e con precisión, se necesita teoría cuántica que ya incorpora h. Las mediciones que condujeron al valor adoptado de h no eran independientes entre sí: compartían supuestos teóricos fundamentales.

El CODATA promediaba estas mediciones ponderando su incertidumbre, pero la coherencia entre ellas era, en parte, coherencia del marco teórico común. No era triangulación desde puntos independientes. Era convergencia dentro del mismo sistema.

Después de 2019, el sistema cerró completamente:

```
h (valor adoptado)
    → define el kilogramo
    → kilogramo calibra la balanza de Kibble
    → balanza de Kibble "mide" h
    → confirma el valor adoptado
```

h es ahora el patrón de h. El sistema no puede producir un resultado que contradiga h, porque cualquier desviación se interpreta como error instrumental, no como corrección al valor de la constante.

---

## 3. El problema epistemológico: Popper invertido

Popper formuló la falsabilidad como actitud epistémica antes que como criterio demarcatorio: la disposición genuina a admitir que una teoría o un valor pueden estar equivocados, a no blindarlos del escrutinio empírico [1]. En ese sentido original, la falsabilidad no es un procedimiento sino una postura ante el conocimiento.

Una constante con valor exacto por definición tiene la estructura opuesta. No puede estar equivocada. Ningún experimento puede corregirla. Si una medición arroja un valor distinto, la conclusión no es "h difiere de lo que pensábamos" sino "el experimento tiene error sistemático". La constante está protegida de la evidencia.

Esto no es un defecto del SI 2019. Es una decisión pragmática coherente: un sistema de medición necesita puntos fijos para funcionar. Lo que resulta filosóficamente significativo es lo que esta decisión revela: que h, en su forma actual, no describe un fenómeno físico susceptible de corrección empírica. Describe un punto de estabilización elegido por convención.

La distinción es precisa. Antes de 2019, h tenía incertidumbre experimental —CODATA 2014 reportaba u_r(h) = 1.2×10⁻⁸— y esa incertidumbre era información sobre la realidad [2]. Después de 2019, h tiene incertidumbre cero por definición, y esa certeza es información sobre la decisión institucional, no sobre el universo.

---

## 4. El problema ontológico: inversión de dirección

En física clásica, la dirección del conocimiento es:

$$\text{Fenómeno} \rightarrow \text{Medición} \rightarrow \text{Número}$$

El fenómeno existe independientemente. La medición lo aproxima. El número converge hacia el valor verdadero con creciente precisión.

El SI 2019 invierte esta dirección:

$$\text{Número (exacto)} \rightarrow \text{Define la unidad} \rightarrow \text{Determina la medición válida}$$

Lo que cuenta como una medición correcta del kilogramo es ahora lo que coincide con el valor de h previamente fijado. La definición determina qué hechos son aceptables. No es que la realidad corrija la definición: es que la definición selecciona la realidad medible.

Esta inversión tiene consecuencias concretas. Si mañana la tecnología permitiera una medición de h con mayor precisión que la utilizada en 2019, y esa medición arrojara un valor en el noveno dígito distinto al adoptado, el resultado no sería "h es 6.62607016×10⁻³⁴". El resultado sería una revisión de los estándares de calibración. El valor de h permanecería intacto.

La física no es arbitraria por esto. Las predicciones que involucran h son extraordinariamente precisas y reproducibles en cualquier laboratorio del mundo. El sistema funciona. Pero lo que produce no es una descripción del universo con creciente fidelidad. Es una descripción internamente coherente, anclada en convenciones que se sostienen mutuamente.

---

## 5. Discusión: ¿realismo o convencionalismo?

El realismo científico sostiene que las constantes físicas describen propiedades del universo que existen independientemente del observador, y que la práctica científica converge hacia sus valores verdaderos [3]. Bajo este marco, la precisión creciente de h entre 1900 y 2018 sería evidencia de esa convergencia.

El SI 2019 complica esta narrativa de dos maneras.

Primero, la convergencia se detuvo por decisión, no por límite físico. No alcanzamos el valor "verdadero" de h. Elegimos un valor suficientemente preciso y lo declaramos exacto porque el sistema lo requería. El CODATA 2018 no reporta menor incertidumbre que el CODATA 2014 porque las mediciones mejoraron dramáticamente. Reporta incertidumbre cero porque se adoptó la decisión de fijar el valor [4].

Segundo, la coherencia del sistema no es evidencia de correspondencia con la realidad. Un sistema puede ser internamente coherente —producir predicciones precisas y reproducibles— sin que eso implique que sus fundamentos describen propiedades independientes del mundo. La coherencia es condición necesaria pero no suficiente para el realismo.

El convencionalismo de Poincaré anticipó parte de este problema al argumentar que la geometría del espacio no es un hecho sino una convención [5]. El SI 2019 extiende este argumento a las unidades de medida: la magnitud del kilogramo no es un hecho del universo sino una convención fijada en relación a h, que es a su vez una convención fijada por consenso.

Esto no implica que la física sea subjetiva. Implica que la objetividad de las constantes físicas es de un tipo distinto al que el realismo ingenuo supone: no correspondencia con propiedades independientes, sino estabilidad bajo triangulación y coherencia predictiva.

---

## 6. Conclusión

La redefinición del SI en 2019 es una decisión metrológica sólida con excelentes razones pragmáticas. También es una decisión filosóficamente significativa que merece ser examinada como tal.

La circularidad que introduce —h define el kilogramo, el kilogramo calibra los instrumentos que "miden" h— no es un error. Es la estructura necesaria de cualquier sistema de medición que se cierra sobre sí mismo para garantizar coherencia interna.

Lo que esta circularidad revela es que las constantes físicas operan en dos registros simultáneamente: como descripciones de fenómenos físicos, y como convenciones que constituyen el sistema de descripción. Confundir ambos registros —tratar h como propiedad descubierta cuando es también convención adoptada— es el núcleo del problema epistemológico y ontológico que este artículo intenta señalar.

La pregunta que queda abierta no es si el SI 2019 es correcto. Es si el realismo científico, tal como se practica y se comunica, tiene los recursos conceptuales para sostener simultáneamente que h es una propiedad del universo y que su valor fue fijado por votación.

---

## Referencias

[1] Popper, K. R. (1959). *The Logic of Scientific Discovery*. Hutchinson. (Original en alemán: 1934)

[2] CODATA 2014. Mohr, P. J., Newell, D. B., & Taylor, B. N. (2016). CODATA recommended values of the fundamental physical constants: 2014. *Reviews of Modern Physics*, 88(3), 035009.

[3] Psillos, S. (1999). *Scientific Realism: How Science Tracks Truth*. Routledge.

[4] BIPM (2019). *The International System of Units (SI)*, 9th edition. Bureau International des Poids et Mesures.

[5] Poincaré, H. (1902). *La Science et l'Hypothèse*. Flammarion.

---

*Correspondencia: Diego Tentor — La lógica del Arché*  
*Licencia: CC BY-SA 4.0*
