# WingFoil — entry points for AI agents

What an AI agent should read to work with WingFoil projects.
[Back to the organization](https://github.com/wingfoil).

## Working in a project that uses WingFoil

- **Guide for agents:** [docs/agents.md](https://github.com/wingfoil/wingfoil/blob/main/docs/agents.md)
  — what WingFoil is, how to read a WingFoil project and how to change it without breaking its
  rules. It describes `main`; read it at the tag matching `wingfoil --version`.
- **MCP server** (stdio, read-only, ships in the `wingfoil` npm package). For Claude Code, at the
  repository root:

  ```json
  { "mcpServers": { "wingfoil": { "command": "wingfoil", "args": ["mcp"] } } }
  ```

- **Writes** go through the `wingfoil` CLI: [CLI reference](https://github.com/wingfoil/wingfoil/blob/main/docs/cli-reference.md).

## Pack catalog

Not published yet. A machine-readable index of WingFoil Templates' packs will be listed here when
the first pack is published.
