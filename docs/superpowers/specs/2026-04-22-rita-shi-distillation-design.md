# Rita Shi Distillation Design

## Goal

Create two artifacts inside `C:\github\nuwa-skill` for the Chinese insurance broker Rita Shi:

1. A directly usable character skill focused on Rita's communication and advisory style as a professional broker.
2. A companion analysis document that breaks down her communication system so the user can study and reuse it.

The primary learning goal is not generic insurance analysis. It is to learn how Rita communicates as a high-performing broker: how she frames problems, earns trust, creates urgency, and turns content into consultation.

## Scope

### In scope

- Distill Rita primarily from the user-provided `combined_summary.json` transcript collection.
- Supplement with public information only when there is high confidence that the material refers to the same Rita Shi.
- Build a Rita skill that is useful for:
  - practicing broker-style communication
  - studying trust-building language
  - generating Rita-style client education and sales framing
- Write an analysis document focused on reusable communication patterns.

### Out of scope

- Deep legal, tax, or compliance validation of Rita's claims
- Treating uncertain public search results as evidence
- Writing anything outside `C:\github\nuwa-skill`
- Building a generic financial-planning skill detached from Rita's communication identity

## Source Strategy

### Primary source

- `C:\github_whisper\whisper-main\outputs\rita_transcripts\base\combined_summary.json`

### Secondary source rule

- Public material may be used only if identity match is high confidence.
- If identity cannot be confirmed, exclude it from evidence and note that exclusion.

### Evidence labeling

Each conclusion should be tagged mentally during synthesis as one of:

- High confidence: repeated across multiple transcript items
- Medium confidence: present clearly in one substantial item and consistent with the rest
- Low confidence: plausible but weakly supported; keep out of core model sections or label as inference

## Output Design

## Artifact 1: Rita skill

Location:

- `C:\github\nuwa-skill\distilled\rita-shi-perspective\SKILL.md`

Supporting research folder:

- `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\`

The skill should emphasize:

- professional broker identity over product peddling
- consultative sales framing
- content-led trust building
- emotionally resonant but structured explanation
- client-facing Chinese communication patterns

The skill should include:

- identity card
- 3-6 core mental models
- 6-10 decision heuristics
- expression DNA
- value system and anti-patterns
- honest boundaries

The role behavior should be adapted for useful execution:

- sound recognizably like Rita's public communication style
- preserve her framing habits and rhetorical structure
- avoid exaggerated imitation or unsupported biography

## Artifact 2: analysis document

Location:

- `C:\github\nuwa-skill\distilled\rita-shi-perspective\rita-shi-analysis.md`

The analysis should explain:

- how Rita positions herself
- how she reframes insurance into tax, structure, safety, and family control
- how she converts abstract planning into vivid personal stakes
- how she uses identity language to attract specific audiences
- how her content creates trust before a sales conversation
- what a learner can copy safely, and what should be treated carefully

## Research Structure

To keep the skill self-contained, store distilled research under:

- `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\01-writings.md`
- `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\02-conversations.md`
- `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\03-expression-dna.md`
- `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\04-external-views.md`
- `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\05-decisions.md`
- `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\06-timeline.md`

Given the currently reliable material, these files will be adapted as follows:

- `01-writings.md`: long-form positions reconstructed from recurring content themes
- `02-conversations.md`: client-facing explanatory moves and objection handling patterns
- `03-expression-dna.md`: vocabulary, cadence, repeated framing, rhetorical habits
- `04-external-views.md`: only confirmed public references, otherwise marked as insufficient evidence
- `05-decisions.md`: inferred business decisions from her own self-description, labeled carefully
- `06-timeline.md`: only facts supported by the transcripts or high-confidence public confirmation

## Approach Options Considered

### Option 1: Expression-only distillation

Focus almost entirely on surface tone and copyable scripts.

Pros:

- fastest
- immediately useful for mimicry practice

Cons:

- too shallow
- risks becoming style cosplay instead of transferable skill

### Option 2: Advisor-framework distillation

Focus on strategic advisory thinking and reduce role-style content.

Pros:

- strong for case analysis

Cons:

- misses the user's main goal of learning broker communication

### Option 3: Dual-layer distillation

Build a communication-first skill plus an explicit analysis document of the communication system.

Pros:

- directly serves both use and study
- separates role execution from explanatory breakdown
- best fit for the user's stated goal

Cons:

- more synthesis work

Recommended option: Option 3.

## Extraction Hypotheses

Based on the transcript sample already inspected, the likely stable patterns to verify are:

- Rita sells planning authority, not insurance products first.
- She frames financial products as structural tools inside a family system.
- She repeatedly converts tax, retirement, inheritance, and protection topics into identity-level consequences.
- She uses short, high-certainty, high-stakes statements to create urgency.
- She differentiates herself from traditional brokers through content, trust, and advisory posture.
- She speaks especially strongly to Chinese immigrant families, women, mothers, and high-income professionals.

These will only become core skill models if they survive repeated evidence checks across the transcript set.

## Testing Strategy

The skill draft should be checked against realistic prompts such as:

- "How would Rita explain why a high-income immigrant family should care about tax structure before buying products?"
- "How would Rita respond to a client who says insurance is just an expense?"
- "How would Rita create trust in a first-touch educational short video?"
- "How would Rita guide a hesitant client from fear to action?"

Success criteria:

- answers sound like a consultative broker rather than a generic AI finance coach
- recurring Rita-style framing appears naturally
- output remains useful even when specific factual claims are uncertain

## Risks And Mitigations

- Risk: transcript summaries may contain transcription noise.
  - Mitigation: rely on repeated patterns, not isolated wording.
- Risk: external search may match the wrong Rita Shi.
  - Mitigation: exclude low-confidence public references entirely.
- Risk: overfitting to sales rhetoric.
  - Mitigation: separate expression patterns from stronger mental-model claims.
- Risk: making factual claims about her background that are not verified.
  - Mitigation: keep biography sparse and evidence-based.

## Deliverables

Inside `C:\github\nuwa-skill`:

- `docs/superpowers/specs/2026-04-22-rita-shi-distillation-design.md`
- `distilled/rita-shi-perspective/SKILL.md`
- `distilled/rita-shi-perspective/rita-shi-analysis.md`
- `distilled/rita-shi-perspective/references/research/01-writings.md`
- `distilled/rita-shi-perspective/references/research/02-conversations.md`
- `distilled/rita-shi-perspective/references/research/03-expression-dna.md`
- `distilled/rita-shi-perspective/references/research/04-external-views.md`
- `distilled/rita-shi-perspective/references/research/05-decisions.md`
- `distilled/rita-shi-perspective/references/research/06-timeline.md`

## Review Notes

This design intentionally treats the user-provided transcripts as the center of gravity. It aims to produce a skill that is useful for learning Rita's client communication system without pretending we know more about her than the evidence supports.
