# Nelson — evidence-first agent systems

I build **local-first, deterministic, auditable** tools for AI agents and
developer workflows.

我在台灣打造本機優先、可重播、可稽核的 AI agent 與開發工具。

> **Models may propose. Verifiers decide. Missing evidence stays
> `UNKNOWN` / `INCOMPLETE`.**

[Explore the full Nelson Stack →](https://github.com/taipei49314/nelson-stack)

## The audit loop

| Stage | Project | Question |
|---|---|---|
| Detect | [**greenwash**](https://github.com/taipei49314/greenwash) | Did an agent make CI green by weakening verification? |
| Re-run | [**RepoPassport**](https://github.com/taipei49314/RepoPassport) | Did the declared journey work within its capabilities and clean up after itself? |
| Reproduce | [**stateweaver**](https://github.com/taipei49314/stateweaver) | Can an independent verifier replay the finding against a clean state? |
| Forecast | [**tomorrowci**](https://github.com/taipei49314/tomorrowci) | When will dependency or runtime drift invalidate today’s evidence? |

Supporting evaluation surfaces include
[null-city](https://github.com/taipei49314/null-city) for deterministic crisis
response and [NormShift](https://github.com/taipei49314/NormShift) for
evidence-backed standards diffs.

## Released

| Project | Current public status |
|---|---|
| [greenwash](https://github.com/taipei49314/greenwash) | [`v0.1.14`](https://github.com/taipei49314/greenwash/releases/tag/v0.1.14) — deterministic diff-level verification-tampering detector |
| [null-city](https://github.com/taipei49314/null-city) | [`v0.1.0-alpha.1`](https://github.com/taipei49314/null-city/releases/tag/v0.1.0-alpha.1) — playable deterministic agent-evaluation sandbox |
| [tomorrowci](https://github.com/taipei49314/tomorrowci) | [`v0.1.0-grok-session`](https://github.com/taipei49314/tomorrowci/releases/tag/v0.1.0-grok-session) — experimental future-breakage scanner and replay bundle |
| [tomorrowci-lab](https://github.com/taipei49314/tomorrowci-lab) | [`v0.1.1-alpha.2`](https://github.com/taipei49314/tomorrowci-lab/releases/tag/v0.1.1-alpha.2) — measured lab release with explicit `NOT_RUN` boundaries |
| [md-brain](https://github.com/taipei49314/md-brain) | [`v0.2.0`](https://github.com/taipei49314/md-brain/releases/tag/v0.2.0) — public prototype for model-independent Markdown continuity |
| [aurora](https://github.com/taipei49314/aurora) | [`v0.1.47`](https://github.com/taipei49314/aurora/releases/tag/v0.1.47) — alpha evidence engine; observations, not investment claims |
| [receiptradar](https://github.com/taipei49314/receiptradar) | [`v0.1.0-cli.34`](https://github.com/taipei49314/receiptradar/releases/tag/v0.1.0-cli.34) — four-platform CLI release with packaged checksums |
| [github-radar](https://github.com/taipei49314/github-radar) | [`v0.1.0`](https://github.com/taipei49314/github-radar/releases/tag/v0.1.0) — reproducible stdlib-only alpha with bounded coverage claims |
| [FutureShow-pet](https://github.com/taipei49314/FutureShow-pet) | [`v0.1.0`](https://github.com/taipei49314/FutureShow-pet/releases/tag/v0.1.0) — personal Windows alpha; Loop 10 and long-soak automation remain open |

## Active qualification tracks

| Project | Honest boundary |
|---|---|
| [RepoPassport](https://github.com/taipei49314/RepoPassport) | Working `v1alpha1` vertical slice; observer coverage remains `incomplete`, so healthy runs stay `inconclusive` |
| [stateweaver](https://github.com/taipei49314/stateweaver) | Source-only pre-alpha; synthetic/local evidence exists, trusted Reality proof does not |
| [NormShift](https://github.com/taipei49314/NormShift) | M0 implemented; production and release remain blocked pending external audit |
| [nelsoncode-ide](https://github.com/taipei49314/nelsoncode-ide) | Personal preview; external security audit remains **NO-GO** for untrusted use |

## Local-first tools

| Project | What it does |
|---|---|
| [md-brain](https://github.com/taipei49314/md-brain) | Model-independent continuity runtime for Markdown memory |
| [github-radar](https://github.com/taipei49314/github-radar) | GitHub research with measured uncertainty and zero runtime dependencies |
| [aurora](https://github.com/taipei49314/aurora) | Finds unnamed industries from evidence, with no LLM at runtime |
| [receiptradar](https://github.com/taipei49314/receiptradar) | Receipt-to-ledger CLI with no cloud account |
| [nelson-release-studio](https://github.com/taipei49314/nelson-release-studio) | Windows-first music, asset, lyric-video, and release-package workbench |
| [FutureShow-pet](https://github.com/taipei49314/FutureShow-pet) | Personal Windows desktop pet with Taiwan and GitHub information loops |

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

<sub>Last portfolio reconciliation: 2026-08-09.</sub>
