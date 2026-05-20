# Changelog

Todos los cambios relevantes de esta skill quedan documentados acá.

El formato sigue [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/) y el versionado sigue [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] — 2026-05-20

Primera versión pública.

### Added

- `SKILL.md`: orquestación principal con detección automática de dos modos (onboarding vs interview prep) y dos sub-modos de prep (express vs full).
- `frameworks/00-onboarding.md`: framework conversacional de 45-60 minutos para construir el perfil del usuario, con foco en patterns bajo presión.
- `frameworks/01-role-analysis.md`: análisis estructurado de la JD (KPIs implícitos, hard skills vs nice-to-haves, señales de cultura).
- `frameworks/02-interviewer-research.md`: protocolo de investigación del entrevistador con quality gate de mínimo 3 fuentes públicas o declaración explícita de no-huella.
- `frameworks/03-company-dd.md`: due diligence ejecutivo de empresa tipo investment memo, filtrado al mercado/región/unidad relevante, con sección obligatoria sobre impacto de IA en el sector.
- `frameworks/04-fit-gap.md`: análisis fit-gap calibrado al perfil del usuario, con identificación de top 3 fortalezas y top 3-5 gaps reales.
- `frameworks/05-question-bank.md`: banco de preguntas predichas con drafts STAR (estructura impacto-primero, no cronológica).
- `frameworks/06-sparring.md`: modo sparring, el diferenciador. Genera 5-7 ataques calibrados al estilo del entrevistador y a los patterns documentados del usuario, con frame mental de defensa por cada uno.
- `frameworks/07-smart-questions.md`: preguntas inteligentes para hacer al entrevistador, calibradas a la etapa del proceso.
- `frameworks/08-one-pager.md`: one-pager last-mile para releer 10 minutos antes de la entrevista.
- `user-context/template.md`: template del perfil del usuario.
- `output-template.md`: estructura del prep doc final.
- `docs/knowledge-base.svg`: diagrama de los cuatro inputs convergentes.
- `.github/ISSUE_TEMPLATE/case-study.yml`: template de issue para reportar casos donde el sparring no acertó al weak spot real.

### Notes

- Toda la skill está en español neutro/voseo (LatAm).
- Cero referencias personales del autor: la skill es agnóstica y se calibra al perfil que cada usuario carga.
- Anti-hallucination explícito en quality gates de research, footprint del entrevistador y sparring.

---

[1.0.0]: https://github.com/martinjbellocq/full-interview-prep/releases/tag/v1.0.0
