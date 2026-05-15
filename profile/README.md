# OrgForge

**Cryptographic governance.**

OrgForge is a system that enforces organizational rules at the moment actions occur, using cryptographic authorization instead of procedural trust.

---

## The lineage

Bitcoin made money trustless.

Ethereum made computation trustless.

orgfrg makes authorization trustless.

---

## How it works

Actors submit an **intent** describing the action they want to perform. OrgForge evaluates that intent against an **OrgSpec**, a machine-readable organizational constitution. If the rules are satisfied, OrgForge issues a signed **authorization artifact**. Execution systems verify that artifact before acting.

The pipeline is deterministic:

Actor → Intent → OrgForge evaluation → Signed authorization artifact → Execution system verifies → Action executes.

No proof, no action.

---

## What OrgSpec can encode

Spending limits. Multi-approval thresholds. Role-based permissions. Rate limits for autonomous agents. Allowed markets and tool access. Operational states such as freeze, audit, and incident mode. Agent-specific restrictions.

---

## Status

Active development. The protocol engine is locked at 831 of 831 tests passing for Sprint 1 of the A.5 milestone. The platform and SDKs are in active build.

Source repositories will be made public after patent conversion. Until then, the protocol specification, whitepaper, and architecture are available through the authoritative documents below.

---

## Documents

- **Whitepaper:** https://doi.org/10.5281/zenodo.18968718
- **Project site:** https://orgforge.io
- **Protocol site:** https://orgfrg.com

---

## Intellectual property

U.S. Provisional Patent Applications 63/995,907 (filed March 4, 2026) and 64/002,607 (filed March 11, 2026). Additional applications pending.

"OrgForge" and "orgfrg" are trademarks of OrgForge, Inc. U.S. Trademark Serial No. 99710648.

Source code, when released, will be licensed under Apache License 2.0.

---

OrgForge, Inc. · 2026
