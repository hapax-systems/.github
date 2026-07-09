# Hapax Systems

Hapax Systems publishes evidence-bound software for governing AI-agent work: authority before action, receipts before claims, and visible limits instead of unsupported automation claims. The practical value is legibility: operators, reviewers, researchers, and adopters can see what is shipped, what is reserved, and what evidence would have to exist before a stronger claim is allowed.

The public portfolio is intentionally split by value surface. Some parts are open adoption commons, some are source-available commercial core, and some are source-visible research apparatus. The license on each repository is the authority for that repository; do not infer broader rights from the portfolio.

## Public Entry Points

| Surface | What to expect | Reader value | License posture |
|---|---|---|---|
| [reins](https://github.com/hapax-systems/reins) | Product front-door cockpit for observing and previewing governed AI-agent delivery state. | Lets operators and technical buyers see what an agent estate is doing and what a write would request before granting write authority. | Source-available under Business Source License 1.1; not open source until the change license/date applies. Self-hosted evaluation is invited within the BSL grant; competing hosted-service rights are reserved. |
| [agentgov](https://github.com/hapax-systems/agentgov) | Portable governance hooks that an adopter can install, audit, and pilot without inheriting the Hapax estate. | Turns common AI coding-agent risks into installable pre-action checks that teams can pilot before buying or building heavier governance. | Permissive adoption surface; copy may say MIT for agentgov only and must not imply broader Hapax runtime rights or support obligations. |
| [hapax-council](https://github.com/hapax-systems/hapax-council) | Inspect how AI-agent work is authorized, routed, reviewed, refused, and surfaced publicly inside the Hapax estate. | Lets technical leaders, researchers, and auditors evaluate concrete controls: what may run, what may write, what evidence exists, and where stale or unsupported claims fail closed. | Source-visible strict research/runtime artifact; not open source, not a framework, not a supported distribution. |
| [hapax-constitution](https://github.com/hapax-systems/hapax-constitution) | Governance specification and repo-presentation authority for Hapax Systems, with a clear hapax-sdlc tooling boundary. | Gives reviewers one auditable source for names, licenses, support boundaries, and claim ceilings, reducing public-surface drift. | Split posture: specification and publication metadata use CC BY-NC-ND; runnable hapax-sdlc tooling uses Apache-2.0. Do not describe the whole repository as Apache or open source. |
| [hapax-officium](https://github.com/hapax-systems/hapax-officium) | Internal management decision-support runtime published for boundary and governance review. | Shows how management-context software can preserve boundary discipline: preparation and context assembly without people-evaluation or HR-software claims. | Source-visible strict runtime artifact pending product boundary; not open source and not an adoption or support surface. |
| [hapax-research-ledger](https://github.com/hapax-systems/hapax-research-ledger) | Public numeric-only SCED evidence ledger published from the first data point with caveats preserved. | Lets skeptical readers audit early observations, caveats, nulls, and scorer substitutions as data rather than reading them as polished product or research claims. | Public-domain data posture for the ledger only; does not license Hapax runtime code, Reins, or council internals. |
| [hapax-assets](https://github.com/hapax-systems/hapax-assets) | Public CDN mirror of approved aesthetic assets with per-asset provenance and notices. | Lets public pages reuse reviewed assets through stable URLs and license notices without turning the mirror into the source of truth. | Per-asset license posture; preserve upstream BSD-3-Clause, CC-BY-SA-4.0, and other asset-specific notices rather than implying a single repo-level license. |

## Supporting Public Surfaces

| Surface | What to expect | Reader value | License posture |
|---|---|---|---|
| [hapax-mcp](https://github.com/hapax-systems/hapax-mcp) | Hapax Logos MCP Bridge exposing Hapax API state and actions to Claude Code and compatible MCP clients. | Gives MCP clients a bounded bridge to live Hapax state while keeping authority with the underlying APIs rather than the connector. | Permissive integration bridge for MCP use; current copy must frame it as a Hapax logos bridge, not a general-purpose MCP library. |
| [hapax-phone](https://github.com/hapax-systems/hapax-phone) | Mobile context source for the Hapax environment, useful for auditing data sources, transport, and privacy boundaries. | Shows which phone-derived signals enter the estate, which sensors are excluded, and how missing data degrades without becoming a health-efficacy claim. | Single-operator device bridge; source-visible strict unless a separate productized device boundary is created. |
| [hapax-watch](https://github.com/hapax-systems/hapax-watch) | Wrist biometric source for the Hapax environment, useful for auditing device integration and privacy boundaries. | Makes biometric and context ingestion inspectable as a bounded, privacy-scoped signal path rather than a consumer health claim. | Single-operator device bridge; source-visible strict unless a separate productized device boundary is created. |

## Operating Frame

- Reins is the product front door: read and command-preview for governed agentic delivery. It remains a read/preview surface until receipt-backed writes ship and are released.
- agentgov is the adoption commons: portable governance hooks for AI coding agents under MIT.
- hapax-spine is the source-available BSL 1.1 runtime mechanism behind Reins; it is not a general-purpose lifecycle kernel.
- hapax-council is the research/runtime apparatus. It is published for inspection and citation, not as a supported framework.
- Hapax Logos MCP Bridge, Mobile Context Source, and Wrist Biometric Source are public source-visible boundary artifacts. They support audit and integration review; they are not general products, health products, or broad MCP framework claims.
- The Claim Verification Council is a public-facing capability name for claim-checking governance. Internal labels are not part of the public API.
- The Capability Frontier is a way to describe capability registries, route receipts, and authority ceilings without collapsing them into a single agent score. Scores are registry-asserted today; measured calibration is planned.
- omg.lol weblog, RSS, social, DOI/archive, and other public fanout surfaces are governed publication-bus channels. Repository copy may point at published artifacts, but it must not imply direct public egress or cross-channel publication authority.

## Support And Intake

Issues are enabled as redirect surfaces. GitHub Discussions, Projects, and most wikis are not the operating venue for the work. Security, support, and commercial conversations follow the boundary files in each repository.

## Claim Ceiling

Current public material may describe shipped read paths, command preview, governed dispatch mechanisms, evidence ledgers, and source-available inspection surfaces. It must not claim autonomous write authority, full general lifecycle coverage, unrestricted portability, comparative ranking against other systems, or staffed community support unless the corresponding release gates have closed.
