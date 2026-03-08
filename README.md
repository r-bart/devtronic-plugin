# devtronic — Claude Code Plugin Marketplace

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

Core workflow: `/devtronic:brief`, `/devtronic:spec`, `/devtronic:research`, `/devtronic:create-plan`, `/devtronic:execute-plan`, `/devtronic:generate-tests`, `/devtronic:summary`, `/devtronic:post-review`, `/devtronic:checkpoint`, `/devtronic:audit`, `/devtronic:investigate`, `/devtronic:learn`, `/devtronic:quick`, `/devtronic:scaffold`, and more.

Design phase: `/devtronic:design`, `/devtronic:design-research`, `/devtronic:design-define`, `/devtronic:design-ia`, `/devtronic:design-wireframe`, `/devtronic:design-spec`, `/devtronic:design-review`, `/devtronic:design-system`, and more.

### Agents (15)

`code-reviewer`, `test-generator`, `architecture-checker`, `quality-runner`, `error-investigator`, `commit-changes`, `dependency-checker`, `doc-sync`, `design-critic`, `ux-researcher`, `visual-qa`, `a11y-auditor`, `ia-architect`, `design-token-extractor`, `design-system-guardian`

### Hooks

- **SessionStart**: Quick project orientation
- **PostToolUse**: Auto-lint after file changes
- **Stop**: Quality gate before stopping
- **SubagentStop**: Validate subagent completion
- **PreCompact**: Auto-checkpoint before context compaction

## Links

- [devtronic CLI](https://github.com/r-bart/devtronic) — Full documentation and source
- [npm package](https://www.npmjs.com/package/devtronic)
