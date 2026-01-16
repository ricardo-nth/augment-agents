# Augment Sub-Agents

My custom sub-agents for [Augment Code](https://www.augmentcode.com/). Currently testing and iterating on these.

## Agents

| Agent | Model | Purpose |
|-------|-------|---------|
| **Explore** | Haiku 4.5 | Read-only research - searches codebase, reads files, fetches docs |
| **Grunt** | Haiku 4.5 | Repetitive tasks - executes task lists across multiple files |
| **Check** | Haiku 4.5 | Pre-commit verification - runs build, tests, lint |
| **Git-Bot** | Haiku 4.5 | Git commits - single changes or batching into clean commit stacks |
| **Vercel-Bot** | Haiku 4.5 | Deploys to Vercel and returns preview URLs |
| **Oracle** | GPT 5.2 | Complex debugging - analyzes issues and returns implementation plans |
| **SWE** | Opus 4.5 | Senior engineer mode - diagnoses and fixes issues directly |

## Swarm Philosophy

The cheap Haiku agents (Explore, Grunt, Check, Git-Bot, Vercel-Bot) should be spawned liberally and in parallel. The main agent orchestrates while sub-agents do the work. Oracle and SWE are escalation paths for harder problems.

See `~/.augment/rules/subagents.md` for trigger heuristics, anti-patterns, and workflow patterns.

## Usage

Place these `.md` files in `~/.augment/agents/` and they'll be available as sub-agents in Augment Code.

## Status

Experimental - these are what I'm currently using and testing.
