# WingFoil — resources for users

Everything the WingFoil projects have published for users, with where to find it.
[Back to the organization](https://github.com/wingfoil).

## WingFoil (CLI + MCP server)

| Resource | Where |
|---|---|
| npm package `wingfoil` (latest: 0.2.2) | [npmjs.com/package/wingfoil](https://www.npmjs.com/package/wingfoil) |
| README and quick start | [README](https://github.com/wingfoil/wingfoil#readme) |
| User guide | [docs/user-guide.md](https://github.com/wingfoil/wingfoil/blob/main/docs/user-guide.md) |
| CLI reference | [docs/cli-reference.md](https://github.com/wingfoil/wingfoil/blob/main/docs/cli-reference.md) |
| Examples | [docs/examples/](https://github.com/wingfoil/wingfoil/tree/main/docs/examples) |
| Release notes | [CHANGELOG.md](https://github.com/wingfoil/wingfoil/blob/main/CHANGELOG.md) · [GitHub releases](https://github.com/wingfoil/wingfoil/releases) |
| MCP server listings | [Glama](https://glama.ai/mcp/servers/wingfoil/wingfoil) · [AlternativeTo](https://alternativeto.net/software/wingfoil/) |

## WingFoil UI

A local web console for WingFoil-governed projects: it runs each project's own `wingfoil` CLI and
shows its Memory, DNA, directives, team and documentation in your browser. Latest release: v0.1.0,
a read-only console, released as a git tag. It is not published on npm: run it from a checkout of
the tag.

| Resource | Where |
|---|---|
| v0.1.0 (git tag) | [tag v0.1.0](https://github.com/wingfoil/wingfoil-ui/tree/v0.1.0) · [CHANGELOG](https://github.com/wingfoil/wingfoil-ui/blob/v0.1.0/CHANGELOG.md) |
| README, requirements, install and run | [README](https://github.com/wingfoil/wingfoil-ui#readme) |
| User guide | [docs/user-guide.md](https://github.com/wingfoil/wingfoil-ui/blob/main/docs/user-guide.md) |
| CLI reference | [docs/cli-reference.md](https://github.com/wingfoil/wingfoil-ui/blob/main/docs/cli-reference.md) |

## WingFoil Benchmark

The benchmark is built by WingFoil's maintainer: questions, metrics and scenarios are fixed before
any run, losses are published like wins, and every run's record, cost and agent transcript are
public, so the results can be checked and contested.

| Resource | Where |
|---|---|
| v0.1 results (preliminary) | [results site](https://wingfoil.github.io/wingfoil-benchmark/c82a5e74885b/2/) |
| Method: every rule and its limits | [method page](https://wingfoil.github.io/wingfoil-benchmark/c82a5e74885b/2/method.html) |
| v0.1 release notes | [docs/releases/v0.1.md](https://github.com/wingfoil/wingfoil-benchmark/blob/main/docs/releases/v0.1.md) · [releases](https://github.com/wingfoil/wingfoil-benchmark/releases) |
| Run the suite yourself | [README](https://github.com/wingfoil/wingfoil-benchmark#readme) |
| Contest a setup | [issue form](https://github.com/wingfoil/wingfoil-benchmark/issues/new?template=contest-setup.yml) |

## WingFoil Templates

No pack is published yet. For pack authors, the format is specified in
[spec-001](https://github.com/wingfoil/wingfoil-templates/blob/main/docs/memory/tech-spec/spec-001-the-pack-format-manifest-fragments-composition-catalog-compatibility-and-digest.md).
The pack catalog will be linked here when the first pack is published.

## Contributing

Contributions arrive as Memory elements (bug, decision-log, ADR, tech-spec) rather than code pull
requests: see [COLLABORATION.md](https://github.com/wingfoil/wingfoil/blob/main/COLLABORATION.md).
