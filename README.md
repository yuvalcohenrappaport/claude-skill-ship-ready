# Ship Ready — Claude Code Skill

Pre-completion readiness checker. Catches skipped tests, missing error handling, secrets hygiene gaps, and handoff issues before you call it done.

## Installation

```bash
claude install-skill https://github.com/yuvalcohenrappaport/claude-skill-ship-ready
```

## Usage

```
/ship-ready
/ship-ready <project-dir>
```

Runs a scope-appropriate readiness audit. Also triggers proactively before marking non-trivial work as complete.
