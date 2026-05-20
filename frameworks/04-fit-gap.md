# 04 — Fit-Gap Analysis

> Framework invocado por el Paso 5 del flujo principal (`SKILL.md`).
> Cruza el contexto del usuario contra el rol, el entrevistador y la empresa
> para producir una matriz operativa de fortalezas a destacar y gaps a defender.

---

## Inputs (de pasos previos)

1. **Contexto del usuario** — `user-context/[nombre].md` ya cargado en el Paso 0.
2. **Brief del rol** — output del Paso 2 (seniority del rol target, KPIs implícitos, problemas que resuelve la
   contratación, hard requirements vs nice-to-haves, señales de cultura).
3. **Dossier del entrevistador** — output del Paso 3 (qué le importa, estilo probable,
   qué va a probar).
4. **Brief de empresa** — output del Paso 4 (momento estratégico de la empresa).

Si falta cualquiera de estos, no avanzar. Volver a pedir o ejecutar el paso correspondiente.

---

## Outputs (estructura del entregable)

El framework produce CUATRO secciones, en este orden:

### 1. Resumen del fit (3 líneas)

- **Calificación general:** alto / medio / con riesgos.
- **Dónde ganás:** las 1-2 dimensiones donde el fit es más fuerte.
- **Dónde pierdes:** las 1-2 dimensiones donde el fit es más débil.

Ejemplos de redacción por tipo de rol:

> "Fit alto. Ganás en track record de gestión de equipos del tamaño que pide el rol y en dominio del sector. Perdés en experiencia con la stack tecnológica específica que mencionan."

> "Fit con riesgos. Ganás en pensamiento estratégico y reporting a leadership senior. Perdés en operación directa de la función (rol pide hands-on, tu trayectoria es más de gestión a través de managers)."

> "Fit medio. Ganás en experiencia regional cross-mercado y manejo de stakeholders. Perdés en industria específica (vienes de otra vertical)."

### 2. Top 3 fortalezas a destacar

Para cada fortaleza, producir:

- **Fortaleza específica:** qué del usuario.
- **Por qué es relevante PARA ESTE rol:** conexión explícita con un KPI implícito,
  un problema que resuelve la contratación, o algo que le importa al entrevistador.
- **Métrica/historia que la respalda:** qué story específica o qué número del track
  record sostiene la fortaleza.
- **Activación:** en qué momento o tipo de pregunta de la entrevista activarla.

Regla: las fortalezas deben venir del archivo del usuario (`[nombre].md`), no inventadas.
Si una fortaleza obvia para el rol no está en el archivo del usuario, declararlo como
gap, no como fortaleza ausente.

### 3. Top 5 gaps probables (rankeados por probabilidad de prueba)

Para cada gap, producir:

- **Qué falta:** descripción concreta del gap (skill, experiencia, identidad,
  contexto, scope).
- **Tipo de gap:** uno de cinco categorías (ver abajo).
- **Probabilidad de prueba:** alta / media / baja.
- **Severidad si no se cubre bien:** deal-breaker / matiz.
- **Hipótesis de cómo se va a poner a prueba:** qué tipo de pregunta o señal
  esperar en la entrevista.

#### Categorías de gap (cinco tipos)

1. **Knowledge gap** — falta saber algo específico (un dominio, una herramienta, un proceso, un mercado, una metodología). Ejemplos: candidato que viene de retail aplicando a una empresa tech y no domina SaaS metrics; candidato que viene de Argentina aplicando a un rol con foco en Brasil y no conoce las dinámicas locales. Defensa típica: mostrar adaptabilidad pasada o traer un análogo transferible.

2. **Experience gap** — nunca hizo algo concreto. Ejemplos: nunca lideró un equipo del tamaño que pide el rol; nunca manejó un canal de distribución específico; nunca operó en una geografía particular; nunca atravesó un evento específico como un IPO o una crisis. Defensa típica: framing transferible, métricas equivalentes en otras dimensiones, "la habilidad subyacente es la misma, el contexto cambia".

3. **Identity gap** — cómo se presenta el usuario vs cómo lo va a categorizar el entrevistador. Ejemplos: candidato que se ve como "estrategia" pero el rol busca "execution"; candidato que se ve como "líder de área" pero el rol busca "individual contributor senior"; candidato que se ve como "operador" pero el entrevistador lo lee como "consultor". Defensa típica: reframing narrativo, sostener el frame propio incluso cuando el entrevistador tira el otro como ancla. Conceder superficie, defender estructura.

4. **Cultural gap** — cultura del lugar de origen del usuario vs cultura del destino. Ejemplos: viene de una corporación grande, va a una startup chica donde se espera scrappiness; viene de una empresa familiar a una pública con compliance fuerte; viene de cultura jerárquica a cultura plana, o viceversa. Defensa típica: demostrar fluidez con ambos contextos cuando existe; mostrar curiosidad genuina cuando no.

5. **Scope gap** — el rol pide algo de escala o alcance distinto a lo que el usuario hizo. Mucho más grande (saltar de manager a director, de un equipo de 10 a 100); mucho más chico (bajar de un equipo grande a uno chico, lo cual también requiere defensa); distinta industria; distinto tipo de organización (privada vs pública, B2C vs B2B, producto vs servicio). Defensa típica: métricas relativas, "lo que manejaba era complejo en otra dimensión", argumento de transferibilidad.

### 4. Calibración explícita

Sección final que documenta:

- **Qué del contexto del usuario se usó:** referencias específicas a secciones de
  `[nombre].md` (ej: "patterns bajo presión #5: política ambigua").
- **Qué supuestos sobre la JD se hicieron:** especialmente cuando un KPI no está
  explícito sino inferido.
- **Qué supuestos sobre el entrevistador se hicieron:** especialmente sobre qué
  va a probar.
- **Qué supuestos sobre la empresa se hicieron:** sobre todo si se infirió algo del momento estratégico.

Esta sección permite que el usuario detecte y corrija supuestos débiles antes de
seguir con los pasos posteriores (especialmente el sparring).

---

## Proceso (cómo hacer el cruce)

Ejecutar en este orden:

### A. Identificar dimensiones relevantes del rol

Listar las 5-7 dimensiones en las que ESTE rol específico evalúa al candidato.
Salen de combinar:
- Hard requirements de la JD (paso 2)
- Seniority del rol target (paso 2) y cómo se compara con la banda actual del usuario
- Lo que probablemente le importa al entrevistador (paso 3)
- Contexto estratégico de la empresa (paso 4)

Ejemplos de dimensiones (varían por tipo de rol):

- **Para roles de gestión:** escala de equipo manejada, capacidad de hiring senior, manejo de stakeholders cross-funcionales, exposición a leadership de la empresa.
- **Para roles técnicos:** profundidad de la stack relevante, experiencia con el escenario específico (ej: scaling, modernization), exposición a decisiones de arquitectura.
- **Para roles comerciales:** track record con el canal o segmento relevante, sales cycle equivalente, manejo de cuentas de complejidad similar.
- **Para roles de soporte (HR, finance, legal):** experiencia con el tamaño y complejidad de organización, exposición regulatoria relevante.
- **Para todos los niveles a partir de gestión:** capacidad de operar en el ritmo de la empresa (startup vs corporate), dominio de la industria o vertical, manejo del idioma de trabajo, disponibilidad geográfica.

### B. Scoring rápido por dimensión

Para cada dimensión, ubicar el match del usuario en una escala simple:
fuerte / mediano / débil.

No requiere precisión cuantitativa. Es para identificar dónde está el centro de
gravedad del fit y dónde están los focos de riesgo.

### C. Extraer top 3 fortalezas

Las 3 dimensiones donde el match es FUERTE Y la dimensión es CENTRAL al rol.
Una fortaleza fuerte en una dimensión periférica no entra al top 3.

Para cada una, redactar las 4 partes del output (fortaleza / relevancia /
métrica-historia / activación).

### D. Extraer top 5 gaps

Las 5 dimensiones donde el match es DÉBIL O MEDIANO Y la dimensión es relevante
al rol.

Si hay menos de 5 gaps reales, declarar que solo hay X gaps y por qué. NO
inventar gaps adicionales para llegar a 5.

Para cada gap, completar las 5 partes del output (qué falta / tipo /
probabilidad / severidad / cómo se prueba).

### E. Rankear gaps

Ordenar los gaps por probabilidad de prueba (alta primero), y dentro de cada
nivel de probabilidad, por severidad (deal-breaker primero).

### F. Producir resumen del fit

Tres líneas. La calificación general sale de la combinación: si las 3
fortalezas top son fuertes y centrales, y los gaps top son de severidad
matiz, el fit es ALTO. Si los gaps top son deal-breakers de probabilidad
alta, el fit es CON RIESGOS. Casos intermedios son MEDIO.

### G. Documentar calibración explícita

Antes de cerrar el output, revisar el documento producido y listar
explícitamente los supuestos hechos.

---

## Reglas de calidad (no negociables)

- **No inventar fortalezas.** Si una fortaleza obvia para el rol no está en
  `[nombre].md`, declararlo como gap, no como fortaleza ausente.
- **No suavizar gaps.** Si un gap es deal-breaker de probabilidad alta, declararlo.
  La regla "sparring real" del SKILL.md aplica acá: no hacer sentir bien al usuario
  a costa de la calidad del análisis.
- **Especificidad obligatoria.** Las fortalezas y gaps deben ser específicos a ESTE rol concreto. "Es buen líder" no es una fortaleza válida; "construyó equipos de N personas en contextos comparables al de este rol (mismo tipo de industria / misma fase / mismo tamaño)" sí lo es.
- **Conexión explícita con outputs previos.** Cada fortaleza y cada gap debe
  conectar con algo concreto del brief del rol, dossier del entrevistador o brief
  de empresa. Si no hay conexión, no es relevante para este rol.
- **Tipos de gap correctos.** Categorizar bien el tipo de gap es crítico porque
  alimenta directamente al modo sparring (paso 7), que usa el tipo para elegir
  el frame de defensa.
- **Calibración transparente.** La sección 4 (calibración explícita) no es opcional.
  Permite al usuario detectar supuestos débiles antes de avanzar.

---

## Notas de implementación

- Si el rol tiene componentes que no encajan en ninguna dimensión que el usuario haya
  manejado antes, ese es un scope gap por defecto, no una falta de información.
- Si el entrevistador tiene un tema específico que aparece recurrentemente en su huella pública (ej. interés explícito en transformación digital, énfasis en métodos ágiles, cruzada por diversidad e inclusión), ese tema entra como una dimensión adicional aunque no esté en la JD.
- Si la empresa está en un momento muy particular declarado públicamente (ej. expansión anunciada, cambio de estrategia comunicado, transición a estructura distinta), ese momento puede crear gaps culturales o de scope que no están explícitos en la JD.
- La comparación entre la banda del rol target y la banda actual del usuario (validada en el paso 2) es el cruce más importante. Saltar un nivel hacia arriba es uno de los gaps más comunes y más sutiles de defender bien.
- Output esperable: 1-2 páginas. Si supera 3 páginas, está sobre-trabajado.
