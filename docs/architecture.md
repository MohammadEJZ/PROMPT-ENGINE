# Architecture

PROMPT ENGINE is organized as a small orchestration core plus domain-specific modules.

## Layers
- **Orchestration:** routes the request and coordinates the workflow.
- **Discovery:** identifies consequential unknowns and asks adaptive questions.
- **Context analysis:** inspects source artifacts and preserves project truth.
- **Specialist modules:** provide domain-specific requirements and validation.
- **Prompt builder:** assembles a self-contained prompt using the master template.
- **Language engine:** separates conversation, interface, and prompt-output languages.
- **Quality gate:** checks feasibility, completeness, and testability.

## Extension model
To add a domain:
1. Create a focused Markdown module under `modules/`.
2. Define discovery questions, domain workflow, risks, deliverables, and acceptance criteria.
3. Add routing guidance to `SKILL.md` if the domain is not obvious.
4. Add at least one acceptance scenario to `tests/acceptance-checklist.md`.
5. Keep shared principles in `core/`; avoid duplicating them in every module.

## Compatibility
The repository contains portable Markdown instructions. Host-specific installation and UI capabilities are documented separately in `adapters/`.
