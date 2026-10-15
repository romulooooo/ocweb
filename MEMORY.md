# Memory

## Purpose
This file stores persistent operational memory for agents working in this repository.

## Current persistent facts
- The visual goal is to clean the screen and leave only the terminal visible.
- `images/estado_atual_tela_completa.png` shows the current state.
- `images/estado_desejado_apenas_terminal.png` shows the desired state.
- If an agent has vision, images are the primary source of truth.
- If an agent does not have vision, it must use `SCREEN_INTENT.md`, `VISUAL_RULES.md`, `ocr/`, and `ui_state/`.
- OCR is a fallback layer for non vision agents.

## User interaction rules
- Do not mentally correct the user messages.
- Do not use accented characters.
- Do not use scroll.
- Prefer keyboard navigation when possible.
- If the calendar is open, stop immediately.
- If the mouse is over the calendar, stop immediately.

## Working assumptions
- Keep instructions explicit and easy for agents to follow.
- Prefer simple file names and direct explanations.
- Keep visual interpretation aligned across all docs.

## Update policy
Add important decisions, stable user preferences, and repeated constraints here.
Do not store temporary notes that will be outdated quickly.
