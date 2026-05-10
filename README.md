# opencode-skills

Custom skills and agents for [opencode](https://opencode.ai) CLI.

## Structure

```
opencode-skills/
├── skills/                  # opencode skills
│   ├── docx-edit/          # Edit .docx files preserving formatting
│   │   └── SKILL.md
│   └── github-sync/        # Sync skills/agents to GitHub
│       └── SKILL.md
└── agents/                  # opencode agents
    ├── playwright-webpage-capture.md
    └── github-sync.md
```

## Skills

| Skill | Description |
|-------|-------------|
| [docx-edit](skills/docx-edit/SKILL.md) | Edit existing .docx files while preserving original formatting using python-docx and docxedit libraries |
| [github-sync](skills/github-sync/SKILL.md) | Sync opencode skills and agents to the GitHub repository |

## Agents

| Agent | Description |
|-------|-------------|
| [playwright-webpage-capture](agents/playwright-webpage-capture.md) | Open websites using Playwright MCP tools and capture screenshots/snapshots |
| [github-sync](agents/github-sync.md) | Sync opencode skills and agents to GitHub using git and gh CLI |

## Installation

Copy the desired skill/agent folder into your opencode config directory:

```bash
# Skills
cp -r skills/docx-edit ~/.config/opencode/skills/

# Agents
cp agents/playwright-webpage-capture.md ~/.config/opencode/agents/
```

## License

MIT
