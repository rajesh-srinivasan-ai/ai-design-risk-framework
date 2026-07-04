# AI Design Risk Framework (ADRF)

A framework for identifying and classifying design risks in AI systems.

## Why ADRF Exists

AI systems are evolving rapidly.

As these systems mature, recurring patterns of risk are emerging across areas such as:

- Observability
- Accountability
- Explainability
- Governance
- Human Oversight

These risks often appear across multiple products, platforms, and implementations.

ADRF is an attempt to provide a common language for identifying, discussing, and classifying these risks.

ADRF focuses on recurring risk patterns rather than product-specific behavior. Products may be referenced as examples, but the framework is concerned with design risks that can emerge across AI systems.

---

## ADRF Principles

Evolving AI systems are expected to contain design risks.

The goal of ADRF is not to eliminate every flaw or limitation.

The goal is to identify recurring risk patterns, establish a common language for discussing them, and improve collective understanding of their potential implications.

For the complete set of principles, see:

- framework/ADRF-Principles.md

---

## ADRF Observations

ADRF Observations capture recurring insights discovered during the exploration of AI design risks.

Current observations:

- ADRF-OBS-01: When transparency is hidden, risk evolves naturally.

For details, see:

- framework/ADRF-Observations.md

---

## Current Risk Entries

| ID | Risk | Status |
|------|------|------|
| ADRF-01 | Non-Explanatory Metrics | Draft |

For details, see:

- risks/ADRF-01.md

---

## Repository Structure

```text
/
├── README.md
├── LICENSE
├── framework/
│   ├── ADRF-Principles.md
│   └── ADRF-Observations.md
└── risks/
    ├── README.md
    └── ADRF-01.md
```

---

## Disclaimer

ADRF represents independent observations and analysis of AI system design patterns.

The framework is not affiliated with, endorsed by, or associated with any organization, product, platform, or vendor.
