# Test Plan

## Goal
Validate that the repository works as an execution context for both vision and non vision agents.

## Core tests
1. Discovery test
- A new agent can identify the main docs and their roles

2. Visual interpretation test
- A vision capable agent reads the current and desired images correctly

3. Non vision fallback test
- A non vision agent reaches the same interpretation using SCREEN_INTENT.md, VISUAL_RULES.md, ocr/, and ui_state/

4. Workflow test
- The agent can determine a valid next step from GOAL.md, PLAN.md, and TASKS.md

5. Handoff test
- A second operator can continue using MEMORY.md, SESSION.md, and HANDOFF.md

## Acceptance
The same intended result should be reachable through both the vision path and the fallback path.
