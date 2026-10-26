# Maersk conversation style skill

This package contains a platform-neutral AI agent skill derived from the supplied “How we sound” writing guidance.

## Contents
- `SKILL.md`: production-ready skill instructions
- `TESTS.yaml`: acceptance tests for style, accuracy and conversation behaviour

## Recommended integration
Place `SKILL.md` in the agent's skill or instruction directory and register the trigger for drafting, rewriting and reviewing conversational content. If the platform has separate system and task instructions, keep the priority order, safety rules and accuracy rules at system level.

## Design principle
The skill changes how the agent communicates, not what is true. Enterprise grounding, access control, safety policies and task-specific instructions remain authoritative.
