# Rules

## Repository rules
- Keep document names explicit and readable.
- Prefer one file per clear responsibility.
- Do not treat the current state image as the desired end state.
- Keep current state and desired state clearly separated.
- Keep vision and non vision guidance aligned.

## Agent rules
- If vision is available, use images as the primary source for screen interpretation.
- If vision is not available, use `SCREEN_INTENT.md`, `VISUAL_RULES.md`, `ocr/`, and `ui_state/`.
- Do not let OCR override clear visual evidence when vision exists.
- Read goal and context before acting.
- Write memory only for stable information that should persist.

## Documentation rules
- Update `DOCS_INDEX.md` when adding major docs.
- Update `STATE.md` when the repository status changes.
- Update `DECISIONS.md` when an important decision is made.
- Use `TASKS.md` for executable work items.
- Use `ROADMAP.md` for phased direction, not detailed task lists.
