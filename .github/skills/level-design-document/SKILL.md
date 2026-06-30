---
name: level-design-document
description: "Create a complete level design document from a game idea, including flow, mechanics, narrative, and map. Use when users ask to turn ideas into structured level docs."
---

# Level Design Document Skill

## Purpose
Turn rough game ideas into a structured level design document that can be reviewed, iterated, and implemented.

## When To Use
- User asks to turn an idea into a level design document.
- User requests flow, mechanics, narrative, and map planning in one output.
- User needs a draft that multiple disciplines can collaborate on.

## Inputs
Collect or infer these inputs before drafting:
- Genre and target player fantasy
- Target session length and difficulty intent
- Core verbs or mechanics
- Narrative premise
- Required constraints (platform, scope, team size, style)

If critical inputs are missing, ask only for the minimum needed to avoid hallucinated specifics.

## Workflow
1. Restate the design intent in one paragraph.
2. Define player goals and fail states.
3. Draft flow and pacing beats from entry to completion.
4. Specify mechanics with variables and `[PLACEHOLDER]` tuning values.
5. Bind narrative beats to physical spaces.
6. Draft map structure with critical and optional paths.
7. Add encounter progression and difficulty curve.
8. End with validation plan and open questions.

## Output Contract
Produce sections in this order:
1. Overview and design intent
2. Player experience goals
3. Flow and pacing
4. Mechanics and system interactions
5. Narrative and environmental storytelling
6. Map layout and wayfinding
7. Encounter and challenge curve
8. Validation plan and open questions

Use concise bullets first, then add short supporting paragraphs only where needed.

## Quality Bar
- The document should be usable by design, engineering, and narrative collaborators.
- Each mechanic must map to at least one space or encounter.
- Navigation intent must be understandable without extra verbal explanation.
- Unknowns must be explicit, not implied.
