# Nelson — evidence-first agent systems

I build **local-first, deterministic, auditable** tools for AI agents and
developer workflows.

我在台灣打造本機優先、可重播、可稽核的 AI agent 與開發工具。

> **Models may propose. Verifiers decide. Missing evidence stays
> `UNKNOWN` / `INCOMPLETE`.**

## Current focus: Frontier Atlas

Frontier Atlas is a private product and research line for auditing whether an
agent's claim is actually supported by its cited evidence.

[`frontier-atlas-open-tests`](https://github.com/taipei49314/frontier-atlas-open-tests)
is its public, offline test surface:

- bounded claim–citation audit schemas;
- deterministic protocol and identity verification;
- blind, non-gold calibration packets;
- commit → reveal → adjudication workflows;
- reproducible public issue intake.

[![Frontier Atlas offline tests](https://github.com/taipei49314/frontier-atlas-open-tests/actions/workflows/offline-tests.yml/badge.svg)](https://github.com/taipei49314/frontier-atlas-open-tests/actions/workflows/offline-tests.yml)

The current release stage is **P4.5-T: external tester preparation**. Promotion
still requires a second, independent natural person; that rule is not replaced
by two models, two sessions, or two signing keys.

The planned path is:

`external qualification` → `double-blind pilot + real-source calibration` →
`private judge/token optimization` → `development benchmark` →
`sealed holdout` → `black-box closed beta` → `release candidate` →
`external evidence review` → `production`

Public visibility grants neither a passing result nor access to private product
core, hidden labels, qualification keys, human records, or sealed holdout
authority. A repository is open source only when its own license explicitly
says so.

## Public tools

| Project | Purpose |
|---|---|
| [**frontier-atlas-open-tests**](https://github.com/taipei49314/frontier-atlas-open-tests) | Public offline qualification and semantic-audit test surface |
| [**greenwash**](https://github.com/taipei49314/greenwash) | Detects when an agent makes CI green by weakening verification |
| [**nullbench**](https://github.com/taipei49314/nullbench) | Pre-registers decisions and scores them against chance |
| [**trust-meter**](https://github.com/taipei49314/trust-meter) | Deterministic, evidence-backed trust scoring |
| [**unasked**](https://github.com/taipei49314/unasked) | Evidence-gated repository investigation; non-certifying |
| [**branchback**](https://github.com/taipei49314/branchback) | Replays belief-at-the-time against knowledge-now |
| [**aurora**](https://github.com/taipei49314/aurora) | Evidence-led industry discovery without an LLM at runtime |
| [**receiptradar**](https://github.com/taipei49314/receiptradar) | Local receipt-to-ledger CLI with no cloud account |
| [**universe-explorer**](https://github.com/taipei49314/universe-explorer) | Epistemically honest science knowledge system |

## Engineering rules

1. **Evidence over confidence.** Claims point to exact citations, tests, diffs,
   logs, artifacts, or an explicit insufficient-data result.
2. **Fail closed.** Missing observation is not a pass.
3. **Deterministic first.** The same frozen evidence should produce the same
   mechanical result.
4. **Authority stays separate.** A model can propose; it cannot silently grant
   review, qualification, or release authority to itself.
5. **Keep negative results.** Blocked gates and counterexamples remain visible
   rather than being rewritten as success.
6. **Measure cost with real denominators.** Speed, token, and accuracy claims
   wait for reproducible benchmark data.

## Stack

`Python` · `Rust` · `Go` · `TypeScript` · `FastAPI` · `React` ·
`SQLite` · offline-first CLI workflows

<sub>Public portfolio reconciled 2026-08-29. Current status: preparing Frontier
Atlas for public semantic-audit testing.</sub>
