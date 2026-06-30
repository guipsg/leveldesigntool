# Level Design Tool Agent Guide

## Project Mission
Build a tool that turns raw game design ideas into a usable level design document that includes:
- Flow and pacing
- Mechanics and tuning levers
- Narrative and environmental storytelling
- Map layout and wayfinding

## Current Repository State
- This repository currently contains chat custom agents only.
- No runtime stack, build scripts, or tests are defined yet.
- If implementation work is requested, propose stack options first, then align commands in this file.

## Agent Routing
- Idea to mechanics and loops: [.github/agents/game-designer.md](.github/agents/game-designer.md)
- Spatial layout, pacing beats, and encounter flow: [.github/agents/level-designer.md](.github/agents/level-designer.md)
- Interface and tool UX: [.github/agents/design-ui-designer.md](.github/agents/design-ui-designer.md)
- Narrative framing and visual communication: [.github/agents/design-visual-storyteller.md](.github/agents/design-visual-storyteller.md)
- Web implementation and editor UX: [.github/agents/engineering-frontend-developer.md](.github/agents/engineering-frontend-developer.md)
- Fast validation prototypes: [.github/agents/engineering-rapid-prototyper.md](.github/agents/engineering-rapid-prototyper.md)
- Documentation and templates: [.github/agents/engineering-technical-writer.md](.github/agents/engineering-technical-writer.md)

## Preferred Workflow
1. Capture idea, target player fantasy, and constraints.
2. Produce mechanics and progression assumptions.
3. Convert assumptions into a level flow with encounter sequence.
4. Draft narrative beats tied to spaces.
5. Produce a map spec and wayfinding notes.
6. Compile all sections into one level design document.

## Level Design Document Standard
Every complete level design document should contain these sections in order:
1. Overview and intent
2. Player experience goals
3. Flow and pacing
4. Mechanics and system interactions
5. Narrative and environmental storytelling
6. Map layout and key locations
7. Encounter plan and difficulty curve
8. Open questions and test plan

Use [.github/instructions/level-design-document.instructions.md](.github/instructions/level-design-document.instructions.md) for detailed writing rules and acceptance checks.

## Reusable Workflow Skill
Use [.github/skills/level-design-document/SKILL.md](.github/skills/level-design-document/SKILL.md) when asked to transform an idea into a complete level design document.

## Quality Gates
- Mark uncertain numbers and assumptions as `[PLACEHOLDER]`.
- Keep mechanics tied to clear player decisions.
- Ensure map guidance is readable without external explanation.
- Add a short validation plan for playtesting or review.

## Update Rule
When project stack, commands, or data model become known, update this file first and link deeper docs instead of duplicating content.
