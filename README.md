# Nelson — evidence-first agent systems

I build **local-first, deterministic, auditable** tools for AI agents and
developer workflows.

我在台灣打造本機優先、可重播、可稽核的 AI agent 與開發工具。

> **Models may propose. Verifiers decide. Missing evidence stays
> `UNKNOWN` / `INCOMPLETE`.**

[Explore the full Nelson Stack →](https://github.com/taipei49314/nelson-stack)

![Admission then measure — unsigned walkaround, refused advance](https://raw.githubusercontent.com/taipei49314/nelson-stack/main/docs/attach.gif)

## Now

The active line is **admit, then measure**:

- [`walkaround`](https://github.com/taipei49314/walkaround) asks whether the session entered a frozen contract. Done without entry is `BYPASSED`. Receipts are unsigned; no `VERIFIED`.
- [`charterlock`](https://github.com/taipei49314/charterlock) asks whether that journey was allowed to be the exam. Same key writing and sitting it is `CHARTER_COLLAPSED`. Two MAC keys do not prove two people.
- [`trust-meter`](https://github.com/taipei49314/trust-meter) scores a checkout from evidence.
- [`phaseledger`](https://github.com/taipei49314/phaseledger) refuses to advance a phase without a fresh measurer `PASS`.
- [`nullbench`](https://github.com/taipei49314/nullbench) pre-registers decisions and scores them against chance — never backfill.

No GitHub Release for `walkaround` / `charterlock` / `phaseledger`.
`trust-meter` has reached [`v0.2.1`](https://github.com/taipei49314/trust-meter/releases/tag/v0.2.1).
Lab publication remains a measured pre-alpha with explicit `NOT_RUN` / `BLOCKED` rows.

The flagship is that audit spine, not a demo. First CI-backed public
subject: [`cell-shift`](https://github.com/taipei49314/cell-shift)
(CELL//SHIFT). Frozen journey and external receipts live in that repo.
The chamber's own tests are not the spine verdict.

## The audit loop

![Audit loop with honest gaps](https://raw.githubusercontent.com/taipei49314/nelson-stack/main/docs/audit-loop.gif)

| Stage | Project | Question |
|---|---|---|
| Admit | [**walkaround**](https://github.com/taipei49314/walkaround) | Did this session enter a frozen task contract? |
| Charter | [**charterlock**](https://github.com/taipei49314/charterlock) | Was the journey allowed to count as an exam? |
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
- [hgsoc-state-engine](https://github.com/taipei49314/hgsoc-state-engine) — domain-transfer case for evidence-gated naming and path admission; not a medical device
- [branchback](https://github.com/taipei49314/branchback) — decision replay lab; belief-at-the-time vs knowledge-now
- [constraint-deck](https://github.com/taipei49314/constraint-deck) — session-first authorial constraint deck; measure first

## Measured public surfaces

The public surface currently contains **25 active project repositories plus
two meta repositories** (`taipei49314` and `nelson-stack`). Private tools are
intentionally omitted from this page.

| Project | Current public status |
|---|---|
| [cell-shift](https://github.com/taipei49314/cell-shift) | Public subject, not the flagship. Deterministic 3D tissue chamber (CELL//SHIFT). Maintenance-only. Host CI is green; spine `verify` is not claimed. Not biology. |
| [greenwash](https://github.com/taipei49314/greenwash) | GitHub Latest is [`v0.1.42`](https://github.com/taipei49314/greenwash/releases/tag/v0.1.42). `main` identifies as `v0.1.43` and remains ahead of that release after the 2026-08-19 audit round. |
| [nullbench](https://github.com/taipei49314/nullbench) | [`v0.7.0`](https://github.com/taipei49314/nullbench/releases/tag/v0.7.0) — pre-register decisions; score against chance; never backfill |
| [tomorrowci-lab](https://github.com/taipei49314/tomorrowci-lab) | [`v0.2.0-alpha.1`](https://github.com/taipei49314/tomorrowci-lab/releases/tag/v0.2.0-alpha.1) — project-operated prerelease; `CANDIDATE_ONLY_NOT_RELEASE_AUTHORIZED`; no GitHub “Latest” release |
| [unasked](https://github.com/taipei49314/unasked) | [`v0.4.0`](https://github.com/taipei49314/unasked/releases/tag/v0.4.0) — authenticated trust plane; public result remains `M0_NOT_DEMONSTRATED` |
| [null-city](https://github.com/taipei49314/null-city) | [`v0.1.0-alpha.1`](https://github.com/taipei49314/null-city/releases/tag/v0.1.0-alpha.1) — playable deterministic agent-evaluation sandbox (prerelease; no GitHub “Latest”) |
| [receiptradar](https://github.com/taipei49314/receiptradar) | [`v0.1.0-cli.34`](https://github.com/taipei49314/receiptradar/releases/tag/v0.1.0-cli.34) — four-platform CLI release with packaged checksums |
| [aurora](https://github.com/taipei49314/aurora) | [`v0.1.47`](https://github.com/taipei49314/aurora/releases/tag/v0.1.47) — alpha evidence engine; observations, not investment claims |
| [branchback](https://github.com/taipei49314/branchback) | [`v2.0.0`](https://github.com/taipei49314/branchback/releases/tag/v2.0.0) — local-first decision replay laboratory |

Neither [`tomorrowci`](https://github.com/taipei49314/tomorrowci) nor
[`tomorrowci-lab`](https://github.com/taipei49314/tomorrowci-lab) advertises a
GitHub “Latest” release. The `v0.1.0-grok-session` tags are **rejected**
historical candidates, not acceptance claims.
Current lab publication lives in [`tomorrowci-lab`](https://github.com/taipei49314/tomorrowci-lab) as the `v0.2.0-alpha.1` candidate-only prerelease.

## Active qualification tracks

| Project | Honest boundary |
|---|---|
| [walkaround](https://github.com/taipei49314/walkaround) | No release. M4 local kernel; receipts unsigned; `ADMITTED` is not verified work |
| [charterlock](https://github.com/taipei49314/charterlock) | No release. `independence_claim` is always `not_claimed`; two MAC keys do not prove two people |
| [trust-meter](https://github.com/taipei49314/trust-meter) | GitHub Latest [`v0.2.1`](https://github.com/taipei49314/trust-meter/releases/tag/v0.2.1). Local scorer with batch/compare/API surfaces; self-audit only |
| [phaseledger](https://github.com/taipei49314/phaseledger) | No release. Phase advance requires a fresh measurer `PASS`; reclaim invalidates later phases |
| [tomorrowci-lab](https://github.com/taipei49314/tomorrowci-lab) | Newest prerelease is `v0.2.0-alpha.1` and remains candidate-only. macOS / Windows clean-machine and independent authorization remain **BLOCKED** |
| [RepoPassport](https://github.com/taipei49314/RepoPassport) | Working `v1alpha1` vertical slice; 37-row acceptance registry is machine-checked; observer coverage remains `incomplete`, so healthy runs stay `inconclusive` |
| [stateweaver](https://github.com/taipei49314/stateweaver) | Source-only pre-alpha; M6–M8 implementation gates exist; trusted Reality proof does not |
| [NormShift](https://github.com/taipei49314/NormShift) | M0 implemented; production and release remain blocked pending external audit |
| [hgsoc-state-engine](https://github.com/taipei49314/hgsoc-state-engine) | Untreated-HGSOC domain-transfer case. Evidence-gated naming only; not a medical device; CELL//SHIFT is not a biomedical evidence source |
| [smallestlie](https://github.com/taipei49314/smallestlie) | Authorized adversarial harness; no release |
| [constraint-deck](https://github.com/taipei49314/constraint-deck) | Public source; measure-first voice contract; no release yet |
| [editorial-doll-engineering-preview](https://github.com/taipei49314/editorial-doll-engineering-preview) | Public M0–M3 engineering preview of a deterministic styling engine; no release yet |
| [universe-explorer](https://github.com/taipei49314/universe-explorer) | Public epistemically honest science knowledge system; no release yet |
| [vibe-oracle](https://github.com/taipei49314/vibe-oracle) | Explicitly **not** evidence — vibe theater that admits the theater |
| [why-ledger](https://github.com/taipei49314/why-ledger) | Justified sovereign decisions notebook (WJSD); documentation-first; no release yet |

## Local-first tools

| Project | What it does |
|---|---|
| [evidence-workbench](https://github.com/taipei49314/evidence-workbench) | Authority-preserving control plane for exact pins, native envelopes, and fail-closed artifact transport; not an aggregate judge |
| [receiptradar](https://github.com/taipei49314/receiptradar) | Receipt-to-ledger CLI with no cloud account |
| [aurora](https://github.com/taipei49314/aurora) | Finds unnamed industries from evidence, with no LLM at runtime |
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

<sub>Last portfolio reconciliation: 2026-08-21. Aligned with [`nelson-stack`](https://github.com/taipei49314/nelson-stack).</sub>
