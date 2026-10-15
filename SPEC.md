# SPEC

## Purpose
This file defines the working specification for the repository.

## Primary objective
Transform the current desktop state into the desired state where only the terminal remains visible.

## Inputs
- `images/estado_atual_tela_completa.png`
- `images/estado_desejado_apenas_terminal.png`
- `VISUAL_RULES.md`
- `SCREEN_INTENT.md`
- `ui_state/current.json`
- `ui_state/desired.json`
- `ocr/`

## Expected behavior
1. Interpret the current state correctly.
2. Interpret the desired state correctly.
3. Prefer image understanding when vision is available.
4. Use OCR and structured files only as fallback for non vision agents.
5. Produce repeatable desktop actions.

## Success criteria
- Only the terminal is visible in the final state.
- The current state image is not confused with the desired state.
- The agent follows repository rules and user interaction rules.
