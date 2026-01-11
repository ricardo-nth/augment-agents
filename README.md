# Augment Sub-Agents

My custom sub-agents for [Augment Code](https://www.augmentcode.com/). Currently testing and iterating on these.

## Agents

| Agent | Model | Purpose |
|-------|-------|---------|
| **Explore** | Haiku 4.5 | Read-only research - searches codebase, reads files, fetches docs |
| **Git-Bot** | Haiku 4.5 | Git commits - single changes or batching into clean commit stacks |
| **Grunt** | Haiku 4.5 | Repetitive tasks - executes task lists across multiple files |
| **Oracle** | GPT 5.2 | Complex debugging - analyzes issues and returns implementation plans |
| **SWE** | Opus 4.5 | Senior engineer mode - diagnoses and fixes issues directly |

## Usage

Place these `.md` files in `~/.augment/agents/` and they'll be available as sub-agents in Augment Code.

## Status

Experimental - these are what I'm currently using and testing.
