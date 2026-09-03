# Upstream Absorption — Awesome AI Agents — 2026-09-03

## aaif-goose/goose — Apache-2.0
High-priority reference for an extensible MCP/agent runtime, local-model operation and custom/white-label distributions.

### Absorb/evaluate
- extension discovery and permission boundaries
- provider abstraction so local models remain possible
- MCP integration patterns
- tool execution audit trail
- custom distribution/branding architecture
- failure/cancellation semantics

Do not copy product branding. Keep proprietary extensions isolated and explicitly licensed.

## openai/codex — Apache-2.0 code
Reference for terminal coding-agent architecture, tool orchestration and repository workflows. The code is permissive, but provider/API operation may cost money, so no project should make paid inference mandatory merely because Codex code is open source.

## Acceptance rules
- local/free provider path remains possible where product requirements permit
- tool permissions are explicit and least-privilege
- every destructive action is auditable
- secrets never enter prompts/logs by default
- upstream version/license is recorded.