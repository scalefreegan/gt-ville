# gt-ville

A [gastown](https://github.com/steveyegge/gastown) town instance for orchestrating multi-agent AI workflows across multiple projects.

## What's Inside

**Town Configuration**
- `mayor/` - The primary AI coordinator with full workspace context
- `deacon/` - Agent configuration for specialized tasks
- `settings/` - Global escalation and configuration files

**Project Rigs** (git-backed project containers)
- `beerai/` - Beer recipe AI project
- `beerxml_python/` - BeerXML parsing library
- `cv/` - Curriculum vitae management
- `agent_learn/` - Agent learning experiments

**Orchestration System**
- `.beads/` - Git-backed issue tracking with 30+ workflow formulas
- `.claude/` - Claude Code integration and handoff commands
- `plugins/` - Extensibility hooks

## Quick Start

```bash
# Prime the mayor with context
gt prime

# Check your work inbox
gt mail inbox

# View active rigs
gt rig list

# Find available work
bd ready

# Start autonomous patrol
gt patrol start
```

## About Gastown

This town uses gastown's multi-agent orchestration model to coordinate 4-30 Claude Code agents simultaneously. Work persists through git-backed hooks, enabling reliable coordination that survives crashes and context limits.

See [AGENTS.md](AGENTS.md) for agent-specific instructions and workflows.
