# Ultra-learn

An AI agent skill for learning through active practice, targeted feedback, quizzes, and spaced review.

The learner does the thinking: recall, predict, explain, attempt, and try again after feedback. The skill distinguishes success today from retention demonstrated at a later review.

## What it supports

- Focused practice: quizzes, reasoning checks, and teach-back exercises.
- Continuing programmes: a learning map, observable pass criteria, and saved progress.
- Interview and real-world task simulations.
- Review cards based on corrected mistakes, with adjustable review intervals.

## Use

Place this directory in your AI agent's skills directory, preserving `SKILL.md`, `assets/`, and `references/`. The skill follows the [Agent Skills](https://agentskills.io/specification) format. Known install locations:

| Tool | Personal (all projects) | Per repository | Invoke |
|------|-------------------------|----------------|--------|
| Claude Code | `~/.claude/skills/ultra-learn/` | `.claude/skills/ultra-learn/` | `/ultra-learn` or automatic |
| Codex | `~/.agents/skills/ultra-learn/` | `.agents/skills/ultra-learn/` | `$ultra-learn` or automatic |

Make sure `SKILL.md` sits directly inside `ultra-learn/`, with no extra wrapper folder. Codex's older `~/.codex/skills/` location is deprecated.

Example prompts:

- “Use ultra-learn to quiz me on this chapter. Ask one question at a time.”
- “Help me learn statistics for interpreting experiments. Start by checking what I know.”
- “Let me explain this concept, then check my reasoning.”

For continuing programmes, the skill saves one Markdown record per topic in your chosen learning directory, defaulting to a user-level folder such as `~/learning/` rather than the current working directory, so records do not end up inside code repositories. Keep personal learning records outside the installed skill directory. Review dates in those files do not create automatic reminders.

## Files

- [SKILL.md](SKILL.md): agent instructions and learning workflow.
- [Topic template](assets/topic-template.md): progress, evidence, cards, and session log.
- [Example sessions](references/example-session.md): worked examples of applying the skill.
