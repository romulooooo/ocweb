# Workflow

## Purpose
This file defines the default execution flow for humans and agents working in this repository.

## Standard flow
1. Read `README.md` for the project overview.
2. Read `GOAL.md` for the current objective.
3. Read `AGENTS.md` for agent behavior rules.
4. Read `CONTEXT.md` and `VISUAL_RULES.md` for interpretation rules.
5. If the agent has vision, use the reference images as the primary source.
6. If the agent does not have vision, use `SCREEN_INTENT.md`, `ocr/`, and `ui_state/` as fallback sources.
7. Review `PLAN.md`, `ROADMAP.md`, and `TASKS.md` before making changes.
8. Update files consistently when project understanding changes.
9. Validate work against `CHECKLIST.md` before considering the task done.
10. Record stable findings in `MEMORY.md` when needed.

## Visual workflow
- `images/estado_atual_tela_completa.png` shows the current state.
- `images/estado_desejado_apenas_terminal.png` shows the desired state.
- The goal is to remove distractions and leave only the terminal visible.

## Documentation workflow
- Use `PRD.md` for requirements.
- Use `ARCHITECTURE.md` for technical structure.
- Use `DECISIONS.md` and `docs/decisions/` for notable decisions.
- Use `STATE.md` for current project state.

## Update workflow
When adding a new rule or reference:
1. Update the most relevant source file.
2. Update `DOCS_INDEX.md` if a new document is added.
3. Update `MEMORY.md` if the rule is persistent.
4. Update `TASKS.md` if there is follow up work.
