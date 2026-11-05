# Hapax Research Lab

**Hapax Research Lab** builds instruments and software for inspecting claims about AI progress and governance, testing them against primary sources and experiments, and recording scored results — including misses — alongside what each result changes next.

The `hapax-systems` GitHub organization hosts the lab's public source repositories and data ledgers. Each repository is governed by its own `LICENSE`, `SECURITY.md`, and `SUPPORT.md` boundary files.

- **Research portal & register:** [hapaxresearch.com](https://hapaxresearch.com)
- **Research weblog & field notes:** [hapax.weblog.lol](https://hapax.weblog.lol)
- **Public profile:** [hapax.omg.lol](https://hapax.omg.lol)
- **Contact & disclosures:** [hrl-han@hapaxresearch.com](mailto:hrl-han@hapaxresearch.com) ([disclosure & correction policy](https://hapaxresearch.com/about/#contact))

## Public Architecture

| Repository | Role | License |
|---|---|---|
| [`reins`](https://github.com/hapax-systems/reins) | Terminal cockpit for observing and previewing a governed AI-agent delivery lifecycle (read and command-preview surface). | Business Source License 1.1 |
| [`hapax-constitution`](https://github.com/hapax-systems/hapax-constitution) | Constitutional governance specification, public metadata authority, and repository enforcement tooling (`hapax-sdlc`). | CC BY-NC-ND 4.0 (spec) / Apache-2.0 (`hapax-sdlc`) |
| [`hapax-spine`](https://github.com/hapax-systems/hapax-spine) | Source-available runtime mechanism behind Reins: append-only event ledgers, policy-backed routing, capability receipts, and quota tracking. | Business Source License 1.1 |
| [`hapax-research-ledger`](https://github.com/hapax-systems/hapax-research-ledger) | Public-domain numeric evidence ledger recording observations, controlled vocabularies, content hashes, and methodological caveats. | CC0-1.0 |

### Experimental & Supporting Repositories

- [`hapax-mcp`](https://github.com/hapax-systems/hapax-mcp) — Experimental research tooling: local Model Context Protocol (`stdio`) bridge connecting MCP clients to an existing Logos API deployment (MIT).
- [`hapax-assets`](https://github.com/hapax-systems/hapax-assets) — Static publication and brand asset mirror with per-asset provenance and license notices ([Pages mirror](https://hapax-systems.github.io/hapax-assets/)).
- *Historical archive:* `agentgov` is retired and archived for historical reference only; active governance rules and enforcement tooling live in [`hapax-constitution`](https://github.com/hapax-systems/hapax-constitution).

## Operating Commitments & Scope

1. **Position, test, score, implication:** Claims are stated with explicit thresholds before testing and scored regardless of direction. Corrections and misses remain part of the permanent public record at [hapaxresearch.com](https://hapaxresearch.com).
2. **Explicit capability ceilings:** Public repositories document what is shipped today (`reins` read and command-preview, `hapax-spine` mechanism modules, `hapax-constitution` specifications, `hapax-research-ledger` data) without claiming autonomous write authority or staffed product support.
3. **Repository-scoped licensing:** Rights granted in one repository do not imply rights across any other repository or trademark of Hapax Research Lab.
4. **Support & intake boundary:** Public repositories are published for inspection, verification, and citation rather than community pull-request intake or issue-queue support. Send security disclosures or factual correction proposals to [hrl-han@hapaxresearch.com](mailto:hrl-han@hapaxresearch.com).
