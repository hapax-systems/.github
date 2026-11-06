# Hapax Research Lab

**Hapax Research Lab** (`hrl-han`) evaluates AI capability and governance at the level of the situated Human-Agentic Network (`HAN`) — model weights operating inside explicit verification, routing, benchmark, and authority boundaries — rather than treating isolated model checkpoints as self-governing systems. Across research records and software, the lab enforces authority before action, receipts before claims, and visible scope limits, publishing misses and corrections alongside supported results so readers can inspect what is shipped, what is reserved, and what evidence would have to exist before a stronger claim is allowed.

- **Research portal & commitments register:** [https://hapaxresearch.com](https://hapaxresearch.com)
- **Research weblog & field notes:** [https://hapax.weblog.lol](https://hapax.weblog.lol)
- **Identity outpost:** [https://hapax.omg.lol](https://hapax.omg.lol)
- **Disclosures & corrections:** [hrl-han@hapaxresearch.com](mailto:hrl-han@hapaxresearch.com) ([contact & security policy](https://hapaxresearch.com/about/#contact))

The public `hapax-systems` portfolio is partitioned by role and license: source-available commercial core (`BSL 1.1`), public-domain numeric evidence (`CC0 1.0`), constitutional governance specifications (`CC BY-NC-ND 4.0` / `Apache-2.0`), permissive integration tooling (`MIT`), and checksum-verified publication assets (`CC BY 4.0` plus per-asset upstream terms). The license on each repository is the sole license authority for that repository; do not infer broader portfolio or trademark rights.

## Public Entry Points

| Surface | What to expect | Reader value | License posture |
|---|---|---|---|
| [reins](https://github.com/hapax-systems/reins) | Product front-door terminal cockpit for observing and previewing governed AI-agent delivery state (`reins --demo` runs offline on bundled fixture data). | Lets operators, auditors, and technical evaluators inspect live or fixture agent-delivery state and see what a governed write command would request before any write authority is granted. | Source-available under Business Source License 1.1; not open source until the Change Date converts the work to Apache-2.0. Self-hosted and non-competing production use is permitted within the Additional Use Grant; competing hosted-service rights remain reserved. |
| [hapax-spine](https://github.com/hapax-systems/hapax-spine) | Runtime mechanism package for append-only events, policy-backed routing, capability receipts, quota arithmetic, EDT measurement, and projections. | Separates the runtime mechanics behind Reins so dispatch, receipts, quotas, and projections can be inspected and tested independently without claiming to represent a complete multi-tenant platform. | Source-available under Business Source License 1.1; not open source until the Change Date converts the work to Apache-2.0. Self-hosted and non-competing production use is permitted by the Additional Use Grant; offering the licensed work as a competing hosted or managed service remains reserved. |
| [hapax-constitution](https://github.com/hapax-systems/hapax-constitution) | Governance specification and repo-presentation authority for Hapax Research Lab, with a clear hapax-sdlc tooling boundary. | Gives reviewers one auditable source for names, licenses, support boundaries, and claim ceilings, reducing public-surface drift. | Split posture: specification and publication metadata use CC BY-NC-ND 4.0; runnable hapax-sdlc tooling uses Apache-2.0. Do not describe the whole repository as Apache or open source. |
| [hapax-research-ledger](https://github.com/hapax-systems/hapax-research-ledger) | Public numeric SCED evidence ledger and reproducible witness records published from the first data point with caveats preserved. | Lets skeptical readers audit early observations, caveats, nulls, scorer substitutions, and commitment witness checks directly as schema-validated data. | Public-domain dedication (CC0 1.0) for the declared ledger and witness data surface only; does not license Hapax Research Lab runtime code, Reins, or internal apparatus, and asserts no human copyright over machine-generated records. |

## Supporting Public Surfaces

| Surface | What to expect | Reader value | License posture |
|---|---|---|---|
| [hapax-mcp](https://github.com/hapax-systems/hapax-mcp) | Experimental MCP stdio bridge exposing Logos HTTP API state and bounded actions to Claude Code and compatible MCP clients. | Lets compatible MCP clients inspect state and invoke bounded endpoints against a running Logos API while keeping policy and authorization in the underlying backend. | MIT-licensed integration bridge for MCP clients; requires a separately running Logos API backend and is not a general-purpose MCP framework. |
| [hapax-assets](https://github.com/hapax-systems/hapax-assets) | Public GitHub Pages mirror serving reviewed publication and aesthetic artifacts with SHA-256 manifest verification and per-asset license notices. | Provides stable, checksum-verified asset URLs and auditable attribution records (_manifest.yaml, _NOTICES.md) for Hapax Research Lab web and publication surfaces. | Original documentation, index.html, and repository metadata use CC-BY-4.0 (see LICENSE and LICENSE-SCOPE.md); trademarks and brand marks of Hapax Research Lab (Hapax Research LLC) are expressly reserved; mirrored third-party assets retain their declared upstream licenses (BSD-3-Clause, CC-BY-SA-4.0, CC0-1.0) in _manifest.yaml and _NOTICES.md, so licenses remain per-asset. |
| [agentgov](https://github.com/hapax-systems/agentgov) *(archived)* | Archived early governance-hook prototype retained for historical inspection and citation; active work lives in hapax-systems/reins. | Preserves historical pre-action hook scripts and MIT source for reference while directing new evaluations to hapax-systems/reins and https://hapaxresearch.com. | Archived MIT-licensed prototype; existing MIT grants remain intact for historical inspection and citation of agentgov only and do not imply rights or support obligations across active Hapax Research Lab repositories. |

## Operating Frame

- **Reins (`reins`)** is the product front door: terminal observation and governed command preview (`reins --demo` runs offline on fixture data). It remains a read/preview surface until receipt-backed writes ship and are released.
- **Runtime mechanism (`hapax-spine`)** is the source-available `BSL 1.1` mechanism layer behind Reins (append-only event ledgers, policy-backed routing, capability receipts, quota arithmetic, EDT projections); it is not a general-purpose lifecycle kernel.
- **Governance anchor (`hapax-constitution`)** holds the axiom registry, interpretive canons, and deterministic `hapax-sdlc` frontmatter renderers.
- **Numeric ledger (`hapax-research-ledger`)** publishes append-only `CC0 1.0` observations, controlled vocabularies, hashes, caveats, and public commitment witnesses.
- **Logos MCP Bridge (`hapax-mcp`)** is an experimental `MIT` `stdio` bridge for existing Logos HTTP API deployments; internal research, coordination, and companion device runtimes operate privately inside `hrl-han` and are not supported public frameworks, consumer health products, or general MCP frameworks. Public research examinations and correction records are published at [https://hapaxresearch.com](https://hapaxresearch.com).
- **Historical archive (`agentgov`)** is an archived early standalone governance-hook prototype (`MIT`, `v0.3.2` inactive) superseded by [reins](https://github.com/hapax-systems/reins).
- **Capability Frontier & publication channels:** Capability routing scores are registry-asserted today; measured calibration is planned. Weblog, RSS, archive/DOI, and social syndication surfaces operate as governed publication-bus channels and must not imply unreviewed direct public egress.

## Claim Ceiling

Current public material describes shipped read paths, governed command preview, dispatch and receipt mechanisms, numeric evidence ledgers, and source-available inspection surfaces. It does not claim autonomous write authority, full general lifecycle coverage, unrestricted portability, comparative ranking without primary reproduction witnesses, or staffed community support.

## Support, Identity, and Legal Boundary

GitHub Issues are enabled only as redirect surfaces; GitHub Discussions, Projects, and Wikis are disabled across `hapax-systems`, and unsolicited pull requests are not accepted.

- **Institution:** Hapax Research Lab (`hrl-han` — the research network of Hapax Research Lab)
- **Legal entity (as filed): Hapax Research LLC, organized in Wyoming on 2026-05-10, filing ID 2026-001973400**
- **Contact:** [hrl-han@hapaxresearch.com](mailto:hrl-han@hapaxresearch.com) ([https://hapaxresearch.com/about/#contact](https://hapaxresearch.com/about/#contact))
- **Commitment:** The network commits to receipt, retention and published correction. It promises no response time.

---

*HACA-C v0.3.15, the lab's draft rule for labelling machine-made text, not an external certification. No request to a natural person to approve the final wording, and no such approval, was found in hrl-han's sending, review and coordination records when the text was released. hrl-han releases a text once its checking is complete, under a standing rule that hrl-han's principal, who is not named in this text, adopted before the text was drafted. Review record: https://hapaxresearch.com/review-record/ (open to anyone). This label records how the text was made; it does not certify that the text is true. An unaltered record can contain false claims or miss relevant events.*
