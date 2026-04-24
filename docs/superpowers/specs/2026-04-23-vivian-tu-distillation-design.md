# Vivian Tu Distillation Design

## Goal

Create an anonymous perspective skill inside `C:\github\nuwa-skill` distilled from Vivian Tu's public-facing communication style, with deliberate emphasis on the I-style portion the user wants to study:

- social pull
- story-led momentum
- conversational spreadability
- high-energy framing
- action-driving clarity

The final output should function as a reusable communication system, not as biography, fandom summary, or surface-level imitation.

## Scope

### In scope

- Distill the speaker's public communication patterns from official or high-confidence public materials.
- Keep only the parts that support strong I-style influence in money communication.
- Produce:
  - an anonymized `SKILL.md`
  - a short anonymized `analysis.md`
- Store the final distilled files under `distilled/`.

### Out of scope

- Personal biography
- Career history
- Family background
- Personal anecdotes and origin stories
- Brand slogans, identity watermarks, or self-labeling hooks
- Private-life material
- Any persuasion move that depends on "believe me because of who I am"

## User Constraints

- All writes must stay inside `C:\github\nuwa-skill`.
- The final distilled result must not include the source person's personal information.
- The final distilled result must not include personal history or autobiographical proof.
- The final distilled result must not preserve the source person's watermark phrases, signature self-branding, or named persona wrapper.

## Source Strategy

Primary focus:

- official website messaging
- official podcast/show descriptions
- direct interviews and reputable profiles that describe how the style lands on audiences

Research focus:

- how the speaker makes money content feel like social conversation rather than lecture
- how she turns insider framing into shareable, high-retention storytelling
- how she creates momentum with punchy reframes and quick escalation
- how she makes dense topics feel gossip-adjacent, friendly, and urgent
- how she pushes from attention to action without depending on personal life story

## Output Design

### Artifact 1: anonymous analysis

Location:

- `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\analysis.md`

Purpose:

- explain the I-style influence engine
- separate transferable communication mechanics from non-transferable personal watermark
- give the user a study guide for learning the style

### Artifact 2: anonymous skill

Location:

- `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\SKILL.md`

Purpose:

- provide a directly usable anonymous perspective
- preserve social pull, punchiness, conversational persuasion, and action momentum
- avoid biography, self-branding, and personal credential-led authority

## Extraction Hypotheses

The source set suggests the final skill should preserve these patterns:

- open with a socially sticky hook instead of a dry definition
- frame money topics as surprisingly relevant, unfair, juicy, or game-like
- use friend-to-friend language that feels inclusive rather than institutional
- move fast from recognition to reframe to takeaway
- convert explanation into a memorable line that others could repeat
- keep pressure high enough to create momentum, but not so high that it becomes shame-heavy

The final skill should remove these patterns:

- source-person self-introduction
- source-person career credentials
- source-person backstory
- source-person signature brand wrapper
- source-person named catchphrases or watermarks

## Distinction From Nearby Repo Patterns

This package should not collapse into the repo's existing gentle, steady, or emotionally reassuring money voices.

The target is not:

- S-style emotional holding
- pure reassurance-first guidance
- soft companionship as the main engine

The target is:

- fast social engagement
- conversational charisma
- high-retention framing
- strong reframe energy
- memorable, retellable explanation

## Risks And Mitigations

- Risk: the result drifts into a generic "confident finance creator" voice.
  - Mitigation: preserve specific sequencing, framing habits, and I-style social dynamics.
- Risk: removing personal watermark makes the style too flat.
  - Mitigation: keep the speed, contrast, gossip-adjacent framing, and repeatable punchline logic.
- Risk: the result overlaps with existing repo I-style entries.
  - Mitigation: emphasize friend-group spreadability, insider-decoder energy, and socially contagious explanation rather than comfort-first influence.
- Risk: analysis leaks biography.
  - Mitigation: describe only communication mechanics and reusable narrative moves.

## Deliverables

- `docs/superpowers/specs/2026-04-23-vivian-tu-distillation-design.md`
- `docs/superpowers/plans/2026-04-23-vivian-tu-distillation.md`
- `distilled/vivian-tu-perspective - I/analysis.md`
- `distilled/vivian-tu-perspective - I/SKILL.md`
