# Decisions

## Decision 001
Use explicit markdown files to separate goals, memory, roadmap, context, and execution rules.

Reason:
- easier for agents to parse
- easier for humans to locate intent
- reduces ambiguity across files

## Decision 002
Use two visual references with different meanings.

Files:
- `images/estado_atual_tela_completa.png`
- `images/estado_desejado_apenas_terminal.png`

Reason:
- the current state must not be confused with the desired state
- the target output should remain obvious

## Decision 003
Use OCR and structured UI state only as fallback for non vision agents.

Reason:
- vision capable agents should rely on direct visual evidence first
- non vision agents still need a reliable textual representation
