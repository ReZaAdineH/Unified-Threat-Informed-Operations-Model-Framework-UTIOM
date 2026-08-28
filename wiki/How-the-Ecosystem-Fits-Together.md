# How the Ecosystem Fits Together

The UTIOM Ecosystem is designed as a set of connected but distinct layers.

## 1. Operating model

**UTIOM** defines how Security Operations should work as one connected, threat-informed system.

It establishes the direction and traceability chain:

**Vision → Security Operations Strategy → Threat Profiling → Crown Jewels and Critical Services → Threat Models → Dependencies and Trust Boundaries → Attack Paths → Required Adversary Evidence → Threat Visibility / Telemetry Engineering → Assured Telemetry → Threat Detection / Detection Engineering → Detection Validation → Analysis and Decision → Response → Metrics and Evidence → Continuous Improvement**

This is the architectural backbone of the ecosystem.

## 2. Detection capability depth

**TID-CMM** provides specialist measurement of whether the detection side of the operating model is mature, evidence-based and threat-informed.

Its practical question is:

> **Would we see the relevant adversary behaviour?**

TID-CMM deepens the areas around threat prioritisation, threat modelling, telemetry, detection engineering, adversarial validation, hunting and the detection-to-response interface.

It does not replace UTIOM.

## 3. Response capability depth

**TIR-CMM** provides specialist measurement of whether response capability can make the right decision and execute action in time.

Its practical question is:

> **Could we make the right response decision and act in time?**

TIR-CMM deepens authority, response engineering, containment, validation, response tempo and recovery-related capability.

It does not replace UTIOM.

## 4. Platform maturity

**RSMM** provides a practical maturity view of the SIEM and monitoring platform layer.

Its role is to help assess whether the technical platform that supports Security Operations is realistically capable of doing the work expected of it.

The platform supports the operating model; it does not define the operating model.

## 5. Exploitation and exposure context

**KEVMAP** enriches prioritisation with known-exploited-vulnerability and exposure context.

Its role is contextual rather than structural. It can influence prioritisation in areas such as Strategy, Crown Jewels, Threat Visibility and Threat Detection.

It is not a maturity model and not a lifecycle phase.

## 6. Assessment and assurance

The UTIOM assessment toolkit and specialist capability models answer different questions:

- **UTIOM maturity** — how mature is the overall operating model?
- **UTIOM capability** — where are the weakest operational capabilities?
- **UTIOM metrics** — is the system improving?
- **TID-CMM** — how mature and proven is detection capability?
- **TIR-CMM** — how mature and proven is response capability?
- **RSMM** — how mature is the SIEM/monitoring platform layer?
- **KEVMAP** — which exploited-vulnerability/exposure context should sharpen prioritisation?

## 7. Community and evidence

The ecosystem community is part of the improvement mechanism:

**Slack conversation → GitHub Discussion/Issue → evidence and review → accepted improvement → versioned framework/model update**

That flow helps prevent useful practitioner knowledge from disappearing into private chat while still allowing fast informal collaboration.

## One ecosystem, not one giant framework

The UTIOM Ecosystem should remain modular.

The goal is not to merge every useful concept into UTIOM itself. The goal is to let each component solve a clear problem while remaining traceable back to the overarching operating model.

A useful rule is:

> **If a new component cannot clearly explain what it measures, validates, enriches or enables within the existing operating model, it probably does not belong in the ecosystem yet.**
