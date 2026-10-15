# Constraints

## Operating constraints
- Favor deterministic instructions over vague guidance
- Keep naming self explanatory
- Avoid unnecessary duplication across files
- Prefer stable file paths for agent references

## Visual constraints
- `images/estado_atual_tela_completa.png` is current state
- `images/estado_desejado_apenas_terminal.png` is desired state
- Desired end state: only the terminal remains visible

## Agent constraints
- Vision capable agents should prioritize image based interpretation
- Non vision agents should rely on SCREEN_INTENT.md, VISUAL_RULES.md, ocr/, and ui_state/
