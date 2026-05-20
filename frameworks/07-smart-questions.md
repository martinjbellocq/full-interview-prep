# 07 — Smart Questions

> Framework invocado por el Paso 8 del flujo principal (`SKILL.md`).
> Genera 8-10 preguntas que el usuario hace al entrevistador. Función dual:
> demostrar profundidad y preparación + filtrar si el rol cumple los
> criterios no negociables del usuario (de `user-context/`).
> Las preguntas son tan importantes para evaluar si el rol es real como las
> respuestas del usuario lo son para evaluar si el usuario es bueno.

---

## Regla principal: SIEMPRE preguntar algo

> **No preguntar es una mala señal.** "No, no tengo preguntas" / "ya me quedó todo claro" es interpretado por casi todos los entrevistadores como falta de interés, falta de preparación, o ambas. La pregunta "¿tienes preguntas para nosotros?" no es opcional ni decorativa: es parte de la evaluación.
>
> **El piso es preguntar algo. El techo es preguntar bien.** Este framework apunta al techo, pero antes de nada asegurate que el piso esté cubierto.

---

## Preguntas que NO suman (a evitar)

Algunas preguntas son técnicamente legítimas pero **no rinden en el momento de "¿tienes preguntas?"** porque:
- Se contestan con recursos humanos en una etapa posterior, no con el entrevistador de fit.
- Sugieren foco en condiciones laborales antes de demostrar interés en el rol mismo.

A evitar en este momento de la entrevista:

- **Días de vacaciones, licencias, política de teletrabajo, beneficios.** Eso se ve después con RH, no con el hiring manager.
- **Salario y compensación.** Si no se habló antes, hay un momento dedicado a eso (cuando RH lo trae, o cuando preguntan tus expectativas). En "¿tienes preguntas?" se nota mal.
- **"¿Cuándo me avisan?"** sin contexto, especialmente al inicio. Va al final como pregunta de proceso, bien encuadrada.

Estos temas son legítimos en otro momento del proceso. Acá no suman.

---

## Preguntas que SÍ suman (cinco familias)

Las preguntas que rinden en el momento "¿tienes preguntas?" demuestran interés genuino en el rol, la empresa o el entrevistador. Cinco familias generales:

1. **Sobre el rol específico** — qué se espera, qué prioridades tiene, cómo se mide el éxito.
2. **Sobre por qué se abrió esta búsqueda** — pregunta directa al entrevistador, evitando que la skill la infiera (anti-hallucination).
3. **Sobre la empresa y su momento** — algo concreto del DD ejecutivo o de prensa reciente.
4. **Sobre la dinámica con el entrevistador o el equipo** — qué espera él/ella, cómo trabaja el equipo.
5. **Sobre el proceso** — próximos pasos, criterios de decisión.

El framework genera 8-10 preguntas distribuidas en estas familias, calibradas al rol, al entrevistador y a la empresa.

---

## Inputs (de pasos previos)

1. **Contexto del usuario** — `user-context/[nombre].md`. Especialmente la
   sección "Criterios no negociables" y "Lo que necesito de un rol para rendir".
2. **Brief del rol** (output del Paso 2) — incluye la sección "Preguntas que
   la JD deja abiertas" y la sección 3 ("Problemas que esta contratación intenta resolver") con su regla anti-hallucination.
3. **Dossier del entrevistador** (output del Paso 3) — qué le importa, qué
   tipo de pregunta probablemente valore más.
4. **Brief de empresa** (output del Paso 4) y DD ejecutivo — momento estratégico y movimientos recientes que valga la pena referenciar.
5. **Etapa del proceso** (input del Paso 1) — cambia el tipo de preguntas:
   primera ronda vs final round demandan profundidad distinta.

---

## Outputs (estructura del entregable)

### 1. 8-10 preguntas, organizadas por categoría

#### Categoría A — Filtro del rol y criterios del usuario (3-4 preguntas)

**La función más crítica.** Preguntas que verifican si el rol cumple los
criterios no negociables del usuario documentados en su archivo de perfil.

Los criterios varían por usuario y por seniority. Algunos ejemplos:

- **Para roles de gestión:** budget bajo gestión, tamaño y autonomía del equipo, decisiones que toma la posición sin escalación, exposición a leadership senior, autonomía sobre hiring/firing.
- **Para roles técnicos:** ownership del stack, autonomía técnica vs decisiones por comité, relación con producto/negocio, profundidad esperada vs amplitud.
- **Para roles comerciales:** tamaño y composición del pipeline, autonomía sobre estrategia comercial, relación con marketing y operaciones, comisión y estructura de compensación variable.
- **Para roles transversales (HR, finance, legal, etc.):** scope real del rol, exposición a leadership team, autonomía vs proceso de aprobaciones.

Ejemplos de preguntas calibradas al criterio:

- "¿Cuál es el budget bajo gestión y quién aprueba qué nivel de gasto?"
- "¿Qué decisiones toma esta posición sin necesidad de escalación?"
- "¿Cuál es el tamaño y composición actual del equipo, y qué autonomía tiene esta posición sobre cambios en el equipo?"
- "¿Cómo se reportan los resultados de [área del rol], a quién y con qué frecuencia?"
- "¿Cómo es la relación de trabajo entre esta posición y [un stakeholder relevante]? ¿Cuántas interacciones de decisión típicamente hay por mes?"

#### Categoría B — Filtro del momento y razón de la búsqueda (2-3 preguntas)

Preguntas que validan el contexto del rol — incluyendo el "por qué se abrió esta búsqueda" que la skill explícitamente NO infiere (anti-hallucination del `01-role-analysis.md`).

Ejemplos:

- **"¿Qué pasó con la persona que ocupó este rol antes (si hubo)?"** — pregunta clave, casi siempre rinde.
- **"¿Por qué se abrió esta búsqueda específicamente, y por qué ahora?"** — pregunta directa que cubre exactamente lo que la skill no infiere.
- **"¿Cuáles son las 2-3 prioridades de la empresa para los próximos 12 meses, y dónde encaja esta posición específicamente?"**
- **"Si esta búsqueda fuera exitosa, ¿qué diría la persona en este rol que logró en sus primeros 6 meses?"**

#### Categoría C — Profundidad sobre la empresa o industria (1-2 preguntas)

Preguntas que demuestran que el usuario entiende el contexto estratégico
de la empresa. Vienen del DD ejecutivo y del research público — no del chisme interno.

Ejemplos:

- **Sobre algo del earnings call o reporte público:** "En el último reporte mencionaron [tema X] como prioridad. ¿Cómo ve esta posición su rol en esa agenda?"
- **Sobre IA y la industria:** "Hay competidores nuevos entrando al segmento con propuesta IA-first. ¿Cómo está pensando la empresa la respuesta?"
- **Sobre anuncios recientes:** "Anunciaron [movimiento estratégico] hace unos meses. ¿Cómo está impactando eso en la operación del día a día?"
- **Sobre algo que salió en prensa:** "Vi la nota de [publicación] sobre [tema]. ¿Cómo lo están viendo internamente?"

Estas preguntas tienen función dual fuerte: filtran si la empresa tiene
respuesta clara Y demuestran que el usuario hizo research serio.

#### Categoría D — Sobre el entrevistador y la dinámica de trabajo (1-2 preguntas)

Si el entrevistador es alguien con quien el usuario trabajaría directamente,
preguntar sobre cómo es trabajar con él/ella o cómo él/ella ve el rol
desde su lente.

Ejemplos:

- "¿Qué espera específicamente de la relación con esta posición en sus primeros 90 días?"
- "¿Cuál fue el último gran cambio que impulsó en su área y qué aprendizajes le dejó?"
- "¿Cómo describiría su estilo de management y qué tipo de perfil rinde mejor contigo?"
- "Si tuviera que describir el equipo en 3 palabras, ¿cuáles serían y por qué?"

#### Categoría E — Sobre el proceso (1 pregunta)

Una pregunta práctica al final, que cierra y abre próximos pasos.

Ejemplos:

- "¿Cuáles son los próximos pasos en el proceso y qué van a estar evaluando para decidir si avanzamos?"
- "¿Hay algo de mi perfil que les gustaría que profundizara antes de la próxima ronda?"

### 2. Para cada pregunta, anotar:

- **La pregunta** (formulada como la haría el usuario, en su tono).
- **Función:** filtro / demostración / dual (la mayoría son dual).
- **Qué señal busca capturar:** qué información concreta o qué reacción del
  entrevistador sería relevante.
- **Por qué es buena para ESTE entrevistador específico:** conexión con
  algo del dossier (su rol, sus prioridades públicas, su huella).
- **Cómo interpretar respuestas:**
  - **Respuesta verde:** señal de que el rol/empresa cumple expectativa.
  - **Respuesta amarilla:** ambigüedad, vale la pena profundizar.
  - **Respuesta roja:** señal de que el rol/empresa NO cumple criterio
    no negociable.

### 3. Marcado de preguntas core (3-4)

Las 3-4 preguntas que SÍ o SÍ se hacen, sin excepción, aunque la entrevista
se acorte. Son las que cubren los criterios no negociables más críticos del
usuario. Marcadas explícitamente como "CORE — preguntar siempre".

### 4. Calibración explícita

Sección final que documenta:
- Qué criterios no negociables del usuario se filtraron con qué preguntas.
- Qué puntos del DD se buscó validar con qué preguntas.
- Qué preguntas se descartaron y por qué.

---

## Proceso (cómo generar las preguntas)

### A. Mapear criterios no negociables a preguntas

Tomar la sección "Criterios no negociables" del archivo de perfil y, para cada
criterio, generar UNA pregunta que lo filtre. Si un criterio no se puede
filtrar con pregunta directa (ej: cultura ambigua), formular pregunta
indirecta que revele señales.

Esto produce las preguntas de la Categoría A.

### B. Generar preguntas de contexto y razón de la búsqueda

Generar 2-3 preguntas para la Categoría B, incluyendo casi siempre la pregunta directa "por qué se abrió esta posición" (que la skill no infirió en el paso 4 por la regla anti-hallucination — acá el usuario la hace).

### C. Identificar preguntas de profundidad

Del DD de empresa, extraer 1-2 puntos sustantivos basados en evidencia pública (un movimiento reciente declarado, una posición pública del CEO sobre algún tema, un movimiento competitivo visible) y formular pregunta que demuestre que el usuario los notó.

Importante: usar solo información pública. No preguntar sobre "rumores", "lo que se dice", o información sensitive que el entrevistador no haya hecho pública.

Esto produce las preguntas de la Categoría C.

### D. Personalizar al entrevistador

Si el dossier del entrevistador tiene contenido relevante (cargo específico,
trayectoria, posts públicos), formular 1-2 preguntas que solo tienen sentido
hechas a esta persona específicamente.

Esto produce las preguntas de la Categoría D.

### E. Cerrar con pregunta de proceso

Una pregunta práctica para cerrar la entrevista profesionalmente.

Esto produce la pregunta de la Categoría E.

### F. Marcar core y calibrar

Identificar las 3-4 preguntas que cubren los criterios no negociables más
críticos. Marcarlas como CORE.

Documentar la calibración explícita.

---

## Reglas de calidad (no negociables)

- **Especificidad obligatoria.** "¿Cómo es la cultura?" no es smart, es genérica. Cada pregunta debe poder responder a "¿por qué esta pregunta para ESTA persona en ESTA empresa?". Si no puede, reformular.
- **Función dual cuando posible.** Las mejores preguntas filtran Y demuestran. Si una pregunta solo demuestra (sin filtrar nada accionable), reconsiderar.
- **Filtro sin paranoia.** Las preguntas filtro deben ser respetuosas y legítimas, no acusatorias. Probar el rol, no atacar al entrevistador.
- **Cuidado con preguntas border.** Algunas preguntas pueden sonar invasivas, especulativas, o como chisme interno: "¿Por qué se fue X de la empresa?", "¿Qué pasa con el conflicto entre [persona A] y [persona B]?", "¿Es cierto que están perdiendo dinero?". Estas preguntas pueden cruzar el límite incluso si la información circulaba públicamente. El criterio: ¿es algo que el entrevistador puede responder con dignidad? Si tu pregunta lo pone en posición incómoda donde la única salida es no responder o mentir, está mal formulada.
- **Interpretación de respuestas.** El framework debe entregar el "código" para leer las respuestas. Sin eso, el usuario hace las preguntas pero no sabe qué hacer con lo que escucha.
- **Core marcado.** Las preguntas que SÍ o SÍ se hacen deben estar identificadas. Si la entrevista se acorta, son las que se priorizan.
- **No hacer todas.** 8-10 generadas, 3-5 hechas. El framework genera el banco; el usuario elige según el flujo de la entrevista.
- **No sonar a checklist.** Las preguntas deben fluir como conversación ejecutiva, no como interrogatorio. Si una pregunta suena a "ahora me toca preguntar X", reformular.
- **Evitar las preguntas que NO suman** (vacaciones, salario, beneficios) en este momento de la entrevista. Esos temas tienen su momento, no es este.

---

## Notas de implementación

- Si la etapa del proceso es primera ronda, las preguntas de Categoría A
  (filtro del rol) son las más críticas. Si el rol es decorativo o no cumple criterios, mejor saberlo en primera ronda que en final round.
- Si la etapa es final round, las preguntas de Categoría D (sobre la
  dinámica con el entrevistador) cobran más peso porque la decisión de
  trabajar juntos es inminente.
- Si el entrevistador es muy senior con poco tiempo, evitar preguntas que suenan a entry-level y enfocarse en preguntas estratégicas y filtro del rol.
- Si el dossier del entrevistador muestra que valora "candidatos que hacen
  buenas preguntas" (lo declaró públicamente), esto es señal de que las
  preguntas pesan especialmente en su evaluación. Calibrar foco hacia
  Categoría B y C (las que demuestran más).
- Output esperable: 1-2 páginas. Si supera 3, está sobre-trabajado o
  incluyendo preguntas no diferenciadas.
