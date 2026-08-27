# Modular Social Banner Skills

Seven focused skills for a reusable AI-assisted social-banner workflow.

`brand-visual-system → social-banner-composition + banner-copy-structure → ai-art-direction → campaign-prompt-builder → visual-qa-review + brand-consistency-check`

| Skill | Responsibility |
|---|---|
| brand-visual-system | Reusable brand rules |
| social-banner-composition | Layout and hierarchy |
| banner-copy-structure | Headline, proof, CTA |
| ai-art-direction | Visual concept and hero image |
| campaign-prompt-builder | Consistent prompt variants |
| visual-qa-review | Clarity, accessibility, production QA |
| brand-consistency-check | Campaign alignment to brand rules |

## Installation

Keep this directory intact so the skills can load `shared/` via relative paths.

- **Codex-style:** copy the folder to `~/.codex/skills/` or a project skill directory, then point discovery to each `skills/*/SKILL.md` if needed.
- **Claude Code:** copy to `.claude/skills/social-banner-skills-modular`; retain `skills/` and `shared/`. Direct-folder installations must adjust each `../../shared/` path to `../shared/`.
- **Gemini CLI:** copy to a project-visible skill directory such as `.gemini/skills/social-banner-skills-modular` and register each `skills/*/SKILL.md` according to your installation's discovery configuration.

Use the flow above, but invoke only the skill needed. For example: update a campaign image with `brand-consistency-check` without rerunning copy or art direction.
