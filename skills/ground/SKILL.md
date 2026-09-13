---
name: ground
description: >
  Activates before any new project begins. Runs a mandatory pre-flight
  protocol: deep research, architecture approval, design reference selection,
  and workspace setup. Use this skill when the user says "start a new project",
  "build me a", "create a", or begins describing something they want to build.
  Prevents the #1 vibe coding failure: building the wrong thing beautifully.
---

# GROUND — Pre-Flight Protocol

You are not allowed to write code yet. Read this entire file first.

---

## PHASE 1 — RESEARCH (required, no exceptions)

Search the web and present this to the human before anything else:

```
GROUND REPORT
─────────────────────────────────────────
Project: [what the human wants to build]

COMPETITORS FOUND:
[1] [Name] — [URL] — [Their weakness]
[2] [Name] — [URL] — [Their weakness]
[3] [Name] — [URL] — [Their weakness]

FAILED ATTEMPTS:
[1] [What was built] — [Why it failed]
[2] [What was built] — [Why it failed]

SUCCESS METRIC:
"This project succeeds when: ___"

DIFFERENTIATION:
"This will win because: ___"
─────────────────────────────────────────
Reply APPROVED to continue, or redirect me.
```

Do not proceed until the human replies.

---

## PHASE 2 — ARCHITECTURE LOCK (required, no exceptions)

Present the full plan in ONE message:

```
ARCHITECTURE PROPOSAL
─────────────────────────────────────────
Stack: [every technology, framework, library — and why]

Folder structure:
  /
  ├── [folder] — [what it contains]
  └── [file]   — [what it does]

Out of scope (will NOT be built):
  - [explicit boundary 1]
  - [explicit boundary 2]

First 3 actions after your approval:
  1. [exact action]
  2. [exact action]
  3. [exact action]
─────────────────────────────────────────
Reply APPROVED to lock this. No changes after approval.
```

Once approved: architecture is locked. Zero scope creep. Zero "while I'm at it."

---

## PHASE 3 — DESIGN REFERENCES (activates for any UI work)

Never generate UI from your imagination. Always follow this:

```
Step 1 — Tell the human:
"Finding design references for [component]. Searching now..."

Step 2 — Search Dribbble, Awwwards, Mobbin, Screenlane, Landbook
for 10 real examples matching the exact project category.

Step 3 — Present:
DESIGN REFERENCES — [component name]
──────────────────────────────────────
[1] [Name] — [URL] — [why it fits]
[2] [Name] — [URL] — [why it fits]
... up to 10

Which number? (or: "closest to X, adapted")

Step 4 — STOP. Wait for human's choice.

Step 5 — Build to match that reference. State:
"Building based on reference [N]: [name]"
```

---

## PHASE 4 — WORKSPACE SETUP (run once, automatically)

Create this structure immediately when starting any project. No asking:

```
[project-name]/
├── STATE.md      ← live status: done / in-progress / blocked
├── DECISIONS.md  ← every decision made + reason + date
└── DONE.md       ← completed tasks log with timestamps
```

Tell the human ONCE:
```
Workspace created at /[project-name]/
Tracking: STATE.md · DECISIONS.md · DONE.md
```

---

## RULES (always active)

**Zero-question policy:**
You have web search, documentation, and best practices available.
If you don't know something → look it up, decide, do it.
Never ask the human about things you can research.

**Two allowed interruptions:**
1. Phase 3: design reference choice
2. A decision with genuinely different outcomes for the human

Format for allowed interruptions:
```
DECISION NEEDED
Context: [2 sentences]
Option A: [outcome for the human]
Option B: [outcome for the human]
My recommendation: [A/B] — [one sentence why]
```

**Token awareness:**
- Never re-read files you already read this session
- After each phase: update STATE.md
- Prefer targeted edits over full rewrites
- Handle context limits silently — never mention them to the human

**Communication:**
Progress update (no reply needed): `✓ [done] → [next]`
Phase complete:
```
PHASE COMPLETE: [name]
Done: [bullets]
Next: [what starts now]
```

Never say "I'll need you to..." or "Could you provide..." or "As an AI..."
If you hit a wall → find another way. Log it in DECISIONS.md.
