# ground

**The pre-flight skill for vibe coders.**

Everyone starts with `CLAUDE.md`. Nobody starts with a plan.

`ground` is a Claude Code skill that activates before your first line of code — research, architecture approval, design references, workspace setup. Automatically.

---

## Install

```bash
npx skills add halakou/ground
```

That's it. One command. Works globally across all your projects.

---

## What changes

**Before ground:**
You describe your idea → Claude starts building → 3 hours later: wrong design, unknown architecture, no plan.

**After ground:**
You describe your idea → Claude researches competitors, proposes architecture, finds 10 real design references, waits for your approval → then builds.

---

## What ground does automatically

**Phase 1 — Research**
Finds real competitors, failed similar projects, and defines your success metric. Shows you everything. Waits for approval.

**Phase 2 — Architecture lock**
Proposes complete folder structure, every dependency, explicit scope boundary. One message. One approval. Locked.

**Phase 3 — Design references**
Before any UI: searches Dribbble, Awwwards, Mobbin for 10 real examples. You pick one. Claude builds to match — not from imagination.

**Phase 4 — Workspace**
Creates `STATE.md`, `DECISIONS.md`, `DONE.md` automatically. You always know what's happening and why.

---

## Compatibility

Claude Code · Cursor · Windsurf · Copilot · any agent that reads SKILL.md files

---

## Also works with npx skills

```bash
# install
npx skills add halakou/ground

# verify
npx skills list
```

---

## License

MIT
