# RFC

## Title
Standard visual state description for agent driven desktop tasks

## Status
Draft

## Problem
Agents may confuse reference images or may operate without vision.

## Proposal
Use paired assets and text layers:
- current image
- desired image
- visual rules
- OCR fallback
- JSON UI state

## Decision
Adopt the repository structure as the standard source of truth.

## Consequences
### Positive
- Better reliability for vision and non vision agents
- Lower ambiguity
- Easier handoff

### Tradeoffs
- More files to maintain
- Need to keep images and text in sync
