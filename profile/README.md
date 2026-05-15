# OrgForge

**Cryptographic governance.**

OrgForge enforces organizational rules at the moment actions occur, using cryptographic authorization instead of procedural trust.

The underlying protocol is called orgfrg.

---

## The lineage

Bitcoin made money trustless.

Ethereum made computation trustless.

orgfrg makes authorization trustless.

---

## How it works

Actors submit an **intent** describing the action they want to perform. orgfrg evaluates that intent against an **OrgSpec**, a machine-readable organizational constitution. If the rules are satisfied, orgfrg issues a signed **authorization artifact**. Execution systems verify that artifact before acting.

The pipeline is deterministic:

Actor → Intent → orgfrg evaluation → Signed authorization artifact → Execution system verifies → Action executes.

No proof, no action.

This allows organizational rules to control payments, deployments, tool calls, treasury actions, and other governed actions before execution.

---

## What OrgSpec can encode

Spending limits. Multi-approval thresholds. Role-based permissions. Rate limits for automated systems. Allowed markets and tool access. Operational states such as freeze, audit, and incident mode. Agent-specific restrictions.

---

## Status

Active development. The protocol engine is under active test coverage across the authorization, verification, OrgSpec, and audit layers. The platform and SDKs are in active build.

Source repositories are not yet public while patent strategy remains active. Public specifications and documents are available through the authoritative links below.

---

## Documents

- **Whitepaper:** https://doi.org/10.5281/zenodo.18968718
- **Project site:** https://orgforge.io
- **Protocol site:** https://orgfrg.com

---

## Intellectual property

U.S. Provisional Patent Applications 63/995,907 (filed March 4, 2026) and 64/002,607 (filed March 11, 2026). Additional filings are under evaluation.

"OrgForge" and "orgfrg" are trademarks of OrgForge, Inc. U.S. Trademark Serial No. 99710648.

Source code, when released, is expected to be licensed under Apache License 2.0.

---

OrgForge, Inc. · 2026
