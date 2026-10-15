# Risks

## Primary risks
1. Document sprawl
- Too many files can reduce clarity
- Mitigation: keep DOCS_INDEX.md current and define source of truth per topic

2. Conflicting instructions
- Rules repeated in many files can drift
- Mitigation: AGENTS.md, RULES.md, and CONSTRAINTS.md must remain aligned

3. Vision mismatch
- A non vision agent may misread the intended screen state
- Mitigation: use SCREEN_INTENT.md, VISUAL_RULES.md, ocr/, and ui_state/

4. Session loss
- Important context may disappear between runs
- Mitigation: use MEMORY.md, SESSION.md, and HANDOFF.md

5. False completion
- An agent may claim success without checking the final state
- Mitigation: use CHECKLIST.md, SUCCESS_CRITERIA.md, and TEST_PLAN.md
