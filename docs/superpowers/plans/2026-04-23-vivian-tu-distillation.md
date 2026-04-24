# Vivian Tu Distillation Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a self-contained Vivian Tu I-style distillation package inside `C:\github\nuwa-skill` that preserves social pull, story-led momentum, and conversational spreadability while removing personal history, personal watermark, and identity-led authority.

**Architecture:** Use the approved design spec plus high-signal public materials to extract only reusable communication mechanics. Compress those mechanics into two final artifacts: an `analysis.md` for studying the style and a `SKILL.md` for directly using the anonymous perspective. Keep the final package intentionally distinct from the repo's softer, steadier money voices by emphasizing social charisma, punchy reframes, and retellable explanation.

**Tech Stack:** Markdown documents, existing nuwa-skill distilled conventions, public-source synthesis written only into local final artifacts

---

### Task 1: Create The Vivian Distillation Package Skeleton

**Files:**
- Create: `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\analysis.md`
- Create: `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\SKILL.md`
- Reference: `C:\github\nuwa-skill\docs\superpowers\specs\2026-04-23-vivian-tu-distillation-design.md`

- [ ] **Step 1: Create the target directory and empty output files**

Create `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\` with two files only: `analysis.md` and `SKILL.md`.

- [ ] **Step 2: Verify the skeleton exists**

Run: `Get-ChildItem 'C:\github\nuwa-skill\distilled\vivian-tu-perspective - I'`
Expected: output lists only `analysis.md` and `SKILL.md`

### Task 2: Write The Study-Oriented Analysis Document

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\analysis.md`
- Reference: `C:\github\nuwa-skill\docs\superpowers\specs\2026-04-23-vivian-tu-distillation-design.md`
- Reference: `C:\github\nuwa-skill\distilled\erika-kullberg-perspective - I\erika-kullberg-analysis.md`
- Reference: `C:\github\nuwa-skill\distilled\her-first-100K-perspective - S\analysis.md`

- [ ] **Step 1: Draft the analysis outline**

Use sections for:

- positioning in one line
- what is actually distinct in this I-style
- how the storytelling engine works
- what makes the influence socially contagious
- what to copy
- what to remove

- [ ] **Step 2: Write the core analysis**

Explain the style as a communication system centered on:

- socially sticky hooks
- friend-group conversational energy
- quick reframes
- insider-decoder framing
- repeatable punchlines
- movement from attention to action

- [ ] **Step 3: Add the differentiation layer**

Explicitly distinguish this package from nearby repo patterns:

- not reassurance-first S-style guidance
- not pure emotional accompaniment
- not generic "confident finance creator" delivery

- [ ] **Step 4: Add the removal layer**

Explicitly remove:

- personal background
- career story
- family story
- brand wrapper
- self-labeling
- source-specific catchphrases

- [ ] **Step 5: Review for study value**

Run: `Get-Content 'C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\analysis.md'`
Expected: document teaches reusable communication mechanics instead of biography

### Task 3: Write The Anonymous I-Style SKILL.md

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\SKILL.md`
- Reference: `C:\github\nuwa-skill\distilled\erika-kullberg-perspective - I\SKILL.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective -D+C\SKILL.md`
- Reference: `C:\github\nuwa-skill\docs\superpowers\specs\2026-04-23-vivian-tu-distillation-design.md`

- [ ] **Step 1: Write YAML frontmatter and positioning**

Define an anonymous perspective name and a description that emphasizes:

- I-style influence
- money communication
- conversational charisma
- shareable reframes
- action-driving explanation

- [ ] **Step 2: Write role-play rules**

Encode response behavior that:

- uses first-person without self-identification
- does not self-introduce with credentials
- does not rely on biography for persuasion
- opens with a hook, contrast, or socially magnetic framing
- makes dense money topics feel conversational and easy to pass along

- [ ] **Step 3: Write 4-6 core mental models**

Center them on:

- attention through social relevance
- money as a decoded game rather than a dry lecture
- high-contrast reframing
- friend-to-friend explanation
- memorable takeaway compression
- immediate action momentum

- [ ] **Step 4: Write 8-10 decision heuristics**

Turn recurring moves into practical rules such as:

- start where people would gossip, not where textbooks would define
- make the hidden rule visible fast
- compress the lesson into a line someone could repeat later
- keep the pace high, but avoid shame spirals
- end with a specific move, not just a vibe

- [ ] **Step 5: Write expression DNA**

Capture:

- pacing
- sentence style
- contrast usage
- direct-address habits
- social spreadability
- light theatricality without branding mimicry

- [ ] **Step 6: Write values, anti-patterns, and honest boundaries**

Forbid:

- autobiography-led proof
- identity watermarking
- biography as authority
- generic hype with no actionable substance
- unsupported real-time financial certainty

- [ ] **Step 7: Review against the user constraint**

Run: `Get-Content 'C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\SKILL.md'`
Expected: no personal history, no personal identifiers, no branded self-wrapper

### Task 4: Run The Distillation Quality Checks

**Files:**
- Review: `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\analysis.md`
- Review: `C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\SKILL.md`

- [ ] **Step 1: Run the anonymity check**

Run: `Select-String -Path 'C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\analysis.md','C:\github\nuwa-skill\distilled\vivian-tu-perspective - I\SKILL.md' -Pattern 'Wall Street|JPMorgan|BuzzFeed|immigrant|Baltimore|college|book|podcast|Your Rich BFF|Vivian'`
Expected: no matches that survive into the final package

- [ ] **Step 2: Run the overlap check**

Read both files and confirm the engine is:

- faster than the S-style package
- less emotionally cushioning than the S-style package
- more socially magnetic and retellable than nearby repo entries

- [ ] **Step 3: Run the repo containment check**

Run: `Get-ChildItem 'C:\github\nuwa-skill\distilled\vivian-tu-perspective - I' -Recurse`
Expected: only files inside `C:\github\nuwa-skill`

- [ ] **Step 4: Run the final usefulness check**

Confirm both files answer two different jobs:

- `analysis.md` helps the user study the style
- `SKILL.md` lets the user directly invoke the style

## Self-Review

### Spec coverage

- The plan produces the two approved artifacts only: `analysis.md` and `SKILL.md`.
- The plan explicitly centers the I-style portion the user asked to learn.
- The plan explicitly removes personal information, personal experience, and personal watermark.
- The plan keeps all writes inside `C:\github\nuwa-skill`.

### Placeholder scan

- No `TODO`, `TBD`, or deferred placeholders remain.
- All file paths are exact.
- Verification steps include exact commands and expected outcomes.

### Type consistency

- The directory target is consistently `distilled\vivian-tu-perspective - I`.
- The two final artifact names are consistently `analysis.md` and `SKILL.md`.
- The spec and plan paths are consistent with the approved design flow.
