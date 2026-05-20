# Output Template — Estructura del Prep Doc Final

> Este archivo define cómo se presenta el resultado del flujo completo
> (Pasos 0-10 del `SKILL.md`) al usuario. NO genera contenido nuevo;
> estructura y ordena los outputs producidos por los frameworks.
>
> El output final depende del modo (ver Paso 1.5 del SKILL.md):
> - **Modo full:** dos documentos `.docx` separados — prep doc principal + DD ejecutivo anexo.
> - **Modo express:** un solo documento `.docx` — prep doc condensado, sin anexo.

---

## Documento 1 — Prep doc principal

Contiene los 9 outputs principales del flujo. Estructura en este orden:

### Header (1 línea)

`Empresa · Rol · Entrevistador · Etapa del proceso · Fecha y hora de la entrevista`

Ejemplo:
> Acme Corp · VP Sales LatAm · Laura Méndez (Chief Revenue Officer LATAM) · Primera ronda · 15 de mayo, 11:00 AM

### Sección 1 — Resumen ejecutivo del fit
De `04-fit-gap.md`, sección "Resumen del fit". 3 líneas.

### Sección 2 — Brief del rol
De `01-role-analysis.md`. Estructura completa del role analysis (resumen,
KPIs implícitos, problemas a resolver, hard vs nice-to-haves, señales de
cultura, red flags, preguntas abiertas).

### Sección 3 — Brief condensado de empresa
De `03-company-dd.md`, output B (brief condensado de 1 página).
**No incluir el DD ejecutivo completo acá** — ese va al final como anexo.

### Sección 4 — Dossier del entrevistador
De `02-interviewer-research.md`. Estructura completa del dossier (identidad,
huella, estilo, qué le importa, qué va a probar, dinámica probable,
conexiones, red flags, hipótesis de por qué fue elegido).

### Sección 5 — Top 3 fortalezas a destacar
De `04-fit-gap.md`, sección "Top 3 fortalezas a destacar".

### Sección 6 — Top 5 gaps probables
De `04-fit-gap.md`, sección "Top 5 gaps probables".

### Sección 7 — Banco de preguntas predichas + STAR drafts
De `05-question-bank.md`. Estructura completa: preguntas por bloque con
probabilidad, STAR drafts para top 5-7, calibración explícita.

### Sección 8 — Modo sparring
De `06-sparring.md`. Estructura completa: declaración de modo, 5-7
ataques con kit completo, cierre con ofertas.

**Importante:** las ofertas de cierre del sparring (drilling
interactivo + hard mode opcional) van al final del documento, no acá. Ver
sección 11.

### Sección 9 — Smart questions para hacer
De `07-smart-questions.md`. Estructura completa: preguntas por categoría,
preguntas core marcadas, interpretación de respuestas.

### Sección 10 — One-pager last-mile
De `08-one-pager.md`. UNA página estricta. Va separada visualmente del
resto del prep doc — es el último material que se lee.

### Sección 11 — Cierre interactivo

Después del one-pager, cerrar el prep doc con tres ofertas al usuario:

1. **Drilling sparring:**
> ¿Quieres practicar las 3 más duras del sparring ahora? Te lanzo la
> pregunta, respondes, te critico, iteramos.

2. **Hard mode** (solo si el sparring corrió en modo realista):
> ¿Quieres ver la versión hard mode de los top 3 ataques?

3. **Profundizar bloque:**
> ¿Quieres profundizar algún bloque específico del prep doc o ajustar
> algún supuesto que no te cierre?

---

## Documento 2 — DD ejecutivo de empresa (anexo)

Documento separado del prep doc principal. Contiene el DD ejecutivo completo
de `03-company-dd.md`, output A (las 9 secciones del investment memo).

### Header del anexo (1 línea)

`Anexo: DD Ejecutivo de [Empresa] — [Mercado/Región/Unidad relevante]`

Ejemplo:
> Anexo: DD Ejecutivo de Acme Corp — LatAm

### Estructura

Las 9 secciones definidas en `03-company-dd.md`:
1. Resumen ejecutivo (5 bullets accionables).
2. Industria y mercado.
3. Modelo de negocio.
4. Financials.
5. Posición competitiva.
6. Propuesta de valor y ventajas competitivas.
7. Cómo IA está afectando a la empresa específicamente.
8. Movimientos recientes.
9. Hipótesis estratégicas.

### Nota al final del anexo

Una línea recordando al usuario que este DD es reutilizable:
> Este DD se actualiza una vez por empresa, no por entrevistador. Si avanzás
> rondas en este proceso, el DD sigue vigente; lo que cambia entre rondas
> es el dossier del entrevistador y el fit-gap específico.

---

## Cómo presentar los dos documentos al usuario

### Formato de entrega: archivos .docx descargables

El output final son archivos Word (`.docx`) generados con la skill `docx` (ver `/mnt/skills/public/docx/SKILL.md` para la API exacta de python-docx). NO entregar el contenido como markdown inline en chat.

**Modo full.** Generar dos archivos separados:
- `prep-doc-[empresa]-[YYYY-MM-DD].docx` — prep doc principal (secciones 1-10 de arriba).
- `dd-anexo-[empresa]-[mercado].docx` — DD ejecutivo de empresa anexo.

**Modo express.** Un solo archivo:
- `prep-doc-express-[empresa]-[YYYY-MM-DD].docx` — prep doc principal condensado, sin anexo.

Guardar los archivos en `/mnt/user-data/outputs/` y presentarlos con la herramienta `present_files`. El prep doc principal debe ir primero en el array de filepaths (es el documento que se lee primero).

### Convenciones de formato dentro del .docx

- **Heading 1** para "Sección N — Título".
- **Heading 2** para subsecciones dentro de cada sección.
- **Heading 3** y siguientes para granularidad adicional.
- Tablas para comparaciones (competidores, fortalezas vs gaps, etc.).
- Listas con bullets para enumeraciones cortas.
- Bold para énfasis puntual (nombres clave, métricas signature), no para párrafos enteros.
- Page break antes del one-pager (sección 10) para que quede visualmente aislado en la última página.
- Page break antes del cierre interactivo (sección 11).

### Mensaje al usuario al entregar

Anteponer una línea breve de orientación antes de la entrega de archivos:

**Modo full:**
> Te entrego dos archivos: el **prep doc principal** que lees 24-48h antes (con one-pager para el last-mile), y el **DD ejecutivo de empresa** como anexo (lectura de fondo, reutilizable para futuras rondas con esta misma empresa).

**Modo express:**
> Te entrego el **prep doc express**. Sin anexo de DD porque para esta etapa estaría sobre-trabajado. Si avanzás de ronda, puedes pedirme el upgrade a modo full y armo el DD ejecutivo aparte sobre la misma base.

---

## Reglas de presentación

- **Separación clara entre documentos.** El prep doc principal y el DD
  anexo son entregables distintos. No mezclarlos en un solo flujo de
  contenido sin separadores explícitos.
- **Orden no es opcional.** Las secciones del prep doc principal van en el
  orden definido. El one-pager siempre al final del prep doc, antes del
  cierre interactivo.
- **Headers consistentes.** Cada sección numerada con el mismo formato
  (## Sección N — Título).
- **Sin redundancia entre secciones.** Si una pieza de información aparece
  en una sección, no repetirla en otra. Excepción: el one-pager
  intencionalmente comprime y repite (esa es su función).
- **Calibración explícita visible.** Cada sección que tenga "calibración
  explícita" en su framework (fit-gap, question-bank, smart-questions)
  debe mantener esa transparencia en el output final. No esconder
  supuestos.
- **Lengua consistente.** Todo el output en el idioma del usuario (español
  por default del archivo de perfil; inglés solo si la entrevista es en inglés y el
  usuario explícitamente lo pidió).

---

## Notas de implementación

- Si algún framework no produjo output (ej: footprint del entrevistador insuficiente, JD muy vaga, etc.), incluir la sección igual con la declaración explícita de la limitación. NO omitir secciones por silencio.
- El formato por default es `.docx`. Si el usuario explícitamente pide otro formato (PDF, plain text, markdown en chat), el contenido es el mismo pero el rendering cambia. La estructura semántica no.
- Output esperable total en modo full: 8-15 páginas para el prep doc principal + 4-6 páginas para el DD anexo. En modo express: 4-6 páginas para el prep doc condensado. Si supera esos rangos significativamente, algún framework está sobre-trabajado.
- El cierre interactivo (sección 11) NO es un texto fijo; las tres ofertas son explícitas pero el usuario puede pedir lo que quiera. La skill debe responder a cualquier pedido razonable de profundización.
- **Modo express:** la sección 3 del prep doc (brief condensado de empresa) reemplaza la necesidad del DD anexo. No generar el documento 2. El cierre interactivo agrega una cuarta oferta: "¿Quieres que arme el DD ejecutivo completo de [Empresa] aparte? Útil si avanzás de ronda y la inversión empieza a justificarse."