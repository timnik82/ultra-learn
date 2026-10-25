# Ultra-learn

An AI agent skill for learning through active practice, targeted feedback, quizzes, and spaced review.

The learner does the thinking: recall, predict, explain, attempt, and try again after feedback. The skill distinguishes success today from retention demonstrated at a later review.

## What it supports

- Focused practice: quizzes, reasoning checks, and teach-back exercises.
- Continuing programmes: a learning map, observable pass criteria, and saved progress.
- Interview and real-world task simulations.
- Review cards based on corrected mistakes, with adjustable review intervals.

## Use

Place this directory in your AI agent's skills directory, preserving `SKILL.md`, `assets/`, and `references/`. Your agent must support Markdown skills; installation paths vary by tool.

Example prompts:

- “Use ultra-learn to quiz me on this chapter. Ask one question at a time.”
- “Help me learn statistics for interpreting experiments. Start by checking what I know.”
- “Let me explain this concept, then check my reasoning.”

For continuing programmes, the skill saves one Markdown record per topic in your chosen learning directory, or in `learning/` in the current workspace. Keep personal learning records outside the installed skill directory. Review dates in those files do not create automatic reminders.

## Files

- [SKILL.md](SKILL.md): agent instructions and learning workflow.
- [Topic template](assets/topic-template.md): progress, evidence, cards, and session log.
- [Example sessions](references/example-session.md): worked examples of applying the skill.
