# WingFoil — entry points for AI agents

What an AI agent should read to work with WingFoil projects.
[Back to the organization](https://github.com/wingfoil).

## Working in a project that uses WingFoil

- **Guide for agents:** [docs/agents.md](https://github.com/wingfoil/wingfoil/blob/main/docs/agents.md)
  — what WingFoil is, how to read a WingFoil project and how to change it without breaking its
  rules. It describes `main`; read it at the tag matching `wingfoil --version`.
- **MCP server** (stdio, read-only, ships in the `wingfoil` npm package; listed on the
  [official MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=wingfoil)
  as `io.github.wingfoil/wingfoil`). For Claude Code, at the
  repository root:

  ```json
  { "mcpServers": { "wingfoil": { "command": "wingfoil", "args": ["mcp"] } } }
  ```

- **Writes** go through the `wingfoil` CLI: [CLI reference](https://github.com/wingfoil/wingfoil/blob/main/docs/cli-reference.md).

## Pack catalog

WingFoil Templates' published packs (first: `base` 1.0.0, for WingFoil 0.3.0). No released
WingFoil installs packs yet: an agent adopts a pack by hand, following the *Install and update*
steps of the pack's README at its tag.

- **Machine-readable index:** [catalog-index.json](https://raw.githubusercontent.com/wingfoil/wingfoil-templates/main/catalog-index.json)
- **Agent entry point:** [llms.txt](https://raw.githubusercontent.com/wingfoil/wingfoil-templates/main/llms.txt)
- **Human-readable catalog:** [CATALOG.md](https://github.com/wingfoil/wingfoil-templates/blob/main/CATALOG.md)
  · [search page](https://wingfoil.github.io/wingfoil-templates/) (follows `main`)
