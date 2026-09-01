# Nelson — evidence-first agent systems

I build **local-first, deterministic, auditable** tools for AI agents and
developer workflows.

我在台灣打造本機優先、可重播、可稽核的 AI agent 與開發工具。

> **Models may propose. Verifiers decide. Missing evidence stays
> `UNKNOWN` / `INCOMPLETE`.**

## Current focus: checkwash

[checkwash](https://github.com/taipei49314/checkwash) catches the agent that
made CI green by weakening the tests. Deterministic, zero-LLM, zero-network,
reads the diff rather than the code state. Public bypass list included.

[![CI](https://github.com/taipei49314/checkwash/actions/workflows/ci.yml/badge.svg)](https://github.com/taipei49314/checkwash/actions/workflows/ci.yml)

The public line is frozen at **v0.2.8**. New work belongs in an existing
repository; a second independent user of checkwash is the gate before that
freeze lifts.

## Frontier Atlas (private)

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

Public visibility grants neither a passing result nor access to private product
core, hidden labels, qualification keys, human records, or sealed holdout
authority. A repository is open source only when its own license explicitly
says so.

## Public tools

Only repositories that are public today. Private research stays unlisted.

| Project | Purpose |
|---|---|
| [**checkwash**](https://github.com/taipei49314/checkwash) | Detects when an agent makes CI green by weakening verification |
| [**checkwash-corpus**](https://github.com/taipei49314/checkwash-corpus) | Real-world measurement corpus for checkwash |
| [**frontier-atlas-open-tests**](https://github.com/taipei49314/frontier-atlas-open-tests) | Public offline qualification and semantic-audit test surface |
| [**nullbench**](https://github.com/taipei49314/nullbench) | Pre-registers decisions and scores them against chance |
| [**aurora**](https://github.com/taipei49314/aurora) | Evidence-led industry discovery without an LLM at runtime |
| [**branchback**](https://github.com/taipei49314/branchback) | Replays belief-at-the-time against knowledge-now |

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
7. **Do not open a new repository.** Work lands in an existing one, or it waits.

## Stack

`Python` · `Rust` · `Go` · `TypeScript` · `FastAPI` · `React` ·
`SQLite` · offline-first CLI workflows

<sub>Public portfolio reconciled 2026-09-02. Current status: checkwash frozen at
v0.2.8; new repositories are closed.</sub>
