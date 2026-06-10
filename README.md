# feinai-plugin

Claude Code plugin for [feinai](https://github.com/mvisca/feinai) — coordination layer for multi-agent teams.

## Install

```bash
claude install mvisca/feinai-plugin
```

## Skills

| Skill | Purpose |
|---|---|
| `feinai-sdd` | Activates when `.tasca/tasca.db` exists — teaches Claude the workflow |
| `feinai-write-spec` | Writes spec + plan into feinai from a design conversation |
| `feinai-write-tasks` | Decomposes plan into atomic tasks with parallelism analysis |
| `feinai-dispatch` | Orchestrates subagents in isolated git worktrees |
| `feinai-implement` | Claims and executes one task end-to-end |

## Requirements

Install the feinai CLI first:

```bash
bun install -g feinai
```

Full docs: https://www.npmjs.com/package/feinai

