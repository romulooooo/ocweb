# AGENTS

## Visual reference rules

This repository contains two reference images.

- `images/estado_atual_tela_completa.png`
  - This is the current or before state.
  - It shows extra windows and visual clutter.
  - Do not treat this image as the target layout.

- `images/estado_desejado_apenas_terminal.png`
  - This is the desired final state.
  - Treat this image as the target layout.
  - The final workspace should show only the terminal.

## Required interpretation

When using the reference images:

- current state = full desktop with everything visible
- desired state = only the terminal visible

## Agent behavior

The agent should leave the screen in a clean state where:

- only the terminal remains visible
- other windows should not remain visible
- the terminal should be the main focus

See also `VISUAL_RULES.md` and `CONTEXT.md`.
