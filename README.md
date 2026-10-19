# Demo-Skill

**Demo MCP, reimagined as a portable skill for Manus Cue.**

Inspired by [Errordevz/demo-mcp](https://github.com/Errordevz/demo-mcp), this repository translates its core working philosophy into reusable agent instructions: discover tools, research carefully, inspect real browser/media evidence, work systematically with code and data, verify results, and report limitations honestly.

## What's inside

- **SKILL.md** — main skill definition and workflow router
- **references/research.md** — source-backed research and fact-checking
- **references/browser.md** — dynamic browser workflows and safe actions
- **references/media.md** — honest video, image, and transcript analysis
- **references/developer.md** — repository reconnaissance, implementation, and verification
- **references/data.md** — document/data quality and analysis
- **references/security.md** — authorized static-first security analysis
- **examples/prompts.md** — example tasks

## No secrets required

The skill has no API-key configuration and does not require credentials. It uses only tools and permissions already available to the agent. If a tool needs an account or authorization, use the platform's native consent/sign-in flow; the skill does not bypass it.

## Important distinction

This is **not an MCP server** and does not install runtime capabilities. It cannot independently create a browser, fetch private resources, inspect video frames, run code, or call APIs. It guides Cue to use available tools, verify outcomes, and be explicit when a capability is unavailable.

## Install

Import this repository as a skill in the target agent platform if it supports repository-based skills. The entry point is **SKILL.md**. If the platform requires a different folder layout or manifest, adapt the packaging to that platform's current importer requirements.

## Design principles

- Tool discovery before action
- Evidence over assumptions
- Real frames/transcripts over metadata-only claims
- Read-only inspection before side effects
- No secret collection or credential leakage
- Explicit authorization for consequential actions
- Verification before reporting success

## License

MIT. See [LICENSE](LICENSE).