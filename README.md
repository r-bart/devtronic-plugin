# devtronic — Claude Code Plugin

[![npm version](https://img.shields.io/npm/v/devtronic)](https://www.npmjs.com/package/devtronic)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Agentic development toolkit for Claude Code. 35 skills, 15 agents, and workflow hooks for structured AI-assisted development.

## Install

In Claude Code:

```
/plugin marketplace add r-bart/devtronic-plugin
/plugin install devtronic@devtronic
```

Or via the CLI:

```bash
npx devtronic init .
```

## What's Included

### Skills (35)

**Orientation and Research**
`/brief`, `/research`, `/opensrc`

**Planning**
`/spec`, `/create-plan`

**Development**
`/scaffold`, `/setup`, `/investigate`, `/worktree`

**Execution**
`/quick`, `/execute-plan`

**Quality and Review**
`/audit`, `/post-review`, `/generate-tests`

**Session and Meta**
`/checkpoint`, `/summary`, `/backlog`, `/learn`, `/create-skill`, `/devtronic-help`

**Design Phase**
`/design`, `/design-research`, `/design-define`, `/design-ia`, `/design-wireframe`, `/design-system`, `/design-system-define`, `/design-system-audit`, `/design-system-sync`, `/design-audit`, `/design-review`, `/design-spec`

**Orchestration Addon**
`/briefing`, `/recap`, `/handoff`

### Agents (15)

`code-reviewer`, `test-generator`, `architecture-checker`, `quality-runner`, `error-investigator`, `commit-changes`, `dependency-checker`, `doc-sync`, `design-critic`, `ux-researcher`, `visual-qa`, `a11y-auditor`, `ia-architect`, `design-token-extractor`, `design-system-guardian`

### Hooks

- **SessionStart**: Quick project orientation
- **PostToolUse**: Auto-lint after file changes
- **Stop**: Quality gate before stopping
- **SubagentStop**: Validate subagent completion
- **PreCompact**: Auto-checkpoint before context compaction

## How It Works

This repository is a **Claude Code plugin marketplace**. It contains the skills, agents, and hooks that Claude Code fetches when you install the devtronic plugin.

Content is **auto-synced from the devtronic CLI** on each release. When you install the plugin, Claude Code fetches and caches this repository automatically — no manual updates needed.

## Contributing

This repository is auto-generated from the main devtronic CLI. Do not submit pull requests here — they will be overwritten on the next release.

To contribute, open issues or PRs on the source repo: [github.com/r-bart/devtronic](https://github.com/r-bart/devtronic)

## Links

- [devtronic CLI](https://github.com/r-bart/devtronic) — Full documentation and source
- [npm package](https://www.npmjs.com/package/devtronic)
