# LAUNCH CONTENT — ground skill
# Post in this order: Reddit r/ClaudeAI → Reddit r/cursor → Twitter/X → Hacker News

---

## [1] Reddit — r/ClaudeAI

Title:
I built a skill that forces Claude to research and plan BEFORE writing code — one command install

Body:
The #1 reason vibe coding sessions fail isn't Claude's code quality.
It's that we start building before we know what we're building.

I made `ground` — a Claude Code skill that activates before any project starts:

- Researches 5 real competitors (names, URLs, weaknesses)
- Finds failed similar projects so you don't repeat their mistakes
- Proposes complete architecture in ONE message — you approve, it locks
- Searches Dribbble/Awwwards for 10 real design references — you pick one, Claude builds to match
- Creates STATE.md, DECISIONS.md, DONE.md automatically

Install:
npx skills add halakou/ground

Then just say "build me X" — the protocol runs automatically before any code.

GitHub: https://github.com/halakou/ground

---

## [2] Reddit — r/cursor

Title:
Skill that prevents the "3 hours wasted, wrong architecture" problem

Body:
Built a pre-flight skill for Claude Code — also works in Cursor, Windsurf, any agent that reads SKILL.md.

Before any project it forces:
✓ Real competitor research (web search, not hallucinated)
✓ Architecture approval before any files are created
✓ Design references from Dribbble/Awwwards — you pick, Claude builds to match
✓ Workspace setup (STATE.md, DECISIONS.md, DONE.md)

One install: npx skills add halakou/ground

https://github.com/halakou/ground

---

## [3] Twitter / X

The real vibe coding problem isn't hallucinations or context windows.

It's starting to build before you know what you're building.

`ground` — a Claude Code skill that forces research, architecture approval, and real design references before line 1.

npx skills add halakou/ground

https://github.com/halakou/ground

---

## [4] Hacker News — Show HN

Title:
Show HN: ground – a Claude Code skill that enforces planning before code

Body:
Install: npx skills add halakou/ground

When you say "build me X", the skill runs automatically:

1. Web-searches 5 real competitors — names, URLs, their weaknesses
2. Finds 2 failed similar projects and why they failed
3. Proposes complete folder structure + stack in one message — waits for your approval — locks on approval
4. Searches Dribbble/Awwwards/Mobbin for 10 real UI references matching your category — you pick one — Claude builds to match it, not from imagination
5. Creates STATE.md, DECISIONS.md, DONE.md

Zero code. One markdown file. Changes agent behavior completely.

The insight: Claude Code skills are plain text. A well-structured SKILL.md is more powerful than most people realize.

https://github.com/halakou/ground
