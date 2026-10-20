# ACP brand skill

An Agent Skill that applies the Asu Capital Partners (ACP) and AG1 brand to decks, documents, charts, LP reports and pages. It follows the open Agent Skills format (a folder with a `SKILL.md`), so it works in any agent that reads skills.

## Install

Claude Code, Codex, Cursor, Gemini CLI and other agents that support skills:

```
npx skills add masonmeiws/acp-brand-skill
```

Or copy the `asu-brand` folder into your agent's skills folder, for example `~/.claude/skills/asu-brand`.

Claude on the web, desktop and mobile: download [asu-brand.zip](https://github.com/masonmeiws/acp-brand-skill/releases/latest/download/asu-brand.zip) and upload it in the skills section of Claude settings.

## Contents

- `asu-brand/SKILL.md`: the rules.
- `asu-brand/assets/logos/`: official logo files.
- `asu-brand/references/brand-guidelines.pdf`: the full guidelines.

## Use

Ask your agent for any ACP or AG1 material, for example "Make an ACP deck about Fund II" or "Chart this data in the ACP style". The agent loads the skill and applies it.

The ACP logo and names are the property of Asu Capital Partners. Use them only for work with or about ACP and AG1.
