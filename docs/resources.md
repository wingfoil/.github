# WingFoil — resources for users

Everything the WingFoil projects have published for users, with where to find it.
[Back to the organization](https://github.com/wingfoil).

## WingFoil (CLI + MCP server)

| Resource | Where |
|---|---|
| npm package `wingfoil` (latest: 0.3.0) | [npmjs.com/package/wingfoil](https://www.npmjs.com/package/wingfoil) |
| Documentation site | [wingfoil.github.io/wingfoil](https://wingfoil.github.io/wingfoil/) |
| README and quick start | [README](https://github.com/wingfoil/wingfoil#readme) |
| User guide | [docs/user-guide.md](https://github.com/wingfoil/wingfoil/blob/main/docs/user-guide.md) |
| CLI reference | [docs/cli-reference.md](https://github.com/wingfoil/wingfoil/blob/main/docs/cli-reference.md) |
| Examples | [docs/examples/](https://github.com/wingfoil/wingfoil/tree/main/docs/examples) |
| Release notes, and upgrading a 0.2.x project | [CHANGELOG.md](https://github.com/wingfoil/wingfoil/blob/main/CHANGELOG.md) · [release v0.3.0](https://github.com/wingfoil/wingfoil/releases/tag/v0.3.0) (test results and coverage attached) · [GitHub releases](https://github.com/wingfoil/wingfoil/releases) |
| MCP server listings | [Glama](https://glama.ai/mcp/servers/wingfoil/wingfoil) · [AlternativeTo](https://alternativeto.net/software/wingfoil/) |

## WingFoil UI

A local web console for WingFoil-governed projects: it runs each project's own `wingfoil` CLI and
shows its Memory, DNA, directives, team and documentation in your browser. Latest release: v0.2.0,
on npm: run it with `npx wingfoil-ui` (Node ≥ 22.12).

It supports WingFoil 0.2.2 to 0.2.x: keep WingFoil 0.2.x in the projects you open with it for now
(a project on WingFoil 0.3 opens read-only). Support for WingFoil 0.3 is planned for v0.3.

| Resource | Where |
|---|---|
| v0.2.0 | [release v0.2.0](https://github.com/wingfoil/wingfoil-ui/releases/tag/v0.2.0) · [CHANGELOG](https://github.com/wingfoil/wingfoil-ui/blob/v0.2.0/CHANGELOG.md) |
| npm package `wingfoil-ui` | [npmjs.com/package/wingfoil-ui](https://www.npmjs.com/package/wingfoil-ui) |
| README, requirements, install and run | [README](https://github.com/wingfoil/wingfoil-ui#readme) |
| User guide | [docs/user-guide.md](https://github.com/wingfoil/wingfoil-ui/blob/main/docs/user-guide.md) |
| CLI reference | [docs/cli-reference.md](https://github.com/wingfoil/wingfoil-ui/blob/main/docs/cli-reference.md) |

## WingFoil Benchmark

A benchmark built and run by WingFoil's maintainer (validity threat T1): questions, metrics and
scenarios are fixed before any run, losses are published like wins, and every run's record, cost
and agent transcript are public, so the results can be checked and contested.

Latest: **v0.2 — Competitors**, preliminary results (scenarios S2, S3, S8 and both model slices ran
once per arm, only S1 three times). It compares a plain agent and WingFoil v0.3.0 with Spec Kit
v1.1.0 and OpenSpec 1.14.0 arms, set up from their official documentation under the same rules as
WingFoil.

| Resource | Where |
|---|---|
| v0.2 results (preliminary) | [reference campaign, WingFoil v0.3.0](https://wingfoil.github.io/wingfoil-benchmark/81ebb2691f9c/1/) · [bridge campaign, WingFoil v0.2.2](https://wingfoil.github.io/wingfoil-benchmark/bf3a1ac7dff5/1/) · [all results](https://wingfoil.github.io/wingfoil-benchmark/) |
| Method: every rule and its limits | [method page](https://wingfoil.github.io/wingfoil-benchmark/81ebb2691f9c/1/method.html) |
| v0.2 release notes | [docs/releases/v0.2.md](https://github.com/wingfoil/wingfoil-benchmark/blob/main/docs/releases/v0.2.md) · [release v0.2](https://github.com/wingfoil/wingfoil-benchmark/releases/tag/v0.2) (with errata) · agent transcripts attached to each campaign's release |
| v0.1 results (preliminary) | [results site](https://wingfoil.github.io/wingfoil-benchmark/c82a5e74885b/2/) · [docs/releases/v0.1.md](https://github.com/wingfoil/wingfoil-benchmark/blob/main/docs/releases/v0.1.md) |
| Run the suite yourself | [README](https://github.com/wingfoil/wingfoil-benchmark#readme) |
| Contest a setup | [issue form](https://github.com/wingfoil/wingfoil-benchmark/issues/new?template=contest-setup.yml) |

## WingFoil Templates

The first pack is published: **`base` 1.0.0**, the core of every project governed by WingFoil.
Foundation: `base` published, `software` next. `base` works with WingFoil 0.3.0; no released
WingFoil installs packs yet, so adopt it by hand, following the *Install and update* steps of its
README.

| Resource | Where |
|---|---|
| Pack catalog (Foundation row, install steps) | [CATALOG.md](https://github.com/wingfoil/wingfoil-templates/blob/main/CATALOG.md) |
| `base` 1.0.0 | [README at the tag `base@1.0.0`](https://github.com/wingfoil/wingfoil-templates/blob/base@1.0.0/packs/base/README.md) |
| Search the catalog | [wingfoil.github.io/wingfoil-templates](https://wingfoil.github.io/wingfoil-templates/) (follows `main`) |
| Pack format, for pack authors | [spec-001](https://github.com/wingfoil/wingfoil-templates/blob/main/docs/memory/tech-spec/spec-001-the-pack-format-manifest-fragments-composition-catalog-compatibility-and-digest.md) |

## Contributing

Contributions arrive as Memory elements (bug, decision-log, ADR, tech-spec) rather than code pull
requests: see [COLLABORATION.md](https://github.com/wingfoil/wingfoil/blob/main/COLLABORATION.md).
