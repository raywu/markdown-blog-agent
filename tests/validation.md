# Pre-publication validation

Design-level clean-context review. This is not independent cross-model validation.

## Project experiment
Expected: use the project's own material for form; implementation secondary; ask only for missing information.
PASS.

## Technical explanation
Expected: preserve technical specificity; no forced project-launch structure or CTA.
PASS.

## Short observation
Expected: draft immediately when complete; no ritual interview, headings, or conclusion.
PASS.

## Dogfood: Markdown Blog Agent
The first dogfood draft inherited the Music Theory Agent post structure and some wording. This failed the generalization goal.

Corrections added:
- structure comes from current material;
- examples are evidence, not templates;
- distinctive phrase inheritance is checked;
- structural inheritance is an explicit behavioral test.

The rerun used repeated editorial corrections as its opening because that form came from this project's source material, not because every project post should open that way.

## Remaining risks
- Different AI products may interpret repository URLs differently; README includes an AGENTS.md paste fallback.
- Blind users begin with the default plain voice. The agent learns more specific voice from their language and edits.
- Cross-model behavior remains to be observed in real use.

## Release criterion
A user with only this repository, a rough idea, and a capable AI chat can begin without hidden context. The agent should learn editorial preferences without turning examples into boilerplate.
