# UTIOM — Unified Threat-Informed Operations Model

**Security operations designed as one system, not disconnected silos.**

**Current public framework release: v1.3 · August 2026**  
**Current UTIOM Framework Book: v1.1 — new edition coming soon**  
**Canonical website: https://utiom.de**  
**License: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**

UTIOM is an open cybersecurity and **Security Operations Center (SOC) operating framework** for **threat-informed defense, security architecture, threat modeling, telemetry engineering, detection engineering, incident response, purple teaming and continuous improvement**. It connects leadership intent, threat understanding, engineering discipline, operational response and measurable improvement into one connected system.

**Focus areas:** Security Operations · SOC Architecture · Threat-Informed Defense · Threat Modeling · Telemetry Engineering · Detection Engineering · Incident Response · Threat Intelligence · Purple Teaming · MITRE ATT&CK · NIST CSF · SOC Maturity

The model is built around a simple premise: security operations should not begin with tools, telemetry volume, alert counts or isolated controls. They should begin with purpose, business consequence and relevant threats, then engineer the visibility, detection and response capabilities required to protect what matters.

> **Purpose first → strategy first → business consequence → relevant threats → attack paths → required evidence → engineered visibility → engineered detection → operational response → measurable improvement.**

UTIOM treats security operations as a **living product**, a **living system**, and an **operating model for the security program** rather than a collection of independent SOC functions.

---

## Public downloads

UTIOM is intentionally published with free public/community resources so organisations can study the framework, assess themselves offline and run the public toolkit locally.

| Public artifact | Current version | Access |
| --- | ---: | --- |
| UTIOM framework / website | **v1.3** | https://utiom.de |
| Assessment workbook | **v1.3** | https://utiom.de/utiom-assessment-workbook.xlsx |
| Complete self-hosted assessment toolkit | **v1.3** | https://utiom.de/utiom-assessment-toolkit.zip |
| UTIOM Framework Book | **v1.1** | https://utiom.de/utiom-framework-v1.1.pdf |

> **Book edition note:** the currently published book remains **v1.1**. The framework and toolkit have continued to evolve to v1.3. A **new edition of the UTIOM Framework Book is in preparation and will be published soon**. The existing v1.1 book is not being relabelled as v1.3.

See [`downloads/README.md`](downloads/README.md) for the public distribution index and [`self-hosted/`](self-hosted/) for the Docker/nginx bootstrap configuration.

---

## Core diagrams

### UTIOM operating model

The operating model shows the three pillars, seven canonical phases, the engineering/operations OODA loop and the strategic decision-making feedback loop.

<p align="center">
  <a href="diagrams/utiom-operating-model.svg">
    <img src="diagrams/utiom-operating-model.svg" alt="UTIOM operating model" width="1200">
  </a>
</p>

<p align="center"><sub><b>Click the diagram to open the full-size SVG.</b></sub></p>

### UTIOM V-Model

The V-model pairs design and intent on the left with validation and operation on the right. Each major design decision must be proven operationally rather than accepted as an assumption.

<p align="center">
  <a href="diagrams/utiom-v-model.svg">
    <img src="diagrams/utiom-v-model.svg" alt="UTIOM V-Model" width="1200" style="width:100%;max-width:1200px;height:auto;">
  </a>
</p>

<p align="center"><sub><b>Click the diagram to open the full-size SVG.</b></sub></p>

---

## Canonical UTIOM lifecycle

UTIOM has exactly seven lifecycle phases:

1. **Vision**
2. **Strategy**
3. **Crown Jewels**
4. **Threat Visibility**
5. **Threat Detection**
6. **Response**
7. **Continuous Improvement**

The lifecycle contains ordered dependencies, but it is **not a rigid waterfall**. Engineering, operations and validation run iteratively, and operational evidence continuously feeds back into leadership decisions and future engineering work.

---

## Three operating pillars

- **Leadership & Governance**
- **Engineering & Enablement**
- **Operations & Analysis**

The purpose of the pillars is not to create new silos. Their purpose is to make ownership clear while preserving one connected operating model.

---

## Threat-to-outcome traceability

A core UTIOM requirement is end-to-end traceability:

**Business purpose**  
→ **Security Operations Strategy**  
→ **Threat Profiling**  
→ **Crown Jewels & Critical Services**  
→ **Threat Models**  
→ **Dependencies & Trust Boundaries**  
→ **Attack Paths**  
→ **Required Adversary Evidence**  
→ **Telemetry Engineering / Assurance**  
→ **Threat Detection / Detection Engineering**  
→ **Detection Validation**  
→ **Analysis & Decision**  
→ **Response**  
→ **Metrics & Evidence**  
→ **Continuous Improvement**

If an important behaviour must be observable but the evidence does not exist, the gap becomes a **Telemetry Engineering requirement** rather than being passively accepted as a detection limitation.

---

## Validation is part of the operating model

UTIOM pairs design with evidence that the design works.

**Purple Teaming + Detection QA + Response Exercising** validate the chain:

**Attack path → telemetry → detection → alert → analysis → decision → response**

Validation findings belong to the phase that owns the weakness. Missing evidence belongs in Telemetry Engineering; a silent or noisy rule belongs in the detection lifecycle; slow decision-making belongs in authority and response design; systemic lessons belong in Continuous Improvement.

---

## Assessment and measurement

UTIOM includes public browser-based assessment instruments for maturity, capability, metrics and improvement planning. The objective is not maturity for its own sake, but measurable operational capability and demonstrable risk reduction.

The current public site provides:

- **Maturity Assessment — 50 staged criteria**
- **Capability Assessment — 105 indicators**
- **Metrics Calculator — 70 explicit metrics**
- **Improvement Roadmap**
- **Capability Dashboard**

The public assessment tools run in the browser and are designed so assessment answers are not transmitted to a UTIOM backend.

Start at: https://utiom.de

---

## Framework family

UTIOM is the overarching operating model. Supporting models add measurement depth or decision context without becoming additional UTIOM lifecycle phases.

- **TID-CMM — Threat-Informed Detection Capability Maturity Model** — https://tid-cmm.com
- **TIR-CMM — Threat-Informed Response Capability Maturity Model** — https://tir-cmm.com
- **RSMM — Realistic SIEM Maturity Model** — https://rsmm.rezaadineh.com/
- **KEVMAP** — known-exploited-vulnerability and exposure context — https://kevmap.io

---

## Relationship to established standards

UTIOM does **not** replace MITRE ATT&CK, NIST, ISO, NIS2, DORA, SOC-CMM or other established frameworks and regulations.

It provides an operating model that helps translate governance, threat knowledge, engineering and response requirements into connected operational work.

---

## Repository scope and public/commercial boundary

This repository is the **public framework and community repository** for UTIOM.

It may contain:

- framework doctrine and terminology;
- lifecycle and pillar documentation;
- public diagrams;
- public mappings;
- implementation guidance and examples;
- assessment descriptions and public assessment artifacts;
- the public self-hosting/bootstrap configuration;
- research and citation material;
- change history.

It intentionally does **not** expose private production infrastructure, credentials, private administrative functionality, proprietary enterprise automation, customer data, non-public APIs or future commercial implementation material that has not been intentionally released.

**A publicly available framework, workbook or self-hosted community edition does not imply that every current or future UTIOM implementation is open source or must be provided free of charge.**

Material intentionally released for free remains available under the licence stated for that material. Future commercial offerings may add enterprise scale, collaboration, integrations, assurance, automation, hosting and professional services without retroactively withdrawing the public edition.

See [`PUBLIC-COMMERCIAL-BOUNDARY.md`](PUBLIC-COMMERCIAL-BOUNDARY.md).

---

## Author

**Reza Adineh**  
Creator of the Unified Threat-Informed Operations Model (UTIOM)

Website: https://utiom.de  
Author: https://rezaadineh.com

**Think smarter. Stay secure.**
