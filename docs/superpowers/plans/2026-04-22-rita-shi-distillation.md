# Rita Shi Distillation Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a self-contained Rita Shi distillation package inside `C:\github\nuwa-skill`, including research notes, a study-oriented analysis document, and a directly usable Rita communication skill.

**Architecture:** Use the user-provided transcript summary file as the primary evidence base, synthesize recurring patterns into structured research notes, then derive two final artifacts from that evidence: an analysis doc for learning and a `SKILL.md` for direct usage. Keep all work self-contained under a single `distilled/rita-shi-perspective/` directory so the package can be copied independently.

**Tech Stack:** Markdown documents, existing nuwa-skill templates, local transcript JSON input

---

### Task 1: Create Rita Distillation Directory Skeleton

**Files:**
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\01-writings.md`
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\02-conversations.md`
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\03-expression-dna.md`
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\04-external-views.md`
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\05-decisions.md`
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\06-timeline.md`
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\SKILL.md`
- Create: `C:\github\nuwa-skill\distilled\rita-shi-perspective\rita-shi-analysis.md`

- [ ] **Step 1: Create the skeleton files with minimal headings**

Add each file with a top-level heading so later synthesis has stable targets.

- [ ] **Step 2: Verify the files exist**

Run: `Get-ChildItem 'C:\github\nuwa-skill\distilled\rita-shi-perspective' -Recurse`
Expected: output lists `SKILL.md`, `rita-shi-analysis.md`, and the six research markdown files

- [ ] **Step 3: Commit**

```bash
git add distilled/rita-shi-perspective
git commit -m "chore: scaffold rita shi distillation package"
```

### Task 2: Synthesize Transcript Evidence Into Research Notes

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\01-writings.md`
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\02-conversations.md`
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\03-expression-dna.md`
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\04-external-views.md`
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\05-decisions.md`
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\06-timeline.md`
- Check input: `C:\github_whisper\whisper-main\outputs\rita_transcripts\base\combined_summary.json`

- [ ] **Step 1: Read the transcript source and list repeated themes**

Extract recurring claims, audience targeting, framing patterns, and self-positioning from the JSON summary file.

- [ ] **Step 2: Write `01-writings.md`**

Summarize long-form themes reconstructed from repeated topics such as tax, retirement, inheritance, family structure, and advisory identity.

- [ ] **Step 3: Write `02-conversations.md`**

Capture client-facing explanation moves, trust-building sequences, objections, CTA structure, and consultative framing.

- [ ] **Step 4: Write `03-expression-dna.md`**

Capture tone, cadence, sentence shape, repeated vocabulary, identity labels, rhetorical contrasts, and certainty profile.

- [ ] **Step 5: Write `04-external-views.md`**

Record that public search results were checked but excluded unless identity confidence is high. If no confirmed public profile is found, explicitly mark evidence as insufficient.

- [ ] **Step 6: Write `05-decisions.md`**

Infer business choices Rita appears to have made based on her own statements, such as content-first acquisition, consultative positioning, and category reframing.

- [ ] **Step 7: Write `06-timeline.md`**

Record only timeline items supported by transcript evidence, and mark anything inferred as inference.

- [ ] **Step 8: Review all six files for evidence discipline**

Check that high-confidence claims come from repeated transcript evidence and that uncertain claims are labeled as inference or omitted.

- [ ] **Step 9: Commit**

```bash
git add distilled/rita-shi-perspective/references/research
git commit -m "docs: add rita shi research notes"
```

### Task 3: Write The Learning Analysis Document

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\rita-shi-analysis.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\01-writings.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\02-conversations.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\03-expression-dna.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\05-decisions.md`

- [ ] **Step 1: Draft the analysis outline**

Use sections for positioning, trust-building, reframing method, conversion path, expression patterns, copyable moves, and caution points.

- [ ] **Step 2: Write the core analysis**

Explain how Rita moves from content to trust to consultation, and break down which communication patterns are repeatable for a learner.

- [ ] **Step 3: Add a "what to copy carefully" section**

Separate durable communication methods from claims that may depend on credentials, regulation, or Rita-specific personal branding.

- [ ] **Step 4: Review for usefulness**

Check that the document teaches transferable communication practice rather than simply praising Rita or summarizing transcripts.

- [ ] **Step 5: Commit**

```bash
git add distilled/rita-shi-perspective/rita-shi-analysis.md
git commit -m "docs: add rita shi communication analysis"
```

### Task 4: Write The Rita SKILL.md

**Files:**
- Modify: `C:\github\nuwa-skill\distilled\rita-shi-perspective\SKILL.md`
- Reference: `C:\github\nuwa-skill\references\skill-template.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\01-writings.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\02-conversations.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\03-expression-dna.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\05-decisions.md`
- Reference: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\06-timeline.md`

- [ ] **Step 1: Define 3-6 validated mental models**

Only include models supported by repeated transcript evidence, such as planning authority, structure-first selling, or identity-linked urgency if they survive synthesis.

- [ ] **Step 2: Define 6-10 decision heuristics**

Turn recurring Rita-style moves into practical rules the skill can apply in new broker communication scenarios.

- [ ] **Step 3: Write expression DNA**

Encode her phrasing habits, contrast patterns, audience targeting, certainty level, and CTA rhythm in a way that guides generation.

- [ ] **Step 4: Write values, anti-patterns, and honest boundaries**

Include what she appears to pursue, what she rejects, and what the evidence does not support claiming.

- [ ] **Step 5: Write the full `SKILL.md`**

Use the existing nuwa template structure, but optimize for client education and broker communication rather than generic strategic advice.

- [ ] **Step 6: Review against sample prompts**

Mentally test prompts about objections, trust-building, and short-video client education to confirm the skill sounds like a consultative broker rather than a generic finance coach.

- [ ] **Step 7: Commit**

```bash
git add distilled/rita-shi-perspective/SKILL.md
git commit -m "feat: add rita shi perspective skill"
```

### Task 5: Final Package Review

**Files:**
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\SKILL.md`
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\rita-shi-analysis.md`
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\01-writings.md`
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\02-conversations.md`
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\03-expression-dna.md`
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\04-external-views.md`
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\05-decisions.md`
- Review: `C:\github\nuwa-skill\distilled\rita-shi-perspective\references\research\06-timeline.md`

- [ ] **Step 1: Check spec coverage**

Confirm the final package includes both requested artifacts and that the emphasis remains on professional broker communication.

- [ ] **Step 2: Check file containment**

Confirm all created or modified files are under `C:\github\nuwa-skill`.

- [ ] **Step 3: Check for unsupported claims**

Remove or soften any biography or factual statements not grounded in the transcript source or high-confidence identity confirmation.

- [ ] **Step 4: Commit**

```bash
git add distilled/rita-shi-perspective
git commit -m "docs: finalize rita shi distillation package"
```

## Self-Review

### Spec coverage

- The plan includes both requested outputs: a directly usable skill and a separate study-oriented analysis document.
- The plan keeps user-provided transcripts as the primary evidence source.
- The plan includes explicit handling for uncertain public identity matches.
- The plan keeps all work inside `C:\github\nuwa-skill`.

### Placeholder scan

- No `TODO`, `TBD`, or deferred placeholders remain.
- Steps name exact file paths and expected outcomes.
- Testing is review-oriented because this is a documentation and skill-distillation task, not executable product code.

### Type consistency

- Directory target is consistently `distilled/rita-shi-perspective/`.
- Final artifacts are consistently `SKILL.md` and `rita-shi-analysis.md`.
- Research file names remain stable across all tasks.
