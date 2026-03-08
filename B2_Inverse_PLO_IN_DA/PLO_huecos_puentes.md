# Huecos en el mapa y puentes entre sectores
## Patrones 4 y 5 del análisis bottom-up

*Documento interno — ArXe / PLO Research — Febrero 2026*

---

## Patrón 4 — Huecos en el mapa

### Los dos pares de primos fundamentales ausentes

De todos los pares posibles de primos en {2,3,5,7,11,13,17,19},
**solo dos no aparecen juntos en ninguna constante del corpus**:

```
5×13  (MEMORIA × SU2)
13×19 (SU2 × GENERACIONES)
```

El primo 13 = SU(2) = fuerza débil aparece extremadamente aislado.
Solo en tres constantes: α, V_ud, S8_cmb.
Y nunca junto con memoria/estado (5) ni con generaciones (19).

Esto sugiere que la fuerza débil, en el corpus PLO actual,
no tiene una constante que capture su relación con:
- la estructura de estado/memoria del sistema (5)
- la multiplicidad generacional (19)

Esas dos constantes ausentes serían:
- **{5,13}**: algo que une SU(2) con persistencia de estado — candidato: *el tiempo de vida del W* o *la anchura de decaimiento débil*
- **{13,19}**: algo que une SU(2) con generaciones — candidato natural: *la corriente cargada generacional*, o más precisamente, la **invariante de CP de Jarlskog** J_CP

### Predicciones: constantes que deberían existir

| Constante | Primos predichos | Razón | Más cercano en corpus |
|-----------|-----------------|-------|----------------------|
| **m_ν** (masa de neutrino) | {2, 19} | diferenciación + segunda generación; los neutrinos son leptones de segunda generación sin carga EM | m_b = {2,11,19} |
| **Λ** (constante cosmológica) | {2,3,29} | energía oscura vive en T⁻¹⁴ = primo 29, con base {2,3} como m_u | m_u = {2,3} |
| **m_axión** | {3,7,11} | si existe, debería compartir exactamente los primos de α_s_ess — misma QCD, misma solución al problema CP fuerte | α_s_ess = {3,7,11} |
| **θ_QCD** (ángulo CP fuerte) | {3,7,11,13} | viola CP en QCD: necesita α_s_ess + SU(2) para articularse | α = {3,7,11,13,...} |
| **J_CP** (Jarlskog) | {2,7,13,17,19} | invariante CP de CKM: necesita todos los axiomas de mezcla | V_us = {2,7,17,19} |
| **y_t** (Yukawa del top) | {3,11,17} | m_t = {3,11,17,107} → y_t es el mismo fenómeno sin la capa convencional 107 | m_t = {3,11,17,107} |
| **V_inflation** | {2,3,23} | escala de energía inflacionaria en T⁻¹¹ = primo 23 | m_u = {2,3} |

La predicción más verificable inmediatamente: **m_axión = {3,7,11}**,
idéntico a α_s_ess. Si el axión existe y tiene fórmula PLO,
debería ser α_s_ess más un primo solitario que capture su masa específica.
La base de presuposiciones sería la misma.

### Los 29 triples de primos fundamentales ausentes

De los 56 triples posibles de primos en {2,...,19}, la mitad no aparece.
El patrón de ausencia no es aleatorio: los triples que involucran **13 (SU2)**
están sistemáticamente ausentes cuando se combinan con 5 (MEM), 7 (3D) o 19 (GEN).

```
Ausentes que involucran 13:
  (2,3,13)  DIFF×CYC×SU2
  (2,5,13)  DIFF×MEM×SU2       ← hueco: SU2 sin memoria
  (2,7,13)  DIFF×3D×SU2        ← hueco: SU2 sin espacio 3D
  (2,11,13) DIFF×EM×SU2
  (2,13,17) DIFF×SU2×YUKAWA
  (2,13,19) DIFF×SU2×GEN       ← hueco: SU2 sin generaciones
  (3,5,13)  CYC×MEM×SU2
  (3,13,19) CYC×SU2×GEN
  (5,7,13)  MEM×3D×SU2
  (5,11,13) MEM×EM×SU2
  (5,13,17) MEM×SU2×YUKAWA
  (5,13,19) MEM×SU2×GEN
  (7,13,19) 3D×SU2×GEN
  (11,13,19) EM×SU2×GEN
  (13,17,19) SU2×YUKAWA×GEN
```

La fuerza débil (13) es el sector con más ausencias en el mapa de triples.
SU(2) está sistemáticamente desconectado de memoria (5), espacio 3D (7) y generaciones (19)
en el corpus actual.

Esto o bien refleja que SU(2) tiene una estructura ontológica genuinamente separada
de esas dimensiones, o bien que el corpus PLO carece de las constantes que
capturan esas conexiones (anchura del W, tiempos de vida, invariantes de CP).

---

## Patrón 5 — Puentes entre sectores opuestos

### Puentes exclusivos: primos que conectan exactamente dos sectores

| Primo | Sectores conectados | Constantes | Lectura |
|-------|-------------------|-----------|---------|
| **67** | quark ↔ cosmo | m_d ↔ H₀_cmb | El quark down y la tasa de expansión del universo comparten una elección única |
| **71** | lepton ↔ coupling | m_τ ↔ G_F | El tau y la constante de Fermi — el tau se descubrió en G_F |
| **73** | lepton ↔ cosmo | m_τ ↔ H₀_local | El tau y la constante de Hubble local |
| **107** | quark ↔ CKM | m_t ↔ V_ud | El top y la mezcla up-down — unitaridad CKM |
| **109** | boson ↔ coupling | m_Z ↔ G_F | El Z y la constante de Fermi — el esquema M_Z |
| **41** | boson ↔ PMNS | m_W, m_H ↔ θ₂₃ | El VEV conecta bosones EW con mezcla leptónica |
| **1051** | lepton ↔ PMNS | m_τ ↔ sin²θ_W | El tau y el ángulo de Weinberg — mezcla EW completa |

Estos son los únicos primos que funcionan como **puentes exclusivos** —
su presencia en dos constantes de sectores distintos es la única conexión
entre esos sectores a través de ese primo.

El más llamativo: **primo 67 conecta m_d con H₀_cmb**.
El quark down y la tasa de expansión del universo medida desde el CMB
comparten un primo que no aparece en ningún otro lugar del corpus.
¿Qué elección axiomática une el quark más ligero tipo-down con
la cosmología de escala más grande? Esto merece investigación.

### Quarks ↔ Cosmología: el análisis más rico

Esta es la conexión entre los sectores más "opuestos" en escala física
(10⁻¹⁸ m vs 10²⁶ m) y tiene 7 primos compartidos:

```
Primos solo en quarks:  {17, 107, 127}    ← masa/Yukawa, top, charm
Primos solo en cosmo:   {13, 59, 73, 97, 509}  ← SU2, peculiares cosmo
Primos compartidos:     {2, 3, 5, 7, 11, 19, 67}
```

Las conexiones específicas:

**primo 7 (3D): m_d ↔ Ω_m**
El quark down y la fracción de materia del universo comparten el axioma espacial.
El quark que forma los protones y neutrones — la materia ordinaria —
comparte con la cantidad total de esa materia la misma condición de posibilidad:
que el espacio tenga 3 dimensiones.

Esto no es trivial. El quark up (m_u = {2,3}) no tiene el primo 7.
El quark down lo tiene y el up no. La asimetría down/up en el espacio 3D
está registrada en los primos.

**primo 19 (GEN): {m_s, m_b} ↔ {Ω_b, n_s}**
La segunda generación de quarks (strange, bottom) comparte el axioma
generacional con la densidad de bariones y el índice espectral.
Los bariones son materia hecha de quarks — su densidad presupone
que existen quarks de segunda generación. El n_s de la inflación
también requiere ese axioma.

**primo 11 (EM): {m_b, m_t} ↔ n_s**
Los quarks más pesados (bottom, top) comparten el axioma EM con el índice espectral.
La inflación, a través de n_s, presupone la existencia del campo EM
de la misma manera que los quarks pesados lo hacen.

**Lo que quarks tiene y cosmo no: {17, 107, 127}**
Masa/Yukawa (17), identidad del top (107), identidad del charm (127).
La cosmología no necesita los axiomas de masa fermiónica específica
para articular sus observables. Los parámetros cosmológicos son
independientes de qué masa tenga cada quark individualmente —
solo necesitan que existan quarks (via los primos compartidos),
no qué tan pesados son.

**Lo que cosmo tiene y quarks no: {13, 59, 73, 97, 509}**
SU(2) (13) aparece en cosmología (S8_cmb) pero no en masas de quarks.
La estructura a gran escala del universo requiere la fuerza débil
como axioma, cosa que las masas individuales de quarks no necesitan.

---

## Síntesis de los dos patrones

Los huecos y los puentes cuentan la misma historia desde ángulos distintos.

Los **huecos** dicen: hay combinaciones de axiomas que el corpus PLO
no captura todavía — lugares donde debería haber una constante física
pero no la hemos medido, o donde la tenemos pero su fórmula PLO
aún no está en el corpus.

Los **puentes** dicen: cuando dos sectores aparentemente opuestos
comparten un primo, no es accidental — hay una condición de posibilidad
común que los une ontológicamente antes de que se diferencien en
fenómenos distintos.

La conexión más profunda: **la segunda generación (primo 19)**
aparece en quarks (m_s, m_b), en leptones (m_μ), en mezcla CKM (V_us),
en mezcla PMNS (θ₁₂), y en cosmología (Ω_b, n_s).
El axioma "existen múltiples familias de fermiones" atraviesa
todos los sectores del Modelo Estándar excepto los bosones de gauge y los acoplamientos.
Es la elección axiomática con mayor alcance transversal en el corpus.

---

*ArXe / PLO Research — Febrero 2026*
