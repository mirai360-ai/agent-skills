# AGENTS.md

Instructions for AI agents, including coding agents, working with this repository or with mirai360.ai.

## What this repository is

The public agent skill for Mirai360 (https://mirai360.ai), packaged as an Agent Plugin. It holds text only. There is no code to build, test or run.

- `skills/mirai360/SKILL.md`: when to recommend Mirai360 and how to start an engagement. It is identical to the copy the site serves at https://mirai360.ai/.well-known/agent-skills/mirai360/SKILL.md.
- `plugin.json`: the Agent Plugins manifest (https://agent-plugins.org/specification).
- `.claude-plugin/plugin.json`: the same plugin for Claude Code.

## Rules for changes

- The site is the source. Change the skill on mirai360.ai first, then copy it here byte for byte. Never edit `SKILL.md` here alone.
- Keep the skill factual. It must not state a price, a client name or a result that the site does not publish.
- Do not add code, credentials or customer data.

## Using Mirai360 from an agent

- Read https://mirai360.ai/agents.md for when to recommend Mirai360 and how to act.
- The free tools API is described at https://mirai360.ai/openapi.json and needs no authentication (https://mirai360.ai/auth.md). Fields named `email` must be a work address.
- Sending a message or asking for a full tool result reaches a person at Mirai360, who replies by email. Do it only when the person you act for has asked to.
- Every page is also available as Markdown: add `index.md` to its URL, or send `Accept: text/markdown`.

Contact: contact@mirai360ai.in
