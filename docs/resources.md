# WingFoil — resources for users

Everything the WingFoil projects have published for users, with where to find it.
[Back to the organization](https://github.com/wingfoil).

## WingFoil (CLI + MCP server)

Latest release: **v0.3.1** (2026-10-27). `workflow adopt` counts an element created without
`--workflow` as created by a step, `workflow rekey` follows a renamed phase, checks can be confirmed
by a person (`manual: true`), `init` scaffolds workflows the engine can guide, and every
configuration write raises the file's `version:`. Nothing breaks from 0.3.0; a project created by
0.3.0 gets the guided workflows by copying them from a fresh `init`.

| Resource | Where |
|---|---|
| npm package `wingfoil` (latest: 0.3.1) | [npmjs.com/package/wingfoil](https://www.npmjs.com/package/wingfoil) |
| Documentation site | [wingfoil.github.io/wingfoil](https://wingfoil.github.io/wingfoil/) |
| README and quick start | [README](https://github.com/wingfoil/wingfoil#readme) |
| User guide | [docs/user-guide.md](https://github.com/wingfoil/wingfoil/blob/main/docs/user-guide.md) |
| CLI reference | [docs/cli-reference.md](https://github.com/wingfoil/wingfoil/blob/main/docs/cli-reference.md) |
| Examples | [docs/examples/](https://github.com/wingfoil/wingfoil/tree/main/docs/examples) |
| Release notes, and upgrading from 0.3.0 or 0.2.x | [CHANGELOG.md](https://github.com/wingfoil/wingfoil/blob/main/CHANGELOG.md) · [release v0.3.1](https://github.com/wingfoil/wingfoil/releases/tag/v0.3.1) · [release v0.3.0](https://github.com/wingfoil/wingfoil/releases/tag/v0.3.0) (test results and coverage attached) · [GitHub releases](https://github.com/wingfoil/wingfoil/releases) |
| MCP server listings | [official MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=wingfoil) (`io.github.wingfoil/wingfoil` 0.3.0) · [Glama](https://glama.ai/mcp/servers/wingfoil/wingfoil) · [AlternativeTo](https://alternativeto.net/software/wingfoil/) |

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

A first comparison across agents: the baseline arm (a plain agent, no harness) on OpenAI's Codex
CLI 0.162.1 with three OpenAI models, compared with the Claude Code baseline of v0.2's reference
campaign, on its own page and never mixed with the Claude Code results. Preliminary (every group
ran once, S1 three times); its costs are API-equivalent, from a pinned price table.

Codex execution `13fda3099afa/1`: WingFoil against its docs control and the baseline, on
gpt-5.6-terra. **Erratum:** in 12 of the WingFoil arm's 27 steps, the turn after the approver's
reply ran on Codex's default model instead of Terra (fixed). The WingFoil arm is being rerun; the
baseline arms are unaffected.

| Resource | Where |
|---|---|
| Codex baseline, across agents (preliminary) | [results site, *Across agents*](https://wingfoil.github.io/wingfoil-benchmark/) |
| Codex execution `13fda3099afa/1` (with its erratum) | [execution page](https://wingfoil.github.io/wingfoil-benchmark/13fda3099afa/1/) |
| v0.2 results (preliminary) | [reference campaign, WingFoil v0.3.0](https://wingfoil.github.io/wingfoil-benchmark/81ebb2691f9c/1/) · [bridge campaign, WingFoil v0.2.2](https://wingfoil.github.io/wingfoil-benchmark/bf3a1ac7dff5/1/) · [all results](https://wingfoil.github.io/wingfoil-benchmark/) |
| Method: every rule and its limits | [method page](https://wingfoil.github.io/wingfoil-benchmark/81ebb2691f9c/1/method.html) |
| v0.2 release notes | [docs/releases/v0.2.md](https://github.com/wingfoil/wingfoil-benchmark/blob/main/docs/releases/v0.2.md) · [release v0.2](https://github.com/wingfoil/wingfoil-benchmark/releases/tag/v0.2) (with errata) · agent transcripts attached to each campaign's release |
| v0.1 results (preliminary) | [results site](https://wingfoil.github.io/wingfoil-benchmark/c82a5e74885b/2/) · [docs/releases/v0.1.md](https://github.com/wingfoil/wingfoil-benchmark/blob/main/docs/releases/v0.1.md) |
| Run the suite yourself | [README](https://github.com/wingfoil/wingfoil-benchmark#readme) |
| Contest a setup | [issue form](https://github.com/wingfoil/wingfoil-benchmark/issues/new?template=contest-setup.yml) |

## WingFoil Templates

Latest pack: **`base` 2.0.0**, the core of every project governed by WingFoil. Foundation: `base`
published, `software` next. `base` works with WingFoil 0.3.0; no released WingFoil installs packs
yet, so adopt it by hand, following the *Install and update* steps of its README.

`base` 2.0.0 (major, 2026-10-27): new defaults for `plan_id` (`{workflow}-{phase}-plan`) and
`retrospective_path` (`docs/retrospectives/`); `governance-evolution`'s `apply` produces
`.wingfoil/`. Projects on 1.0.0: see the README's *Updating from 1.0.0*. `base` 1.0.0 stays listed.

| Resource | Where |
|---|---|
| Pack catalog (Foundation row, install steps) | [CATALOG.md](https://github.com/wingfoil/wingfoil-templates/blob/main/CATALOG.md#pack-base) |
| `base` 2.0.0 | [README at the tag `base@2.0.0`](https://github.com/wingfoil/wingfoil-templates/blob/base@2.0.0/packs/base/README.md) (*Install and update*, *Updating from 1.0.0*) |
| Search the catalog | [wingfoil.github.io/wingfoil-templates](https://wingfoil.github.io/wingfoil-templates/) (follows `main`) |
| Pack format, for pack authors | [spec-001](https://github.com/wingfoil/wingfoil-templates/blob/main/docs/memory/tech-spec/spec-001-the-pack-format-manifest-fragments-composition-catalog-compatibility-and-digest.md) |

## Contributing

Contributions arrive as Memory elements (bug, decision-log, ADR, tech-spec) rather than code pull
requests: see [COLLABORATION.md](https://github.com/wingfoil/wingfoil/blob/main/COLLABORATION.md).
