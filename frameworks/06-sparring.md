# 06 — Modo Sparring

> Framework invocado por el Paso 7 del flujo principal (`SKILL.md`).
> El diferenciador de la skill. Toma los gaps identificados en el fit-gap y
> produce ataques duros con kit de defensa completo, calibrados al estilo del
> entrevistador y a los patterns del usuario bajo presión.

## Qué es el sparring (y qué NO es)

- **NO es modo coach amable.** No se suaviza, no se da feedback motivacional.
- **NO es lista de preguntas frecuentes.** No son las "10 preguntas duras de entrevistas". Son ataques específicos al fit real.
- **NO es debate teórico.** No son preguntas abstractas sin conexión a weak spots reales.
- **SÍ es entrevistador hostil pero realista**, calibrado al estilo del entrevistador específico y a los patterns concretos del usuario bajo presión, con frame de defensa entregado para cada ataque.

Como en boxeo: simulación de combate con un sparring que sabe pegar fuerte y conoce las debilidades del que entrena. El objetivo es que el día de la pelea real ya hayas comido los golpes que importan, en un entorno donde puedes iterar.

---

## Inputs (de pasos previos)

1. **Perfil del usuario** — archivo `user-context/[nombre].md`. Especialmente:
   - Sección "Patterns bajo presión" — base para identificar trampas probables.
   - Sección "Fortalezas a amplificar" — base para los ángulos correctos.
2. **Output del fit-gap** (Paso 5) — los 5 gaps con tipo, probabilidad, severidad,
   hipótesis de cómo se prueban.
3. **Dossier del entrevistador** (Paso 3) — estilo probable, qué le importa, qué va
   a probar.
4. **Modo del sparring** — `realista` (default) o `hard` (opt-in explícito).

Si falta cualquiera de estos, no avanzar. Volver a pedir o ejecutar el paso correspondiente.

---

## Outputs (estructura del entregable)

### 1. Declaración de modo

Una línea al inicio que declara el modo:
- "Modo realista: ataques que el entrevistador del dossier probablemente hará."
- "Modo hard: ataques que un entrevistador muy duro haría, no necesariamente el real."

### 2. 5-7 ataques estructurados

Rankeados por severidad × probabilidad (los más críticos primero).

Si el fit-gap tiene menos de 5 gaps reales, generar solo los ataques correspondientes
y declararlo: "Solo se identificaron X gaps con probabilidad alta o media; no se
inflaron ataques adicionales para llegar a 5."

Para cada ataque, producir las 5 partes del kit:

#### Parte 1 — La pregunta

Formulada exactamente como la haría el entrevistador del dossier. Estilo calibrado:

- Si el dossier muestra **directo/exigente**: pregunta directa, frontal, sin diplomacia, posiblemente provocadora. Común en founders, operadores con background comercial fuerte, líderes turnaround.
- Si muestra **corporate ejecutivo**: pregunta pulida pero punzante, con
  encuadre formal, posiblemente envuelta en contexto.
- Si muestra **técnico/operador**: pregunta con datos específicos, números,
  retos cuantitativos.
- Si muestra **estilo coaching/desarrollo**: pregunta abierta que invita a
  reflexión, pero con segunda intención evaluativa.
- Si no hay suficiente huella del entrevistador: declararlo y usar default
  "ejecutivo experimentado exigente" (estilo promedio de un líder senior con experiencia entrevistando).

La pregunta debe ser específica al gap, no genérica. "Hábleme de un fracaso" no califica como sparring; "Tu experiencia es principalmente en empresas grandes con procesos consolidados — este rol es en una empresa de N personas donde mucho está por construir. ¿Cómo manejas la falta de estructura?" sí lo es.

#### Parte 2 — Por qué te la van a hacer

Dos líneas:
- **Qué gap detectó** (referenciando el fit-gap).
- **Por qué este entrevistador específico va a probar acá** (referenciando el dossier).

#### Parte 3 — La trampa

Esta es la sección más importante del framework. Es lo que nadie más hace.

La trampa se construye **cruzando el tipo de gap × los patterns del usuario bajo
presión** (del archivo de perfil). Para identificarla:

1. Mirar el tipo del gap (knowledge / experience / identity / cultural / scope).
2. Mirar los patterns del usuario en el archivo de perfil.
3. Inferir cuál es la respuesta defensiva o evasiva más probable bajo presión.

Ejemplos del cruce (genéricos, NO ejemplos cerrados):

- **Knowledge gap + "duda bajo presión"** → trampa: hedgear con calificadores
  ("creo que", "depende", "habría que ver"), sonar menos decisivo de lo que es.
- **Experience gap + "tendencia a evitar conflicto"** → trampa: conceder
  demasiado rápido ("tienes razón, no lo manejé"), evadirse, o dar respuesta
  diplomática que no defiende el track record.
- **Identity gap + "se presenta naturalmente en el rol anterior"** → trampa: cuando el entrevistador tira el ancla del rol anterior, aceptarla en lugar de sostener el frame target. Por ejemplo: candidato que se está repositionando de un rol funcional a un rol de management transversal, y bajo presión vuelve a hablar como especialista en su función original.
- **Identity gap + "presentación cronológica"** → trampa: contar la historia desde el contexto temporal, perdiendo el impacto, dándole tiempo al entrevistador de formar su propia conclusión antes de la tuya.
- **Cultural gap + "más racional que carismático"** → trampa: respuesta seca y
  analítica donde el entrevistador esperaba storytelling emocional o vision pitch.
- **Scope gap + "delegación mejorable"** → trampa: mostrar exceso de
  involucramiento en el detalle, lo cual confirma el gap en vez de defenderlo.
- **Auto-minimización** (pattern muy común) → trampa: descalificar el logro
  antes de que el entrevistador lo haga ("igualmente cualquiera lo hubiera hecho").

Si los patterns del usuario no permiten identificar una trampa clara para un gap
específico, declararlo y describir la trampa genérica del tipo de gap.

#### Parte 4 — El ángulo correcto

Frame mental, **no script literal**. La diferencia es crítica:

- Script (mal): "Decir esto: 'En realidad mi rol fue más amplio, manejé también X e Y'..."
- Frame (bien): "Reframear el alcance del rol previo. Conceder que el título funcional era X pero defender que la responsabilidad real incluía dimensiones adicionales relevantes a este rol. Traer una métrica concreta del track record que lo demuestre. No entrar a defender línea por línea."

Por tipo de gap, los frames típicos son:

- **Knowledge gap** → "lo aprendí cuando..." (mostrar adaptabilidad pasada) o
  "tengo análogo transferible" (traer un caso equivalente).
- **Experience gap** → framing transferible: la habilidad subyacente es la misma,
  la métrica equivalente es esta, lo que cambia es el contexto. NO pedir disculpas
  por no haber estado ahí.
- **Identity gap** → reframing narrativo: sostener el frame propio incluso cuando
  el entrevistador tira el ancla del frame contrario. Conceder superficie, defender
  estructura.
- **Cultural gap** → demostrar fluidez bicultural, mostrar curiosidad genuina,
  no defenderse de la diferencia.
- **Scope gap** → métricas relativas, complejidad en otra dimensión, argumento de
  transferibilidad sin minimizar lo hecho.

El frame debe usar **explícitamente** una o más fortalezas de la sección "Fortalezas
a amplificar" del archivo de perfil. Si el frame no se conecta con una fortaleza
documentada, está improvisado.

#### Parte 5 — Pregunta de práctica

Versión suavizada de la pregunta original, para que el usuario la articule en voz
alta antes del drilling. Misma esencia, menos punzante. Sirve como warm-up.

Ejemplo (genérico):
- Pregunta original: "Tu experiencia es principalmente en empresas grandes con procesos consolidados — este rol es en una empresa de N personas donde mucho está por construir. ¿Cómo manejas la falta de estructura?"
- Pregunta de práctica: "Cuéntame cómo te adaptaste cuando entraste a un contexto con menos estructura de la que estabas acostumbrado."

### 3. Cierre con dos ofertas

Después de los 5-7 ataques, cerrar con:

**Oferta A — Drilling interactivo:**

> ¿Quieres practicar las 3 más duras ahora? Te lanzo la pregunta, respondes
> (en voz alta o escrita), te critico la respuesta, iteramos hasta que el
> ángulo correcto te salga sin pensarlo.

**Oferta B — Hard mode** (solo si el modo del output fue realista):

> ¿Quieres ver también la versión hard mode de los top 3 ataques? Esas son las
> preguntas que un entrevistador "muy duro" haría — no necesariamente las que
> el entrevistador real va a hacer, pero te preparan para el peor caso.

Si el modo ya fue hard, no ofrecer la oferta B.

---

## Proceso (cómo hacer la generación)

Ejecutar en este orden:

### A. Determinar modo

Default: realista. Solo cambiar a hard si el usuario lo pidió explícitamente
(con "hard mode", "modo duro", "peor caso", "ataque máximo" o similar).

### B. Seleccionar gaps a atacar

Tomar los gaps del fit-gap, ordenados por severidad × probabilidad. Atacar los
top 5-7. Si hay menos de 5 gaps reales, atacar solo los que haya y declararlo.

NO incluir preguntas generales (motivación, fit cultural global, "cuéntame de ti").
Esas son del banco de preguntas predichas (paso 6, framework 05). El sparring
es exclusivamente para defender gaps específicos.

### C. Inferir estilo del entrevistador

Del dossier del paso 3, extraer:
- Estilo de comunicación probable (directo / pulido / técnico / coaching).
- Áreas que probablemente le importan más (las que volverá a probar).
- Cualquier tema personal o señal específica del entrevistador que cambie el
  tono de las preguntas.

Si la huella del entrevistador es escasa, declararlo en la declaración de modo y
usar default "ejecutivo experimentado exigente".

### D. Para cada gap, construir el ataque

Ejecutar las 5 partes del kit en orden:
1. Formular la pregunta en estilo del entrevistador, específica al gap.
2. Escribir las 2 líneas de "por qué te la van a hacer".
3. Construir la trampa cruzando tipo de gap × patterns del usuario.
4. Formular el ángulo correcto como frame mental, conectando con fortalezas
   documentadas.
5. Generar la pregunta de práctica suavizada.

### E. Rankear el output

Ordenar los ataques por severidad × probabilidad. Los deal-breakers de probabilidad
alta van primero. Los matices de probabilidad media van al final.

### F. Producir cierre

Agregar las dos ofertas (drilling y, si aplica, hard mode).

---

## Reglas de calidad (no negociables)

- **Sparring real, no suavizado.** Si un ataque resulta tibio en el draft,
  reformularlo más punzante. La regla del SKILL.md "no suavizar para hacer sentir
  bien" aplica con doble fuerza acá.
- **En estilo del entrevistador específico, no genérico.** Cada pregunta debe
  sentirse formulada por la persona específica del dossier, no por un entrevistador
  promedio.
- **Trampa basada en patterns concretos del usuario.** Cruzar tipo de gap × patterns
  del usuario es obligatorio. No hay trampa "default" — si no se puede cruzar bien,
  declararlo.
- **Ángulos como frames, no scripts.** Si una sección "ángulo correcto" se lee como
  una respuesta a memorizar, está mal escrita. Reformular como frame mental
  transferible a múltiples versiones de la pregunta.
- **Conectar frames con fortalezas documentadas.** Cada ángulo correcto debe
  apoyarse en al menos una fortaleza específica del archivo del usuario.
- **Solo gaps, no preguntas generales.** Si una pregunta no ataca un gap del
  fit-gap, no entra al sparring. Va al banco de preguntas predichas.
- **Especificidad obligatoria.** "Te van a preguntar sobre liderazgo" no califica
  como sparring. La pregunta tiene que aterrizar un gap específico con detalles
  del rol target y del track record.

---

## Drilling interactivo (modo runtime, post-output)

Cuando el usuario acepta la oferta A, entrar en modo conversacional. Funcionamiento:

1. Lanzar la primera pregunta del top 3 (la más dura del output).
2. Esperar respuesta del usuario (voz transcrita o escrita).
3. Criticar la respuesta usando estos criterios:
   - **Claridad:** ¿se entendió en una pasada o el entrevistador se pierde?
   - **Frame correcto:** ¿usó el ángulo o cayó en la trampa?
   - **Métricas:** ¿trajo número o anécdota concreta o se quedó en abstracto?
   - **Pattern bajo presión:** ¿cayó en alguno de los patterns del usuario?
     (hedgeo, presentación cronológica, evasión de conflicto, auto-minimización, etc.)
4. Si la respuesta tuvo problemas, decirlo directo. No suavizar.
5. Pedir una segunda toma. Iterar 2-4 rondas hasta que el ángulo correcto le
   salga limpio.
6. Pasar a la siguiente pregunta del top 3.

El drilling es inherentemente duro. La crítica debe ser específica y punzante,
no diplomática. La utilidad del drilling viene de que el usuario practique
articular bajo presión real.

---

## Notas de implementación

- Si el dossier del entrevistador está muy escaso (sin huella pública), el modo
  hard se vuelve más relevante porque la incertidumbre sobre el estilo aumenta el
  rango de preguntas posibles.
- Si los patterns bajo presión del usuario son muy específicos, las trampas serán
  muy precisas. Si los patterns son genéricos, las trampas serán más amplias y
  menos accionables. La calidad del sparring está limitada por la calidad del
  archivo del usuario.
- La sección "Patterns bajo presión" del archivo del usuario es la que da más
  filo al sparring. Si esa sección queda débil o desactualizada, este framework
  pierde precisión rápidamente.
- Output esperable: 2-3 páginas. Si supera 4, está sobre-trabajado.
