# Ramit Sethi Distillation Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a self-contained Ramit Sethi distillation package inside `C:\github\nuwa-skill`, including research notes, a study-oriented analysis document, and a directly usable Ramit perspective skill.

**Architecture:** Use high-confidence public primary sources, centered on Ramit's official site and official podcast materials, to synthesize recurring ideas into structured research notes. Then derive two final artifacts from that evidence: an analysis document for learning and a `SKILL.md` for direct usage. Keep all work self-contained under `distilled/ramit-sethi-perspective/`.

**Tech Stack:** Markdown documents, existing nuwa-skill templates, official web sources summarized into local research notes

---

### Task 1: Create Ramit Distillation Directory Skeleton

**Files:**
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\01-writings.md`
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\02-conversations.md`
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\03-expression-dna.md`
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\04-external-views.md`
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\05-decisions.md`
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\06-timeline.md`
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\SKILL.md`
- Create: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\ramit-sethi-analysis.md`

- [ ] **Step 1: Create the skeleton files with minimal headings**

Add each file with a top-level heading so later synthesis has stable targets.

- [ ] **Step 2: Verify the files exist**

Run: `Get-ChildItem 'C:\github\nuwa-skill\distilled\ramit-sethi-perspective' -Recurse`
Expected: output lists `SKILL.md`, `ramit-sethi-analysis.md`, and the six research markdown files

### Task 2: Gather And Synthesize Primary Source Material

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\01-writings.md`
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\02-conversations.md`
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\03-expression-dna.md`
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\04-external-views.md`
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\05-decisions.md`
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\06-timeline.md`
- Reference: `C:\github\nuwa-skill\docs\superpowers\specs\2026-04-22-ramit-sethi-distillation-design.md`

- [ ] **Step 1: Gather official source passages**

Read official pages covering Ramit's background, Rich Life, conscious spending, money scripts, money dials, couples money guidance, and official podcast index or episode materials.

- [ ] **Step 2: Write `01-writings.md`**

Summarize Ramit's recurring written frameworks:

- Rich Life
- conscious spending
- money dials
- money scripts
- automation
- high-leverage decisions

- [ ] **Step 3: Write `02-conversations.md`**

Capture how Ramit handles coaching, especially:

- partner money discussions
- shame and defensiveness
- avoidance
- behavior change through scripts and questions

- [ ] **Step 4: Write `03-expression-dna.md`**

Capture his tone, challenge style, directness, aspirational framing, anti-frugality posture, and content-hook habits.

- [ ] **Step 5: Write `04-external-views.md`**

Record carefully filtered external reception only if it adds signal without diluting primary-source grounding. If not needed, keep this thin and explicit.

- [ ] **Step 6: Write `05-decisions.md`**

Infer strategic choices Ramit appears to have made:

- choosing Rich Life over austerity branding
- choosing psychology plus systems over pure spreadsheet advice
- choosing couples and live coaching content as a public teaching surface

- [ ] **Step 7: Write `06-timeline.md`**

Record supported milestones from official bio and clearly supported public materials only.

- [ ] **Step 8: Review all six files for source discipline**

Check that the core claims come from official material and that weaker inferences are labeled as inference.

### Task 3: Write The Learning Analysis Document

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\ramit-sethi-analysis.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\01-writings.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\02-conversations.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\03-expression-dna.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\05-decisions.md`

- [ ] **Step 1: Draft the analysis outline**

Use sections for Rich Life, psychology, systems, couples, media voice, copyable methods, and caution points.

- [ ] **Step 2: Write the core analysis**

Explain how Ramit reframes money from guilt to intentionality, from tiny cuts to big moves, and from solitary finance to relational finance.

- [ ] **Step 3: Add a transferability section**

Separate durable methods from Ramit-specific branding or performance style.

- [ ] **Step 4: Review for usefulness**

Check that the document teaches reusable methods rather than merely summarizing his content.

### Task 4: Write The Ramit SKILL.md

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\SKILL.md`
- Reference: `C:\github\nuwa-skill\references\skill-template.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\01-writings.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\02-conversations.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\03-expression-dna.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\05-decisions.md`
- Reference: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\06-timeline.md`

- [ ] **Step 1: Define 3-6 validated mental models**

Only include models supported across multiple official sources, such as Rich Life, conscious spending, automation, high-leverage focus, money scripts, and relationship-aware finance.

- [ ] **Step 2: Define 6-10 decision heuristics**

Turn recurring Ramit-style moves into practical rules for personal finance analysis, couples communication, and behavior change.

- [ ] **Step 3: Write expression DNA**

Encode how he challenges bad scripts, normalizes desire, rejects penny-pinching obsession, and pushes direct action.

- [ ] **Step 4: Write values, anti-patterns, and honest boundaries**

Include what he pursues, what he rejects, and what the evidence does not support claiming.

- [ ] **Step 5: Write the full `SKILL.md`**

Use the nuwa template structure, but optimize for a broad Ramit operating system: psychology, systems, couples, and content framing.

- [ ] **Step 6: Review against sample prompts**

Mentally test prompts about spending guilt, automation, partner conflict, and aspirational money design to confirm the skill sounds like Ramit rather than generic finance advice.

### Task 5: Final Package Review

**Files:**
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\SKILL.md`
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\ramit-sethi-analysis.md`
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\01-writings.md`
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\02-conversations.md`
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\03-expression-dna.md`
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\04-external-views.md`
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\05-decisions.md`
- Review: `C:\github\nuwa-skill\distilled\ramit-sethi-perspective\references\research\06-timeline.md`

- [ ] **Step 1: Check spec coverage**

Confirm the final package includes both requested artifacts and covers the full-spectrum Ramit scope.

- [ ] **Step 2: Check file containment**

Confirm all created or modified files are under `C:\github\nuwa-skill`.

- [ ] **Step 3: Check for unsupported claims**

Remove or soften any biography, media, or behavior claims not grounded in the chosen source set.

## Self-Review

### Spec coverage

- The plan includes both required outputs: a directly usable skill and a separate study-oriented analysis document.
- The plan prioritizes official sources and allows only carefully filtered secondary material.
- The plan preserves the broad Ramit scope: money philosophy, systems, couples, and expression style.
- The plan keeps all work inside `C:\github\nuwa-skill`.

### Placeholder scan

- No `TODO`, `TBD`, or deferred placeholders remain.
- Steps use exact file paths and concrete source and synthesis actions.

### Type consistency

- Directory target is consistently `distilled/ramit-sethi-perspective/`.
- Final artifacts are consistently `SKILL.md` and `ramit-sethi-analysis.md`.
- Research filenames remain stable across all tasks.
