<p align="center"><img src="https://raw.githubusercontent.com/wingfoil/wingfoil/main/docs/assets/wingfoil-mark.svg" width="120" alt="WingFoil logo"></p>

<h1 align="center">WingFoil</h1>

<p align="center"><b>The repo-native record of intent and approvals for AI-assisted engineering —
validated, attributable, readable by any agent.</b></p>

WingFoil keeps your project's intent in git — tasks, specs, ADRs, decision logs, bugs — as typed
documents with their own state machines. Every approval records who decided and why, in the commit.
It works alongside the spec-driven tools and coding agents you already use, through a CLI and an
MCP server.

```bash
npm install -g wingfoil
wingfoil init --template Scrum
```

## Repositories

| Repository | What it is |
|------------|------------|
| [**wingfoil**](https://github.com/wingfoil/wingfoil) | The core: CLI + MCP server — Memory, DNA, Directives, Workflows |
| [**wingfoil-templates**](https://github.com/wingfoil/wingfoil-templates) | Versioned project templates, methodologies and directives that WingFoil consumes |
| [**wingfoil-ui**](https://github.com/wingfoil/wingfoil-ui) | Local web UI for WingFoil-governed projects, driving the `wingfoil` CLI |
| [**wingfoil-benchmark**](https://github.com/wingfoil/wingfoil-benchmark) | Measures where WingFoil makes a difference, against plain agents and other tools |

## Get involved

- 📦 [npm package](https://www.npmjs.com/package/wingfoil)
- 💬 [Discussions](https://github.com/wingfoil/wingfoil/discussions) — questions and ideas
- 🐞 [Issues](https://github.com/wingfoil/wingfoil/issues) — bugs and proposals
- 🤝 [How to contribute](https://github.com/wingfoil/wingfoil/blob/main/COLLABORATION.md) — through Memory, not (only) code

All repositories are MIT licensed.
