# CONTEXT

## Goal

Use the reference images to understand the difference between the current state and the desired final state.

## Image meaning

- `images/estado_atual_tela_completa.png`
  - before state
  - contains extra windows
  - not the desired final layout

- `images/estado_desejado_apenas_terminal.png`
  - after state
  - desired final layout
  - only the terminal should remain visible

## Final expectation

An agent working from these references should clean the workspace until:

- the terminal is the only visible window
- visual clutter is removed
- the terminal is clearly the main focus

## Interpretation warning

Do not use the full desktop screenshot as a template for the final result.
Use it only as evidence of the starting point.
