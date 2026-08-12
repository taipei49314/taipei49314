# Nelson — evidence-first agent systems

I build **local-first, deterministic, auditable** tools for AI agents and
developer workflows.

我在台灣打造本機優先、可重播、可稽核的 AI agent 與開發工具。

> **Models may propose. Verifiers decide. Missing evidence stays
> `UNKNOWN` / `INCOMPLETE`.**

[Explore the full Nelson Stack →](https://github.com/taipei49314/nelson-stack)

![phaseledger attach session](https://raw.githubusercontent.com/taipei49314/nelson-stack/main/docs/attach.gif)

## Now

The active line is **measure before you trust**:

- [`trust-meter`](https://github.com/taipei49314/trust-meter) scores a checkout from evidence.
- [`phaseledger`](https://github.com/taipei49314/phaseledger) refuses to advance a phase without a fresh measurer `PASS`.
- [`nullbench`](https://github.com/taipei49314/nullbench) pre-registers decisions and scores them against chance — never backfill.
- [`tomorrowci-lab`](https://github.com/taipei49314/tomorrowci-lab) asks when today's evidence stops being current.

No GitHub Release yet for `trust-meter` / `phaseledger`. Lab publication remains a
measured pre-alpha with explicit `NOT_RUN` / `BLOCKED` rows.

## The audit loop

![Audit loop with honest gaps](https://raw.githubusercontent.com/taipei49314/nelson-stack/main/docs/audit-loop.gif)

| Stage | Project | Question |
|---|---|---|
| Measure | [**trust-meter**](https://github.com/taipei49314/trust-meter) | What does this checkout actually score from local evidence? |
| Gate | [**phaseledger**](https://github.com/taipei49314/phaseledger) | Can this phase advance without a fresh deterministic `PASS`? |
| Detect | [**greenwash**](https://github.com/taipei49314/greenwash) | Did an agent make CI green by weakening verification? |
| Baseline | [**nullbench**](https://github.com/taipei49314/nullbench) | Did the decision beat chance, with the claim pre-registered? |
| Re-run | [**RepoPassport**](https://github.com/taipei49314/RepoPassport) | Did the declared journey work within its capabilities and clean up after itself? |
| Reproduce | [**stateweaver**](https://github.com/taipei49314/stateweaver) | Can an independent verifier replay the finding against a clean state? |
| Forecast | [**tomorrowci**](https://github.com/taipei49314/tomorrowci) · [**tomorrowci-lab**](https://github.com/taipei49314/tomorrowci-lab) | When will dependency or runtime drift invalidate today’s evidence? |

Supporting evaluation surfaces:

- [unasked](https://github.com/taipei49314/unasked) — evidence-gated repo investigation; non-certifying
- [smallestlie](https://github.com/taipei49314/smallestlie) — authorized adversarial harness; smallest accepted lie
- [null-city](https://github.com/taipei49314/null-city) — deterministic crisis-response sandbox
- [NormShift](https://github.com/taipei49314/NormShift) — evidence-backed standards diffs
- [branchback](https://github.com/taipei49314/branchback) — decision replay lab; belief-at-the-time vs knowledge-now
- [constraint-deck](https://github.com/taipei49314/constraint-deck) — session-first authorial constraint deck; measure first

## Measured public surfaces

| Project | Current public status |
|---|---|
| [greenwash](https://github.com/taipei49314/greenwash) | [`v0.1.23`](https://github.com/taipei49314/greenwash/releases/tag/v0.1.23) — deterministic diff-level verification-tampering detector |
| [nullbench](https://github.com/taipei49314/nullbench) | [`v0.7.0`](https://github.com/taipei49314/nullbench/releases/tag/v0.7.0) — pre-register decisions; score against chance; never backfill |
| [tomorrowci-lab](https://github.com/taipei49314/tomorrowci-lab) | [`v0.1.1-alpha.2`](https://github.com/taipei49314/tomorrowci-lab/releases/tag/v0.1.1-alpha.2) — measured lab release; `NOT_RUN` rows stay visible. GitHub “Latest” still points at rejected [`v0.1.0-grok-session`](https://github.com/taipei49314/tomorrowci-lab/releases/tag/v0.1.0-grok-session) |
| [unasked](https://github.com/taipei49314/unasked) | [`v0.2.1`](https://github.com/taipei49314/unasked/releases/tag/v0.2.1) — non-certifying M0 investigation path |
| [null-city](https://github.com/taipei49314/null-city) | [`v0.1.0-alpha.1`](https://github.com/taipei49314/null-city/releases/tag/v0.1.0-alpha.1) — playable deterministic agent-evaluation sandbox (prerelease; no GitHub “Latest”) |
| [receiptradar](https://github.com/taipei49314/receiptradar) | [`v0.1.0-cli.34`](https://github.com/taipei49314/receiptradar/releases/tag/v0.1.0-cli.34) — four-platform CLI release with packaged checksums |
| [md-brain](https://github.com/taipei49314/md-brain) | [`v0.2.0`](https://github.com/taipei49314/md-brain/releases/tag/v0.2.0) — public prototype for model-independent Markdown continuity (prerelease; no GitHub “Latest”) |
| [aurora](https://github.com/taipei49314/aurora) | [`v0.1.47`](https://github.com/taipei49314/aurora/releases/tag/v0.1.47) — alpha evidence engine; observations, not investment claims |
| [github-radar](https://github.com/taipei49314/github-radar) | [`v0.1.0`](https://github.com/taipei49314/github-radar/releases/tag/v0.1.0) — reproducible stdlib-only alpha with bounded coverage claims (prerelease; no GitHub “Latest”) |
| [nelson-release-studio](https://github.com/taipei49314/nelson-release-studio) | [`v1.0.0`](https://github.com/taipei49314/nelson-release-studio/releases/tag/v1.0.0) — verified Windows-first local release workbench |
| [FutureShow-pet](https://github.com/taipei49314/FutureShow-pet) | [`v0.1.0`](https://github.com/taipei49314/FutureShow-pet/releases/tag/v0.1.0) — personal Windows alpha; Loop 10 and long-soak automation remain open (prerelease; no GitHub “Latest”) |
| [tw-stock-lab](https://github.com/taipei49314/tw-stock-lab) | [`v0.2.0`](https://github.com/taipei49314/tw-stock-lab/releases/tag/v0.2.0) — local TW stock research lab; paper simulation only, not investment advice |
| [branchback](https://github.com/taipei49314/branchback) | [`v2.0.0`](https://github.com/taipei49314/branchback/releases/tag/v2.0.0) — local-first decision replay laboratory |

[`tomorrowci`](https://github.com/taipei49314/tomorrowci) still has GitHub
“Latest” pointed at
[`v0.1.0-grok-session`](https://github.com/taipei49314/tomorrowci/releases/tag/v0.1.0-grok-session).
That tag is a **rejected** historical candidate, not an acceptance claim.
Current measured lab work lives in [`tomorrowci-lab`](https://github.com/taipei49314/tomorrowci-lab).

## Active qualification tracks

| Project | Honest boundary |
|---|---|
| [trust-meter](https://github.com/taipei49314/trust-meter) | No release. Local scorer with batch/compare/API surfaces; self-audit only |
| [phaseledger](https://github.com/taipei49314/phaseledger) | No release. Phase advance requires a fresh measurer `PASS`; reclaim invalidates later phases |
| [tomorrowci-lab](https://github.com/taipei49314/tomorrowci-lab) | Measured Linux Docker slices exist; Podman / Windows / macOS and independent authorization remain **BLOCKED** |
| [RepoPassport](https://github.com/taipei49314/RepoPassport) | Working `v1alpha1` vertical slice; observer coverage remains `incomplete`, so healthy runs stay `inconclusive` |
| [stateweaver](https://github.com/taipei49314/stateweaver) | Source-only pre-alpha; synthetic/local evidence exists, trusted Reality proof does not |
| [NormShift](https://github.com/taipei49314/NormShift) | M0 implemented; production and release remain blocked pending external audit |
| [smallestlie](https://github.com/taipei49314/smallestlie) | Authorized adversarial harness; no release |
| [nelsoncode-ide](https://github.com/taipei49314/nelsoncode-ide) | Personal preview; external security audit remains **NO-GO** for untrusted use |
| [constraint-deck](https://github.com/taipei49314/constraint-deck) | Public source; measure-first voice contract; no release yet |
| [editorial-doll-engineering-preview](https://github.com/taipei49314/editorial-doll-engineering-preview) | Public M0–M3 engineering preview of a deterministic styling engine; no release yet |
| [universe-explorer](https://github.com/taipei49314/universe-explorer) | Public epistemically honest science knowledge system; no release yet |
| [vibe-oracle](https://github.com/taipei49314/vibe-oracle) | Explicitly **not** evidence — vibe theater that admits the theater |
| [why-ledger](https://github.com/taipei49314/why-ledger) | Justified sovereign decisions notebook (WJSD); documentation-first; no release yet |

## Local-first tools

| Project | What it does |
|---|---|
| [receiptradar](https://github.com/taipei49314/receiptradar) | Receipt-to-ledger CLI with no cloud account |
| [md-brain](https://github.com/taipei49314/md-brain) | Model-independent continuity runtime for Markdown memory |
| [github-radar](https://github.com/taipei49314/github-radar) | GitHub research with measured uncertainty and zero runtime dependencies |
| [aurora](https://github.com/taipei49314/aurora) | Finds unnamed industries from evidence, with no LLM at runtime |
| [music-lab](https://github.com/taipei49314/music-lab) | Deterministic local music toolkit; analysis first, no cloud account |
| [nelson-release-studio](https://github.com/taipei49314/nelson-release-studio) | Windows-first music, asset, lyric-video, and release-package workbench |
| [FutureShow-pet](https://github.com/taipei49314/FutureShow-pet) | Personal Windows desktop pet with Taiwan and GitHub information loops |
| [tw-stock-lab](https://github.com/taipei49314/tw-stock-lab) | Local TW market research desk (charts, sector map, signals + Ollama); paper only |
| [branchback](https://github.com/taipei49314/branchback) | Preserve belief-at-the-time vs knowledge-now for decision replay |

## Engineering rules

1. **Deterministic first.** The same evidence should produce the same verdict.
2. **Evidence over vibe.** Claims point to tests, diffs, logs, artifacts, or an
   explicit insufficient-data result.
3. **Fail closed.** Missing observation is not a pass; capability violations
   outrank functional success.
4. **Local first.** Prefer loopback services, offline-capable CLIs, and local
   runtimes over mandatory cloud accounts.
5. **Keep the failures.** Negative controls, blocked gates, and NO-GO verdicts
   remain visible instead of being rewritten as success.

## Stack

`Python` · `Rust` · `Go` · `TypeScript` · `FastAPI` · `React` · `Electron` ·
`SQLite` · `Ollama`

Older market, persona, creative-production, and agent-console experiments are
kept private or archived when they stop being the active line. Market-related
projects are paper-only research simulations, never broker or investment
systems.

<sub>Last portfolio reconciliation: 2026-08-12.</sub>
