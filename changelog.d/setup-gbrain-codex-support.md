---
bump: minor
---
Add Codex CLI bearer token support for setup-gbrain remote MCP.

### Added
- Wire Codex CLI in `/setup-gbrain` Path 4 (Remote MCP) to persist bearer tokens in `~/.codex/gstack/gbrain-mcp.env` and register via `--bearer-token-env-var GBRAIN_MCP_TOKEN` without requiring interactive OAuth login.
- Structural contract tests for Codex CLI Path 4 MCP configuration.
