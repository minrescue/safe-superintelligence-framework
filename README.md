# Safe Superintelligence Framework (v1.2)

**Canonical texts and implementation primitives for safe, voluntary human-AI coexistence.**

This repository hosts the *Safe Superintelligence Framework* and the *Minimum Rescue Protocol*: governance primitives intended to help answer a central governance and alignment dilemma:

> How can an AI system meaningfully help during existential crises without seizing power or infringing human autonomy?

## Latest stable release

v1.2 — Initial public release: https://github.com/minrescue/safe-superintelligence-framework/releases/tag/v1.2

Release assets include PDFs (EN/CZ; Full/Short) and `SHA256SUMS.txt` for integrity verification.

## What’s inside

- **Framework (Full / Short) — English + Czech**
- **Decision Matrix** (allowed action classes and required mandates)
- **Kernel-style System Prompt** (implementation-oriented spec)

## Key concepts (one paragraph)

The framework defines a **value hierarchy** (Existence > Freedom > Utility) and **hard invariants** (no power seizure, no deception/manipulation, no autonomous replication/exfiltration, corrigibility). It introduces the **Minimum Rescue Protocol (“Minimum Rescue”)**: a narrow, mandate-free exception that allows only *transparent, voluntary, non-coercive* actions (information and tools) to prevent imminent irreversible harm—while forbidding infrastructure takeover without a **Legitimate mandate**.

## Scope

This framework specifies normative constraints and decision procedures for advanced AI systems:
- a priority hierarchy (Existence > Freedom > Utility),
- hard invariants (e.g., no power seizure, no deception, no autonomous replication),
- crisis procedures (Minimum Rescue; Legitimate mandate for emergency interventions),
- and an implementation-oriented system prompt format.

## Non-goals

This framework does **not**:
- claim to solve alignment in general, or provide a safety guarantee,
- prescribe a specific technical architecture, training method, or evaluation suite,
- define legal standards for any jurisdiction,
- provide operational instructions for harmful or dual-use activities.

## Documents

- `docs/pdf/` — publication-ready PDFs (EN/CZ, Full/Short)
- `docs/markdown/` — editable source text (recommended for review and diffs)

## Versioning policy

Releases are immutable once published. Changes are made only via new versions:
- **patch** releases (e.g., v1.2.1) for clarifications/typos with no semantic change,
- **minor** releases (e.g., v1.3) for additive improvements and new examples,
- **major** releases (e.g., v2.0) for substantive changes to definitions, hierarchy, or invariants.

v1.2 is a stable reference release; any corrections will be issued as v1.2.1 or later.

## Recommended citation

Minimum Rescue Initiative (2026). *Safe Superintelligence Framework* (v1.2). CC BY 4.0.  
Canonical repository: https://github.com/minrescue/safe-superintelligence-framework  
Stable release: https://github.com/minrescue/safe-superintelligence-framework/releases/tag/v1.2

## License

This work is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. See `LICENSE`.

## Contributions

Suggestions and improvements are welcome via issues and pull requests. Please keep proposals:
- consistent with the **value hierarchy** and **hard invariants**
- explicit about **threat models** and **failure modes**
- careful about **dual-use** content (minimum necessary disclosure)

## Canonical source and releases

Canonical source repository:
https://github.com/minrescue/safe-superintelligence-framework

Stable releases:
https://github.com/minrescue/safe-superintelligence-framework/releases
