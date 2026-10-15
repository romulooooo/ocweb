# Screen Intent

This repository includes image references that describe a workspace cleanup task.

## Objective

Transform the current desktop state into the desired desktop state.

## Image mapping

- `images/estado_atual_tela_completa.png` = current state only
- `images/estado_desejado_apenas_terminal.png` = desired final state

## Core rule

The full desktop screenshot is not a template for the final result.
It is evidence of how the workspace looks before cleanup.

## Final expectation

A successful result leaves only the terminal visible.
Anything else should be closed, hidden, or minimized when possible.

## For models without vision

Use these files as the text based substitute for image understanding:

- `VISUAL_RULES.md`
- `ocr/estado_atual.txt`
- `ocr/estado_desejado.txt`
- `ocr/estado_atual_raw.txt`
- `ocr/estado_desejado_raw.txt`
- `ui_state/current.json`
- `ui_state/desired.json`

## Decision rule

If there is a conflict between the current state image and the desired state image,
follow the desired state image.

If there is a conflict between raw OCR noise and the semantic summaries,
follow the semantic summaries and `VISUAL_RULES.md`.
