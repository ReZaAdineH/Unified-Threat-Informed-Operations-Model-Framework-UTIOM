# UTIOM — Unified Threat-Informed Operations Model

**Security operations designed as one system, not disconnected silos.**

**Current public framework release: v1.4 · September 2026**  
**Current UTIOM Framework Book: v1.2**  
**Current assessment workbook/toolkit: v1.4**  
**Canonical website: https://utiom.de**

UTIOM is a threat-informed **Security Operations operating framework** created by **Reza Adineh**. It connects leadership intent, business consequence, threat understanding, engineering discipline, operational response, evidence and continuous improvement into one system.

> **Purpose → strategy → business consequence → relevant threats → attack paths → required evidence → engineered visibility → engineered detection → operational response → validation → measurable improvement.**

UTIOM treats Security Operations as a **living product and socio-technical system**, not a collection of independently optimised tools and teams.

## Canonical architecture

### Three operating pillars

- **Leadership & Governance** — the management and control plane of UTIOM. It establishes Vision, Strategy, Crown Jewel priorities, decision authority, investment, governance and performance oversight, and receives operational evidence through the strategic feedback loop.
- **Engineering & Enablement** — builds and maintains the evidence, telemetry, detection and enabling mechanisms required by the threat-informed design.
- **Operations & Analysis** — monitors, analyses, investigates, decides, responds and feeds operational evidence back into the system.

### Seven lifecycle phases

**Vision → Strategy → Crown Jewels → Threat Visibility → Threat Detection → Response → Continuous Improvement**

The phases have ordered dependencies, but UTIOM is not a rigid waterfall. Engineering, operations and validation iterate continuously.

### Three cross-cutting enablers

- **Talent**
- **Validation**
- **Threat Hunting**

These are **not lifecycle phases**. They operate across multiple phases and pillars, even where they have a primary assessment home.

### STRATA organisational lens

**Strategy · Talent · Resilience · Automation · Telemetry · Adaptability**

STRATA describes organisational conditions that enable UTIOM. It does not replace the pillars, lifecycle or cross-cutting enablers and does not independently change UTIOM scores.

### Three v1.4 assessment tiers

1. **Strategic & Governance Foundation**
2. **Engineering & Operational Capability**
3. **Assurance & Evolution**

The tiers provide a **system-integrity view of assessment results**. They do not replace UTIOM's three pillars, seven lifecycle phases or three cross-cutting enablers.

## Assessment architecture

UTIOM v1.4 preserves the existing public assessment content:

- **50 staged maturity criteria**
- **105 capability indicators across 10 domains**
- **70 explicit metrics**
- Improvement Roadmap
- Capability Dashboard

v1.4 separates different result types more clearly:

- **Staged Maturity Assessment** — evaluates whether foundational practices are established across the six stages.
- **Diagnostic Capability / Tier Index** — continuous diagnostic information for prioritisation and comparison.
- **Governed UTIOM Maturity** — the official system-level ordinal maturity result after tier/system constraints are applied.

Advanced activity should not simply average away missing system foundations.

## Threat-to-outcome traceability

**Business consequence → Crown Jewel → asset/dependency → relevant adversary → realistic attack path → ATT&CK behaviour → required evidence → telemetry → detection/hunt → analysis → decision → response → validation → governance review → strategy/investment change**

If required evidence does not exist, the gap becomes a **Telemetry Engineering requirement**.

## Framework family and improvement paths

UTIOM remains independently usable as the overarching operating model. Supporting models and services provide optional deeper analysis when UTIOM results indicate a relevant gap; they are not blended into UTIOM scoring and do not raise UTIOM maturity automatically.

- **TID-CMM** — deeper threat-informed detection and visibility capability — https://tid-cmm.com
- **TIR-CMM** — deeper threat-informed response readiness — https://tir-cmm.com
- **RSMM** — deeper SIEM/monitoring-platform maturity where telemetry, detection or platform capability needs attention — https://rsmm.rezaadineh.com/
- **Threat Hunting / Daily Hunt** — deeper operational hunting improvement path — https://hunt.utiom.de/
- **KEVMAP** — exploited-vulnerability and exposure context — https://kevmap.io

## Public downloads

| Public artifact | Current version | Canonical access |
| --- | ---: | --- |
| UTIOM framework / website | **v1.4** | https://utiom.de |
| Assessment workbook | **v1.4** | https://utiom.de/utiom-assessment-workbook.xlsx |
| Self-hosted assessment toolkit | **v1.4** | https://utiom.de/utiom-assessment-toolkit-v1.4.zip |
| UTIOM Framework Book | **v1.2** | https://utiom.de/downloads/UTIOM-Framework-v1.2.pdf |

Book v1.2 remains Book Edition v1.2; the v1.4 assessment architecture is not being falsely relabelled as a new book edition.

## Repository scope

This is the **public framework and community repository**. It contains intentionally public doctrine, documentation, diagrams, mappings, guidance, citation material and the limited self-hosting bootstrap configuration.

It does **not** expose private production infrastructure, credentials, private APIs, customer data, unreleased enterprise automation, proprietary managed-service logic or future commercial implementation material.

## Licensing boundary

UTIOM uses a split licensing model:

- **Framework / methodology / Book / framework diagrams / public framework documentation:** CC BY-SA 4.0.
- **Software and self-hosted implementation:** PolyForm Internal Use License 1.0.0.
- **Assessment workbook and non-software free assessment instruments:** UTIOM Free Assessment Use Terms.
- **Future enterprise/commercial functionality:** proprietary unless separately licensed.

Free access means **free to use within the granted terms**, not transfer of ownership and not unrestricted rights to repackage, resell, white-label or offer a competing hosted implementation.

Historical copies remain governed by the licence under which those copies were originally released.

See [`LICENSE`](LICENSE), [`LICENSE-FRAMEWORK.md`](LICENSE-FRAMEWORK.md), [`LICENSE-SOFTWARE.md`](LICENSE-SOFTWARE.md), [`LICENSE-ASSESSMENT.md`](LICENSE-ASSESSMENT.md) and [`PUBLIC-COMMERCIAL-BOUNDARY.md`](PUBLIC-COMMERCIAL-BOUNDARY.md).

## Community

UTIOM is intended to improve through practitioner use, evidence-backed criticism and transparent peer review. Start with [`COMMUNITY.md`](COMMUNITY.md) and [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Author

**Reza Adineh**  
Creator of the Unified Threat-Informed Operations Model (UTIOM)

Canonical website: https://utiom.de  
Author site: https://rezaadineh.com

**Think smarter. Stay secure.**
