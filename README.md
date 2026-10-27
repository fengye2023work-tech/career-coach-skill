# Career Coach — Strategic Direction Skill

An agent skill for **strategic career direction coaching** — the kind a good human career
coach does: challenging assumptions with evidence, mapping real constraints, diagnosing
job-search funnel problems, and converting vague multi-variable anxiety into one concrete
trade-off at a time.

Deliberately **not** a resume writer, interview drill sergeant, or cheerleader.

## What it does

- Grounds advice in your actual profile/history instead of generic frameworks
- Isolates the real binding constraint (role shape? proof gap? channel? geography?)
- Reasons about market structure: which layers commoditize, consolidate, or grow
- Diagnoses where your funnel leaks (screens vs. first rounds vs. finals) before prescribing
- Treats hard constraints — relationships, visas, language, culture tolerance — as
  first-class inputs to the math, not afterthoughts
- Challenges hedges and optionality hoarding, directly and neutrally

Style: direct, sharp, neutral, analytical, concise. Conversational, not document-shaped.

## What it is not

- Resume/LinkedIn writing, STAR-story excavation, interview mock loops
- Therapy (burnout and demotivation are treated as strategy inputs, not the topic)
- A source of invented market facts, salary figures, or visa rules — it flags what
  needs verification instead of guessing

## Install

The skill is a single `SKILL.md` file following the open
[SKILL.md convention](https://agentskills.io) — a folder with YAML frontmatter
(`name`, `description`) plus instructions.

**Claude Code** (user scope, available in every session):

```bash
mkdir -p ~/.claude/skills/career-coach
curl -o ~/.claude/skills/career-coach/SKILL.md \
  https://raw.githubusercontent.com/fengye2023work-tech/career-coach-skill/main/SKILL.md
```

Or project scope: copy `SKILL.md` into `.claude/skills/career-coach/`.

**Kimi Code**: copy into `~/.agents/skills/career-coach/`.

**Codex / other SKILL.md-compatible runtimes**: copy the folder into your runtime's
skills directory so it can see `SKILL.md`.

**claude.ai (web/desktop)**: zip the folder containing `SKILL.md`, then
Settings → Features → Skills → upload.

## Usage

Talk naturally once installed. Trigger examples:

- "Be my career coach — I'm deciding between two directions."
- "I keep getting interviews but failing the first round. Diagnose the funnel."
- "Should I take this offer or hold out? Help me think through the trade-offs."
- "I have a niche background and I'm not sure if it's an asset or an anchor."

## Related open-source work

This skill focuses on *strategic direction*. For complementary phases, see:

- [donslice/claude-career-coach](https://github.com/donslice/claude-career-coach) —
  no-fluff discovery: STAR excavation, capability mapping, narrative building
- [Jeff-Kazzee/career-coach](https://github.com/Jeff-Kazzee/career-coach) —
  evidence-first career operating system: funnel tracking, scorecards, templates

## License

MIT — see [LICENSE](LICENSE).
