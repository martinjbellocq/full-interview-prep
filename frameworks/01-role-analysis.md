# 01 — Role Analysis

> Framework invocado por el Paso 2 del flujo principal (`SKILL.md`).
> Parsea la JD y el contexto disponible para producir un brief del rol que
> identifica qué buscan REALMENTE (no solo lo que dice la spec) y por qué
> existe esta búsqueda.
> Este brief alimenta directamente al fit-gap (Paso 5), al banco de preguntas
> (Paso 6) y a las smart questions (Paso 8).

---

## Inputs

1. **JD** — link o texto pegado.
2. **Empresa** — nombre y mercado/región/unidad relevante (input del Paso 1).
3. **Etapa del proceso** — input del Paso 1.
4. **Acceso a web search** — para contextualizar el rol con la industria si es
   necesario.

Si la JD no está disponible (solo hay título de rol), declararlo y trabajar con
hipótesis explícitas. La calidad del output va a ser proporcionalmente menor.

---

## Outputs (estructura del brief del rol)

### 0. Seniority del rol target (paso obligatorio, antes del análisis)

> Este es el primer paso. Cambia el calibre de todo lo que viene después (KPIs, hard requirements, hipótesis, preguntas, sparring). Sin esto definido, el resto del análisis sale mal calibrado.

**Inferir desde la JD:**

- **Título del rol** — Team Lead / Manager / Senior Manager / Director / Head / VP / SVP / Chief / GM / Country Manager.
- **Scope de gestión declarado** — número de reportes directos, número total bajo gestión, presupuesto.
- **Reporting line** — a quién reporta.
- **Verbos usados en responsabilidades** — "ejecutar" / "coordinar" (más operativo) vs "definir estrategia" / "dirigir" (más senior).
- **Rango salarial si aparece** — orientativo de mercado para la región.
- **Lenguaje aspiracional** — JDs muy "visionary" sugieren rol más estratégico; JDs muy "hands-on" sugieren rol más ejecutor.

**Categorizar en una de estas bandas:**

- **Team Lead / Líder de equipo** — primer nivel de gestión. 3-8 reportes. Foco en ejecución del equipo, mentoría, coordinación.
- **Manager / Gerente** — gestión consolidada. 8-20 reportes (puede incluir team leads debajo). Foco en operación del área + alguna participación estratégica.
- **Senior Manager / Director** — gestión de managers. 20-50 personas bajo estructura. Foco en estrategia de área + ejecución a través de managers.
- **Head / VP** — gestión de directors. 50-200 personas. Foco en estrategia + escalar liderazgo + alineamiento cross-funcional.
- **C-level / SVP / Chief / GM / Country Manager** — gestión de la función completa. Foco en estrategia organizacional + board / leadership team + decisiones de capital.

**Validar con el usuario antes de seguir:**

Después de inferir, Claude le pregunta al usuario:

> "De la JD inferí que este rol está en banda **[X]** ([criterio que lo sugiere]). ¿Es así? Y tú hoy, ¿en qué banda estás? Esto me ayuda a calibrar las preguntas, el fit-gap y el sparring."

El usuario puede confirmar, corregir, o aclarar (ej. "el título dice Manager pero por el scope es más Director", o "técnicamente soy Director pero busco lateralizarme a un Head"). Integrar la respuesta.

**Por qué importa la banda del usuario y la banda del rol:** las dinámicas son muy distintas según si el candidato está:

- **Lateralizándose** (misma banda en empresa nueva) — el foco va a estar en por qué cambia + fit cultural.
- **Subiendo un nivel** (banda superior en empresa nueva) — el foco va a estar en si tiene capacidad de scope mayor, evidencia transferible, frame de "estoy listo para el siguiente paso".
- **Bajando** (banda inferior) — el foco va a estar en por qué da un paso atrás (downside lateral, búsqueda de aprendizaje, contexto personal). Hay que defender la motivación.
- **Cambiando de función** además de nivel — combinación de los desafíos anteriores.

Esto alimenta directamente el fit-gap (Paso 5) y las hipótesis del modo sparring (Paso 7).

---

### 1. Resumen ejecutivo del rol (3 líneas)

- **Una línea de tesis:** qué problema central va a resolver la persona en este
  rol, según la lectura entre líneas de la JD.
- **Una línea sobre el centro de gravedad:** dónde va a pasar la mayoría del
  tiempo (ejecución, estrategia, equipo, stakeholders, etc.).
- **Una línea sobre el grado de poder:** cuánto ownership/autonomía parece
  tener vs cuánto es coordinación.

Ejemplos por nivel de seniority:

> **Team Lead** — "Probablemente buscan a alguien que pueda manejar un equipo pequeño (4-6 personas) de [función] en un contexto de crecimiento. Centro de gravedad: ejecución directa con mentoría. Poder declarado: limitado a decisiones operativas, alineamiento estratégico con el manager."

> **Manager / Director** — "Buscan a alguien que consolide la operación de [área] tras un período de crecimiento desordenado. Centro de gravedad: estructurar procesos + manejar equipo de 10-15 personas. Poder real: medio (depende de cuánto stakeholder management se requiera con áreas adyacentes)."

> **VP / Head** — "Buscan reorganizar [función] regional tras una rotación en el liderazgo. Centro de gravedad: definir estrategia + escalar equipo + alinear con otras unidades. Poder declarado alto; poder real depende de la relación con el CEO/COO y de cuánto budget tenga autonomía sobre."

### 2. KPIs implícitos del rol

Qué van a medir REALMENTE (no necesariamente lo que dice la JD). Para cada uno:

- **KPI:** descripción específica.
- **Por qué probablemente importa:** inferencia desde la JD, la empresa y la
  industria.
- **Horizonte temporal probable:** primer cuarter, primer año, primeros 2 años.

Mínimo 3, máximo 6 KPIs. Si la JD es muy vaga, declarar la limitación y
trabajar con hipótesis de industria.

### 3. Problemas que esta contratación intenta resolver

> **Regla anti-hallucination.** Esta sección solo se llena si hay **evidencia pública concreta** sobre el por qué de la búsqueda. NO inventar la razón. Para casi cualquier rol hay decenas de razones posibles ("buscan reconstruir el equipo", "están reaccionando a un competidor", "están institucionalizando una capacidad") y elegir una sin evidencia es alucinar.

**Evidencia pública aceptable:**

- Post explícito del hiring manager o de leadership de la empresa sobre la búsqueda o el por qué.
- Noticia o comunicado sobre el contexto que motiva la contratación (expansión anunciada, salida documentada del predecesor, reestructuración pública).
- Earnings call o reporte donde se menciona la inversión en esta área.
- Cambios visibles en el equipo a través de LinkedIn (varias salidas recientes en el área, hires anteriores fallidos).

Si hay evidencia pública concreta, listar las hipótesis con su evidencia explícita. Si NO hay evidencia, dejar la sección como:

> "Razón de la búsqueda: no encontrada en fuentes públicas. Recomendado preguntar al entrevistador (ver `07-smart-questions.md`)."

**Pregunta opcional al usuario:** independientemente del research público, Claude le pregunta al usuario:

> "¿Sabes tú por qué se abrió esta posición? (Si alguien te contó, si te lo dijeron en una conversación previa, si conoces a alguien que estuvo en el rol, etc.) Si no sabes, está OK — preguntamos al entrevistador."

Si el usuario aporta info, integrarla acá explícitamente declarando la fuente ("según info que el usuario aporta de [contexto]"). Si no, la sección queda como "no encontrada".

**Esta sección NO se infiere. Se documenta o se declara abierta.**

### 4. Hard requirements vs nice-to-haves (separados)

#### Hard requirements

Lista de capacidades/experiencias INDISPENSABLES. Identificarlos por:
- Repetición en la JD (si aparece varias veces, es hard).
- Lenguaje específico ("must have", "required", "5+ years of experience in X").
- Convención de industria (ciertos requisitos son obvios para el rol aunque no
  estén marcados explícitamente).

#### Nice-to-haves

Lista de capacidades/experiencias deseables pero no eliminatorias.
Identificarlos por:
- Lenguaje suave ("preferred", "bonus", "ideally").
- Aparición única o tangencial.
- Cosas que la empresa quizás está pidiendo de aspiración más que de
  necesidad real.

### 5. Señales de cultura (lectura del lenguaje)

El lenguaje de la JD revela cultura. Identificar señales:

- **Tono general:** corporativo, startup, técnico, casual, militante.
- **Énfasis repetidos:** si "fast-paced" aparece 5 veces, es señal.
- **Lo que NO se menciona:** la ausencia de menciones al equipo, a la cultura,
  a la diversidad, etc., es información.
- **Estilo de escritura:** las JDs escritas por humanos vs por templates/AI
  revelan cuánto cuidado puso la empresa.
- **Promesas explícitas vs implícitas:** beneficios mencionados, ambiente
  prometido, expectativas declaradas.

Producir 3-5 señales con evidencia (qué texto específico la sugiere).

### 6. Red flags del rol

Detectar señales que vale la pena cuestionar antes de avanzar. Ejemplos típicos:

- Rol declarado de ownership pero sin equipo o presupuesto descritos.
- JD que enumera demasiados hard skills (probablemente la empresa no tiene
  claro qué busca).
- Mención a "high-performing environment" sin descripción de qué significa
  (puede ser código para hours culture).
- Mismo rol publicado meses antes (rotación o no llenan).
- Discrepancia entre el seniority del título y los requisitos (ej: "Director"
  pero pide ejecución muy táctica).
- Fortísimo énfasis en una capacidad específica (sugiere que el predecesor
  fracasó por ahí).
- Mención a "hands-on" en roles seniority alta (puede sugerir falta de equipo
  real).

Si no hay red flags, declarar: "JD limpia, sin red flags evidentes."

### 7. Preguntas que la JD deja abiertas

Lista de 5-8 preguntas críticas que la JD no responde y que vale la pena
hacer al entrevistador. Estas alimentan directamente al framework
`07-smart-questions.md`. Ejemplos típicos:

- ¿Quién ocupó el rol antes y qué pasó?
- ¿Cuál es el budget real bajo gestión?
- ¿Cómo se decide la estrategia de [X área del rol]?
- ¿Cuál es la relación de reporting real (no solo el organigrama)?
- ¿Qué se espera concretamente en los primeros 6 meses?
- ¿Cómo se miden los resultados del rol y a quién se reportan?

---

## Proceso (cómo hacer el análisis)

Ejecutar en este orden:

### A. Lectura literal

Leer la JD completa, identificar:
- Título exacto del rol.
- Reporting line declarado.
- Equipo bajo gestión declarado.
- Lista de responsabilidades.
- Lista de requisitos.
- Beneficios o "what we offer".
- Información sobre la empresa al final.

### B. Lectura entre líneas

Releer buscando:
- Qué se repite (énfasis).
- Qué falta (silencios).
- Qué tono se usa (formal, urgente, aspiracional).
- Qué contradicciones hay entre secciones.

### C. Cruzar con contexto de empresa

Si el DD de empresa está disponible, cruzar:
- ¿Hay rotación reciente en este área?
- ¿La empresa está en momento de crecimiento, contracción, pivote?
- ¿Qué problemas estratégicos sugiere el DD que pueden conectar con esta
  contratación?

Esto refina las hipótesis del por qué de la búsqueda (sección 3 del output).

### D. Cruzar con etapa del proceso

Una primera ronda evalúa fit básico; una final round evalúa decisión de
fondo. Las prioridades del entrevistador y la profundidad esperada del
candidato cambian según etapa.

### E. Construir las 7 secciones del output

En orden: resumen ejecutivo → KPIs implícitos → problemas a resolver → hard
vs nice → señales de cultura → red flags → preguntas abiertas.

### F. Verificación de calidad

Antes de cerrar, chequear:
- Cada KPI implícito tiene evidencia (qué de la JD lo sugiere).
- Las hipótesis de "por qué la búsqueda" tienen argumento.
- Los red flags están separados de las observaciones neutras.
- Las preguntas abiertas son específicas, no genéricas.

---

## Reglas de calidad (no negociables)

- **Lectura entre líneas obligatoria.** Un brief que solo describe lo que
  dice la JD literal no agrega valor. Identificar qué NO dice y qué dice de
  más es lo que diferencia este framework.
- **Hipótesis con argumento.** Toda hipótesis (de KPIs, de problemas,
  de red flags) debe tener evidencia explícita: qué texto específico, qué
  silencio, qué énfasis la sugiere.
- **Separar lectura de evaluación.** El framework describe el rol; NO compara
  con el usuario todavía. La comparación es del fit-gap (Paso 5).
- **Especificidad.** "Es un rol importante" no es contenido válido. "La JD declara reporting al hiring manager X, pero el organigrama público de la empresa muestra una capa intermedia que la JD no menciona; verificar reporting real" sí.
- **Honestidad sobre límites.** Si la JD es muy vaga, declarar la limitación.
  No inventar contenido para llenar secciones.
- **Red flags sin paranoia.** Solo señales que objetivamente merecen verificación.
  No interpretar maliciosamente cada palabra.

---

## Notas de implementación

- Si la JD está en otro idioma que el del usuario, traducir solo lo necesario.
  Mantener términos técnicos en idioma original si son señales (ej: "fast-paced"
  vs "ritmo rápido" tienen connotaciones distintas).
- Si la empresa publicó múltiples versiones del mismo rol o roles similares
  recientemente, mencionar como contexto adicional (probable rotación o expansión
  de equipo).
- Las "preguntas abiertas" (sección 7) son insumo crítico para el framework
  `07-smart-questions.md`. Cuanto más específicas y duras sean, mejor el output
  final del prep doc.
- Output esperable: 1-2 páginas. Si supera 3 páginas, está sobre-trabajado o
  incluyendo descripción literal de la JD que no agrega valor.