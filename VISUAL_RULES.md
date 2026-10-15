# Visual rules for agents

## Purpose
These reference images explain the current state and the desired final state of the workspace.

## Reference images
- `images/estado_atual_tela_completa.png`
  - This image shows the current full desktop state.
  - Treat it as the before state.
  - It includes extra windows and visual clutter that should be removed.

- `images/estado_desejado_apenas_terminal.png`
  - This image shows the desired final state.
  - Treat it as the target state.
  - The final workspace should be clean and show only the terminal.

## Required interpretation
When working from these references, use this meaning:
- current state = full screen with everything visible
- desired state = only the terminal visible

## Expected final result
The agent should leave the screen in a clean state where:
- only the terminal remains visible
- other windows should not remain visible
- the terminal should be the main focus

## Rule for image interpretation
Do not interpret the full desktop screenshot as the desired layout.
Use it only as a record of how things looked before cleanup.
Use the terminal only screenshot as the desired visual outcome.
