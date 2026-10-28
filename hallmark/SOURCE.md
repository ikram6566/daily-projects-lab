# SOURCE — hallmark

- **Original repo:** https://github.com/nutlope/hallmark
- **Original author / credit:** Nutlope (Hallmark contributors) — made by Together AI. All credit for the original work belongs to them; this folder is a mirror inside the Daily Projects Lab.
- **License:** MIT (see `LICENSE` in this folder — copied from the original repo). MIT allows copying with the license and copyright notice kept, which is done here.
- **Date copied:** 2026-10-28
- **Queue entry:** #1, category "AI Agents, LLM & Chatbots"
- **Mode:** copied (same copy, not rewritten)

## What this project is

Hallmark is an anti-AI-slop design skill for Claude Code, Cursor, Codex and OpenCode: it deals one of fifty design themes, builds a self-contained page around the visitor's job, and lints the result in a real browser against machine-made tells (eyebrow above every heading, tracked-capital labels, one coloured word in a headline, empty frames, etc.). Install: `npx skills add nutlope/hallmark -g`.

## What was copied — and one honest exclusion

Copied verbatim from the original repo (commit 6033bab2a8051b5454552d2e8e6cb8f27c483a42, checked 2026-10-28):

- `skills/hallmark/` — the complete skill: SKILL.md, scripts (theme dealer, sloplint, install), agents, references incl. all 50 themes (`.md` + preview `.jpg` each)
- `eval/` — the evaluation harness
- `docs/` — screenshots
- `.claude-plugin/`, `.github/workflows/`
- Root `README.md`, `LICENSE`, `ROADMAP.md`, `package.json`, `vercel.json`

**Excluded:** `site/` — the usehallmark.com marketing website (627 files, ~57 MB, mostly generated theme-preview pages). It is not part of the working skill; the full original repo linked above contains it. Everything needed to install and run the skill is present here.

## Demo run (2026-10-28, this mirror)

`node skills/hallmark/scripts/sloplint.mjs` was run against a small sample page (see `DEMO.md`): static checks pass/fail output recorded there. The skill's scripts run as-is from this copy.
