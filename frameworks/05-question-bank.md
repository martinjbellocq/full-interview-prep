# 05 — Banco de preguntas predichas

> Framework invocado por el Paso 6 del flujo principal (`SKILL.md`).
> Genera el banco de preguntas que el entrevistador probablemente va a hacer,
> con respuesta tipo STAR para las 5-7 más probables, énfasis en impacto,
> profundidad disponible en cada draft, y check final de cobertura de las
> preguntas universales que aparecen en casi cualquier entrevista.

## Misión

Producir tres outputs combinados:

1. **Banco de preguntas predichas** (15-20) organizadas por bloque, con probabilidad estimada.
2. **STAR drafts** para las 5-7 más probables, con foco en impacto y profundidad disponible.
3. **Dos módulos destacados** con preparación específica:
   - Módulo A — la pregunta de apertura (la más común, frecuentemente subestimada).
   - Módulo B — soft questions con segunda intención.

## Inputs (de pasos previos)

1. **Perfil del usuario** — archivo `user-context/[nombre].md`. En particular:
   - Track record con métricas signature.
   - Narrativa de transición actual.
   - Roles target.
   - Patterns bajo presión (para identificar tendencias a evitar en STAR drafts).
   - Fortalezas a amplificar.
2. **Análisis del rol** (Paso 2) — KPIs implícitos, hard requirements, **seniority del rol target** (clave: cambia el calibre de las preguntas).
3. **Dossier del entrevistador** (Paso 3) — estilo, qué probablemente va a probar.
4. **Brief de empresa** (Paso 4) — contexto que va a aparecer en preguntas de "por qué esta empresa".
5. **Output del fit-gap** (Paso 5) — gaps que el banco debe ayudar a defender (el sparring los ataca; el banco los previene).

---

## Pre-flight: check de STAR

Antes de generar los drafts, validar que el usuario conoce el método STAR.

**Acción:** Claude le pregunta al usuario explícitamente:

> "Para preparar las respuestas voy a usar el método STAR (Situación, Tarea, Acción, Resultado). ¿Lo conoces bien o quieres que te lo explique en 30 segundos antes de que te entregue los drafts?"

Si el usuario pide explicación, dar versión condensada:

> **STAR** es un framework para estructurar respuestas a preguntas situacionales o de track record:
> - **Situación** — el contexto. Una o dos líneas. Dónde estabas, qué estaba pasando.
> - **Tarea** — qué tenías que lograr específicamente. El objetivo concreto.
> - **Acción** — qué hiciste tú (no el equipo en abstracto). Decisiones clave, no actividades.
> - **Resultado** — el impacto. Métrica concreta si existe, sí o sí cuantificable de alguna forma.
>
> Regla importante de esta skill: en lugar de seguir el orden literal (S→T→A→R), abrimos con el **resultado/impacto** primero, después contextualizamos. Capta atención en los primeros 10 segundos y compite mejor con la dispersión del entrevistador.

Si el usuario ya lo conoce, saltear y avanzar.

---

## Módulo destacado A — La pregunta de apertura

> Probabilidad: ≈ 100%. Alguna versión de esta pregunta aparece en casi todas las entrevistas, especialmente las primeras rondas. La trampa común es subestimarla y responder improvisando, o confundir las dos variantes principales —que requieren respuestas distintas.

### Dos variantes que se suelen confundir

Lo primero es distinguirlas, porque la respuesta correcta es distinta.

**Variante 1: "Cuéntame de ti" / "Antes de empezar, me gustaría conocerte un poco más" / "Cuéntame tu historia"**

Pregunta abierta y conceptual. El entrevistador NO te está pidiendo recorrido cronológico.

Qué se busca:
- Tu autopresentación sintética: cómo te ves profesionalmente hoy, qué haces ahora, qué te define.
- Capacidad de sintetizar tu trayectoria sin recitarla. La elección de qué condensar señaliza tu autoconciencia.

Frame de respuesta:
- NO recitar empresa por empresa cronológicamente.
- Abrir con algo conceptual: cómo te ves hoy, en qué estás (rol actual o transición actual), qué te define profesionalmente.
- Una o dos referencias a hitos clave de la trayectoria (sin agotarla).
- Cerrar con motivación actual y por qué este rol específicamente.

Tiempo objetivo: 2-3 minutos. Si te extendés más, estás cayendo en recorrido.

**Variante 2: "Walk me through your CV" / "Haz un repaso rápido de tu trayectoria" / "Caminame por tu historia profesional"**

Pregunta cronológica explícita. Acá sí se espera recorrido empresa por empresa.

Qué se busca:
- Estructura y claridad en la narrativa secuencial.
- Qué enfatizás en cada rol. La elección de qué destacar señaliza tus prioridades.
- Coherencia entre los pasos.

Frame de respuesta:
- Recorrido cronológico por rol relevante (no todos, solo los signature).
- Por cada rol: qué fuiste a hacer + qué lograste (con métrica si existe).
- NO incluir proactivamente el "por qué te fuiste" en cada paso. Esa información la traés si el entrevistador la pregunta — sobrecargar el monólogo con razones de cada salida suena defensivo.
- Cerrar con motivación actual y por qué este rol.

Tiempo objetivo: 3-5 minutos máximo.

### Importante: no asumir que el entrevistador va a indagar en las transiciones

Algunos entrevistadores dedican mucho tiempo a profundizar en "¿por qué te fuiste de X?" para leer motivaciones y predecir comportamiento futuro. Otros no lo preguntan en absoluto. **No puedes predecir cuál te toca.**

Tu trabajo es:

- **Tener listas las respuestas para CADA transición** ("por qué te fuiste de [empresa anterior]", "por qué entraste a [empresa siguiente]") por si te preguntan.
- **NO traerlas proactivamente** en un monólogo si nadie te las pidió. Cargar la apertura con razones de cada salida es over-explaining y puede sonar defensivo o ansioso.

### Preparación de transiciones (independiente del monólogo)

Para cada cambio de trabajo de tu CV, llegar con respuesta lista en menos de 30 segundos:

- Por qué te fuiste (versión articulada y honesta, no la sanitizada vacía).
- Por qué elegiste el rol siguiente.
- Qué buscabas en ese momento de tu carrera.

Si te preguntan, sales fluido. Si no te preguntan, no fuerces la conversación hacia ahí.

**Qué leer cuando aparece la pregunta:** si el entrevistador profundiza acá, está leyendo —entre otras cosas— tus motivaciones de cambio (dinero, jefe, ambiente, ascenso, ciclo cerrado, etc.), tu patrón de tenure (rotación corta vs permanencia muy larga sin movimiento), y la coherencia entre lo que buscabas en cada paso y lo que dices buscar ahora. Una buena respuesta de transición es **específica** y **honesta sin amargura**.

### Frame organizador: match mutuo

Independientemente de qué variante te toque, hay un principio que cambia el approach del candidato.

El entrevistador no solo evalúa si tú eres bueno para el rol; también evalúa si el rol va a ser bueno para ti. Si tu motivación principal es liderar equipos grandes y este rol no ofrece eso, te vas a los 6 meses cuando aparezca otra oferta y eso es un fracaso para ambos lados. Si tu motivación es dinero y este rol está debajo de mercado, idem.

Implicación: no estás solicitando un favor. Estás validando un fit en dos direcciones. Tu trabajo no es solo convencerlos. Es darles la información que necesitan para tomar una buena decisión, y tú también necesitás esa decisión.

### Trampas frecuentes a evitar

- **En "cuéntame de ti": caer en recorrido cronológico** cuando la pregunta era abierta. Pierdes la oportunidad de mostrar visión sintética.
- **En "walk me through": recitar el CV sin elección de qué enfatizar.** El entrevistador ya lo leyó. Lo que quieres es interpretarlo.
- **En cualquiera de las dos: monólogo de 10+ minutos** que cubre cada transición y cada razón de cambio. Sobrecarga, suena ansioso o defensivo.
- **Versión sanitizada vacía** si te preguntan por una transición específica. "Buscaba nuevos desafíos" sin sustancia. Mejor agregar contenido honesto: "Me había quedado sin agenda nueva que abrir, la empresa estaba en modo de optimización y yo quería volver a un contexto de construcción" rinde mucho más.
- **Tenures cortos justificados solo con factores externos.** "La empresa quebró", "hubo una reestructuración", "cambió la estrategia". Agregar qué decisión propia hubo dentro de eso.
- **Mal pegado entre trayectoria y "por qué este rol".** Si la trayectoria muestra un patrón y el "por qué este rol" lo rompe, algo no cierra. La conexión tiene que ser orgánica.

### Coherencia interna, no verdad heroica

En general el entrevistador no va a destripar tu versión sanitizada de las salidas. La pregunta no es "tengo la verdad cruda lista". La pregunta es **"mi narrativa se sostiene sin contradecirse"**. Si tus razones para cada cambio se contradicen entre sí, o si claramente estás inflando algo, se nota aunque no te lo digan.

### Drafting personalizado

Claude usa el archivo de perfil (Track record + Narrativa de transición actual + Roles target) para construir:

1. **Draft de variante 1** (cuéntame de ti): respuesta conceptual y sintética, 2-3 minutos.
2. **Draft de variante 2** (walk me through): respuesta cronológica por rol relevante, 3-5 minutos.
3. **Set de respuestas de transición**: una por cada cambio de trabajo en el CV, lista para usarse si el entrevistador profundiza ahí.

**Si en el perfil hay gaps** (transiciones sin razón articulada, tenures cortos sin justificación, motivación actual genérica), Claude los señala como ítems pendientes para que el usuario los complete antes de la entrevista. No improvisar lo que no está documentado.

---

## Módulo destacado B — Soft questions con segunda intención

Tres preguntas que aparecen como casuales pero el entrevistador está leyendo cosas. La trampa común es subestimarlas y responder improvisando.

### B.1 — "¿De qué te sientes orgulloso, en lo profesional?"

**Probabilidad:** alta. Casi todos los entrevistadores hacen esta o una versión equivalente ("¿cuál es tu mayor logro?", "¿qué es lo que más te enorgullece de tu carrera?").

**Qué se busca:**
- Cómo articulás un logro propio sin auto-minimizarlo ni inflarlo.
- Qué tipo de logro eliges (de mayor impacto, más estructural, más complejo, más estratégico). La elección señala tus prioridades.

**Frame:** tener UNO listo antes de la entrevista, calibrado a la narrativa target. Si te estás vendiendo como builder, contá un logro de construcción. Si te estás vendiendo como fixer, contá un turnaround. Si te estás vendiendo como scaler, contá una expansión. No improvisar el primero que se te ocurra: la elección señaliza.

### B.2 — "¿De qué te sientes orgulloso, en lo personal?"

**Probabilidad:** media-alta. Menos universal que la profesional, pero aparece y mucha gente no la tiene preparada. Es donde más candidatos se descolocan.

**Qué se busca:** dimensión personal, no una arenga de "logré ser balanced". Algo concreto y propio.

**Frame:** tener UNO listo. Puede ser:
- Algo realmente personal: rol familiar, logro deportivo, proyecto paralelo, voluntariado, aprendizaje sostenido, recuperación de algo difícil.
- Algo profesional con costado personal: "me siento orgulloso de haber sostenido la disciplina de aprender X durante un período exigente", "haber transicionado de área manteniendo continuidad de aprendizaje".

No tiene que ser épico. Tiene que ser real y articulable.

**Red flag a evitar:** "no se me ocurre nada" o respuesta vaga ("supongo que mi familia"). Eso descoloca al entrevistador y se nota como falta de auto-reflexión.

### B.3 — "¿Qué haces en tu tiempo libre?" / "¿Qué te interesa fuera del trabajo?"

**Probabilidad:** media. Aparece en algunas entrevistas, especialmente en la parte de fit cultural.

**Qué se busca:** una persona con perspectiva más allá del trabajo. **No es un filtro fuerte ni un dealbreaker.** Hay personas excelentes que en un momento de su vida tienen vida personal poco "performable" (etapa de hijos chicos, mudanza, emprendimiento paralelo, salud, cuidados familiares) y sin embargo son profesionales sólidos.

**Frame:**

- Tener algo cierto preparado, no inventar para impresionar.
- **Match interés-empresa puede sumar.** Si alguno de tus intereses tiene conexión natural con la empresa o la industria, mencionarlo aporta. Ejemplos:
  - Postulación a una empresa deportiva → si te gustan los deportes, decilo.
  - Postulación a una casa de bolsa o gestora → si te interesan las inversiones personales, decilo.
  - Postulación a una empresa de viajes → si viajás con frecuencia o estás coleccionando países, decilo.
  - Postulación a una empresa de gastronomía → si cocinás o explorás restaurantes, decilo.
  - Postulación a una editorial → si lees mucho, decilo.

  La conexión genuina rinde. Pero **no inventarla**. No todos los empleados de Adidas son deportistas — el match es plus, no requisito.
- Si no hay match natural, no forzarlo. Una respuesta auténtica funciona mejor que una fabricada.
- Si tu vida actual no tiene hobby fácil de listar, puedes responder honestamente: "Estoy en un momento donde [contexto] absorbe la mayor parte de mi tiempo no laboral. Antes hacía X, espero retomar más adelante". Eso es honesto y razonable.

---

## Bloques del banco de preguntas (15-20 preguntas totales)

> Cada bloque tiene rango de cantidad. La distribución concreta depende del tipo de rol, etapa de proceso y entrevistador. Calibrar.

### Bloque 1 — Track record y experiencia (3-5 preguntas)

Sobre lo que hizo en roles anteriores. Específicas al perfil del usuario y a la JD.

Preguntas típicas:
- "Cuéntame una historia donde tuviste que [X habilidad clave de la JD]."
- "¿Cuál fue tu logro más relevante en [empresa más reciente]?"
- "¿Qué decisión tomaste en [rol] que con la distancia harías distinto?"
- "Si te tuviera que pedir una historia donde [tema relevante para el rol], ¿cuál te viene primero?"

### Bloque 2 — Leadership y construcción de equipos (3-4 preguntas, si el rol implica liderazgo)

Sobre cómo armas, escalás, desarrollás equipos. Calibrar a la seniority del rol target:

- **Team lead / Manager:** preguntas sobre 1-on-1s, feedback, manejo de conflictos en el equipo, primera vez liderando.
- **Director / Head:** preguntas sobre estructurar equipos, hiring de managers, escalar cultura.
- **VP / C-level:** preguntas sobre construcción de organización, sucesión, escalar liderazgo a través de otros líderes.

Preguntas típicas:
- "Cuéntame de una vez que tuviste que dar feedback difícil."
- "¿Cómo manejas a alguien que reporta a ti y no está performando?"
- "Cuéntame un hire que se equivocaron al hacer y qué aprendiste."
- "¿Cómo escalaste cultura cuando el equipo creció?"

**Regla de balance yo-equipo en los drafts:** para roles de liderazgo, los drafts de este bloque deben balancear explícitamente la contribución personal con la del equipo. Anti-patrón a evitar (señalado por entrevistadores experimentados): hablar todo en primera persona ("yo hice esto, yo decidí esto otro, yo logré") cuando claramente es trabajo de equipo. También evitar el extremo opuesto: todo en plural ("el equipo logró") donde no se ve la decisión propia. Frame correcto: **"yo diseñé/decidí/lideré X; el equipo ejecutó Y; mi contribución personal específica fue Z (mentoría / escalación / decisión clave)".**

### Bloque 3 — Technical / domain (2-4 preguntas, si el rol lo requiere)

Específicas a la industria, función o tipo de negocio del rol. Probablemente el entrevistador del dossier va a probar algo de esto si tiene background técnico/de dominio.

Preguntas típicas dependen del rol. Ejemplos por área:

- **Ventas/Comercial:** "¿Cómo estructurás un pipeline?", "¿Cuál es tu approach a forecast?"
- **Producto:** "¿Cómo decidís qué construir y qué priorizar?"
- **HR:** "¿Cómo medís efectividad de programas de desarrollo?"
- **Operaciones/Supply chain:** "¿Cómo balanceaste eficiencia y resiliencia?"
- **Finanzas:** "¿Qué métricas miras para evaluar salud de la unidad?"
- **Tech/Engineering:** preguntas técnicas o de arquitectura específicas al stack.
- **Marketing:** "¿Cómo medís retorno de inversión en awareness vs performance?"

### Bloque 4 — Fit cultural y soft questions (2-3 preguntas)

Incluye las soft questions del Módulo B + otras del estilo:

- "¿Cómo describirías el ambiente de trabajo en el que rendís mejor?"
- "¿Qué tipo de jefe te funciona mejor / peor?"
- "Cuéntame de una vez que estuviste en desacuerdo con tu jefe."
- "Tell me about a difficult coworker." (clásica universal)

### Bloque 5 — Motivación y carrera (3-4 preguntas)

Cubre el "¿por qué?" desde múltiples ángulos. Estas son universales:

- "¿Por qué este rol?" — frame: conexión orgánica con la trayectoria + lo que el rol específicamente ofrece.
- "¿Por qué esta empresa?" — frame: 2-3 datos específicos del DD ejecutivo con interpretación propia. NO leer Wikipedia el día anterior; se nota.
- "¿Por qué te vas / te fuiste de tu trabajo actual o anterior?" — frame: honestidad sin amargura, focus en lo que buscas más que en lo que escapás.
- "¿Dónde te ves en 5 años?" — frame: específico sin ser rígido. Conectar con la trayectoria implícita del rol y la empresa, no recitar un plan de vida.

### Bloque 6 — Situacionales / hipotéticas (1-2 preguntas)

"¿Qué harías si…?". Probables si el entrevistador es operador/founder, menos probables si es corporate.

Preguntas típicas:
- "¿Qué harías en tus primeros 90 días en este rol?"
- "Si [escenario específico del negocio], ¿cómo lo manejarías?"

### Bloque 7 — Compensación y proceso (1 pregunta, opcional)

- "¿Cuáles son tus expectativas salariales?" — frame: rango realista calibrado al mercado y al rol; si la JD no lo declaró, preguntar antes el rango de la empresa o pedir rango orientativo. Evitar tirar un número específico antes de tener señal del rango ofrecido.

### Bloque 8 — Cierre

- "¿Tenés preguntas para nosotros?" — probabilidad ≈ 100%. Detalle completo en `frameworks/07-smart-questions.md`. **Importante:** no preparar preguntas o decir "no, no tengo preguntas" es leído como falta de interés genuino. La preparación de las preguntas para el entrevistador es tan importante como la preparación de las respuestas.

---

## Construcción del banco (proceso)

### A. Calibrar al seniority del rol target

El seniority del rol target (validado en el Paso 2 del flujo principal) cambia el calibre de las preguntas. Un mismo tema se prueba distinto en distintos niveles. Ejemplos:

- **Tema: "manejaste conflicto en el equipo".**
  - Team lead: "Cuéntame una vez que tuviste que mediar un conflicto entre dos personas de tu equipo."
  - Director: "Cuéntame un conflicto entre dos managers que reportaban a ti y cómo lo manejaste."
  - VP/C-level: "Cuéntame una vez que tuviste que intervenir en una dinámica disfuncional del leadership team."

- **Tema: "tomaste una decisión difícil".**
  - Team lead: decisión sobre prioridad operativa o reasignación de un miembro del equipo.
  - Director: decisión sobre estructura, hiring/firing de un manager, o pivot de iniciativa.
  - VP/C-level: decisión sobre estrategia, sunset de unidad de negocio, decisión de board.

Ajustar el banco a este calibre. No usar preguntas que asumen scope mayor del que tiene el rol.

### B. Identificar bloques relevantes

No todos los bloques aplican a todas las entrevistas:
- Rol sin gestión de personas → recortar Bloque 2.
- Entrevista de filtro inicial con recruiter → priorizar Bloques 1, 5, 7. Menos peso en 3 y 6.
- Entrevista técnica con peer/manager → priorizar Bloques 3 y 6.
- Entrevista de fit con CEO o board → priorizar Bloques 4, 5 y 8. Menos peso en 3.

### C. Generar preguntas específicas

Para cada bloque, generar 2-5 preguntas específicas al rol/empresa/entrevistador. NO usar preguntas genéricas tipo "cuéntame de un fracaso". Cada pregunta debe estar enraizada en el contexto del rol o en el track record del usuario.

Ejemplos de especificidad:

- Mal: "Cuéntame de un fracaso."
- Bien: "El lanzamiento del producto X en el mercado Y coincidió con un cambio de contexto importante. Si pudieras hacer ese lanzamiento de nuevo, ¿qué harías distinto?"

- Mal: "¿Cuál fue tu mayor logro?"
- Bien: "Construiste un equipo de [función] de N personas en varios mercados. ¿Cuál fue la decisión de hiring que más impacto tuvo en hacer ese equipo funcionar?"

### D. Asignar probabilidad

Para cada pregunta, evaluar:

- ¿Esta pregunta aparece típicamente en este tipo de rol/etapa? (peso: 40%)
- ¿El entrevistador del dossier probablemente va a probar esta área? (peso: 30%)
- ¿Esta pregunta toca un gap del fit-gap o una fortaleza clave del perfil? (peso: 30%)

Asignar: Alta (>70%), Media (40-70%), Baja (<40%).

### E. Identificar top 5-7 para STAR drafts

Las preguntas con probabilidad Alta + las que tocan los gaps más relevantes del fit-gap. La pregunta del Módulo A (apertura) **siempre va al top 5-7** por su probabilidad ≈100%.

### F. Construir STAR drafts

Estructura del draft:

1. **Apertura con impacto/resultado** (1 línea). Ejemplo: "Crecimos la unidad X% en N meses. El contexto fue…"
2. **Contexto** (2-3 líneas). Situación + tarea, breves.
3. **Acción** (3-5 líneas). Decisiones específicas que tomó el usuario, no actividades. Si es bloque de leadership, balance yo-equipo explícito.
4. **Resultado** (1-2 líneas). Métrica concreta + por qué importó.
5. **Profundidad disponible** (no se dice, se prepara). 2-3 niveles de detalle disponibles para repreguntas tipo "¿cómo lo hiciste?", "¿qué obstáculos atravesaste?", "¿con quién?", "¿qué métrica secundaria sostiene esa principal?".

### G. Check de profundidad disponible (regla crítica)

**Para cada draft, validar que el usuario puede sostener 2-3 niveles de profundidad sobre el logro.** Si dices "construí equipo de N personas", tienes que tener listo:

- Qué roles contrataste, en qué orden, por qué.
- Cuáles fueron tus criterios de hiring.
- Qué errores cometiste en el proceso.
- Qué métricas usaste para evaluar performance del equipo.
- Cómo decidiste quién se quedaba y quién no si hubo rotación.

Los entrevistadores experimentados detectan inflación profundizando con repreguntas. Una mentira superficial no se sostiene con detalles. Si tú no puedes sostener detalles sobre algún punto del draft, ese punto está inflado y hay que reformularlo (o sacarlo).

En el output entregado al usuario, incluir para cada draft un párrafo de **"Profundidad esperable"**: las repreguntas más probables que el entrevistador va a hacer si profundiza, y los datos que el usuario debe tener listos para sostenerlas.

---

## Check de cobertura: preguntas universales

Antes de cerrar el banco, validar que las 12 preguntas universales (las que aparecen en casi cualquier entrevista) están cubiertas o tienen su equivalente local. Si alguna no está cubierta por el banco generado en los pasos anteriores, agregarla.

Lista (en español, adaptable):

1. Cuéntame de ti (Módulo A — siempre incluida).
2. ¿Por qué este rol?
3. ¿Por qué esta empresa?
4. ¿Cuál es tu mayor fortaleza?
5. ¿Cuál es tu mayor debilidad?
6. Cuéntame una vez que lideraste un equipo.
7. Cuéntame una vez que fallaste.
8. Cuéntame de un compañero/colega difícil.
9. ¿Por qué te vas de tu trabajo actual?
10. ¿Dónde te ves en 5 años?
11. ¿Cuáles son tus expectativas salariales?
12. ¿Tenés preguntas para nosotros?

**Acción:** después de generar el banco con los bloques, recorrer la lista. Para cada una, verificar si está cubierta literal o por equivalente:

- Si **sí** está cubierta → marcar como cubierta.
- Si **no** está cubierta → agregar al banco con probabilidad estimada según el tipo de entrevista.

Esta cobertura es **piso mínimo**, no objetivo. Idealmente el banco generado por bloques ya cubre la mayoría sin redundar.

---

## Reglas de calidad

- **Especificidad obligatoria.** Preguntas genéricas tipo "hábleme de usted" sin contexto no van. Cada pregunta debe estar enraizada en el rol, la empresa, el entrevistador, o el perfil del usuario.
- **Calibrado al seniority del rol target.** No usar preguntas que asumen scope mayor del que el rol tiene. Si el rol es Team Lead con 5 reportes, no preguntar sobre "estructurar una organización de 200 personas".
- **Drafts con apertura de impacto.** Ningún draft abre con "En 2018 entré a [empresa]…". Abre con resultado/impacto.
- **Balance yo-equipo en bloque de leadership.** Drafts del Bloque 2 deben mostrar contribución personal + del equipo de forma explícita.
- **Profundidad disponible.** Cada draft tiene su sección de "Profundidad esperable" con 2-3 niveles de detalle preparados para repreguntas.
- **Coherencia con el perfil.** Cada draft conecta con al menos una fortaleza documentada en el archivo del usuario. Si no se puede conectar, está improvisado.
- **STAR drafts como estructuras, no scripts.** Si un draft se puede recitar de memoria, está sobre-trabajado. La idea es que el usuario internalice estructura + datos clave, no memorice palabras.
- **Cobertura de las 12 universales.** Validada al final como check, no como objetivo.
- **Idioma consistente** con el archivo de perfil del usuario.

---

## Notas de implementación

- Si el archivo de perfil tiene gaps significativos (transiciones sin razones articuladas, métricas vagas, motivaciones genéricas), declararlo en el output del banco. Mejor declarar el gap que generar drafts inflados.
- Si la sección "Patterns bajo presión" del archivo de perfil incluye "presentación cronológica", reforzar en cada draft que la apertura debe ser de impacto, nunca de contexto temporal.
- Si el perfil incluye "auto-minimización" como pattern, reforzar en drafts del bloque B (preguntas de orgullo) que la respuesta debe defender el logro sin descalificarlo.
- Output esperable del framework: 3-5 páginas. Si supera 6, está sobre-trabajado para una sola entrevista.
