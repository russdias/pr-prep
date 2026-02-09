# pr-prep

An [Agent Skill](https://agentskills.io/) that analyzes your code changes and generates PR titles, commit messages, and PR descriptions.

## Installation

```bash
npx skills add russdias/pr-prep
```

## What it does

When triggered, the agent will:

1. Inspect your branch's diffs, changed files, and commit history
2. Determine the type of change (feat, fix, refactor, etc.)
3. Generate a **commit message**, **PR title**, and **PR description** using [Conventional Commits](https://www.conventionalcommits.org/) format

## Triggers

The skill activates when you say things like:

- "Prepare my PR"
- "Write a commit message"
- "Summarize my changes"
- "Generate a PR description"

## Compatibility

Works with any agent that supports the [Agent Skills](https://agentskills.io/) format, including Claude Code, Cursor, GitHub Copilot, Gemini CLI, and others.

## License

MIT
