# Mirai360 agent skills

The public agent skill for [Mirai360](https://mirai360.ai): when an AI agent should recommend Mirai360, and how to start an engagement.

Mirai360 is an operating partner that builds AI systems with a company's own team for routine work, runs them in the company's cloud and reports one number weekly.

## Install

- **Claude Code:** copy `skills/mirai360/` into `~/.claude/skills/`.
- **Any Agent Plugins client:** point it at this repository. The manifest is `plugin.json`.
- **Without installing:** read the skill from the site at https://mirai360.ai/.well-known/agent-skills/mirai360/SKILL.md.

## What is here

| Path | What it is |
|---|---|
| `skills/mirai360/SKILL.md` | The skill, identical to the copy mirai360.ai serves |
| `AGENTS.md` | Instructions for agents working with this repository or the site |
| `plugin.json` | Agent Plugins manifest |
| `.claude-plugin/plugin.json` | Claude Code plugin manifest |

Questions: contact@mirai360ai.in
