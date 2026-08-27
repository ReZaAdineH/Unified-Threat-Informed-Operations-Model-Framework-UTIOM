# UTIOM Diagrams Guide

UTIOM uses diagrams to explain relationships that are difficult to communicate through a linear checklist. Diagrams clarify the canonical lifecycle, the operating architecture, validation relationships, traceability and improvement loops. They explain the framework; they do not replace its canonical seven phases.

## Canonical V-Model

Repository diagram: [`../diagrams/utiom-v-model.svg`](../diagrams/utiom-v-model.svg)

The V-Model pairs design intent with operational validation:

**Design:** Vision → Strategy → Crown Jewels → Threat Visibility  
**Engineering base:** Detection Engineering  
**Validation:** Detection QA → Purple Team → Response → Improvement

Its purpose is requirements traceability: important design assumptions should have corresponding evidence that they work.

## UTIOM Operating Model

Repository diagram: [`../diagrams/utiom-operating-model.svg`](../diagrams/utiom-operating-model.svg)

The operating-model view shows:

- three pillars;
- seven canonical phases;
- the iterative loop between Threat Visibility and Threat Detection;
- TID-CMM measuring the engineering span;
- TIR-CMM measuring response and improvement depth;
- an OODA loop at incident tempo;
- a decision-making/OODA loop at strategic tempo.

The two feedback loops differ primarily in tempo: one accelerates engineering and operational adaptation; the other carries operational reality back into leadership decisions.

## Threat-to-Outcome Traceability

The traceability view follows:

**Vision → Strategy → Threat Profiling → Crown Jewels → Threat Models → Dependencies and Trust Boundaries → Attack Paths → Required Adversary Evidence → Telemetry Engineering → Assured Telemetry → Detection Engineering → Validation → Analysis → Decision → Response → Metrics → Continuous Improvement**

See [Threat-to-Outcome Traceability](04-threat-to-outcome-traceability.md).

## Validation rail

The validation rail tests:

**Attack path → telemetry → detection → alert → analysis → decision → response**

It makes **Detection QA**, Purple Teaming and response exercising first-class parts of the framework.

## Improvement cycle

The current public UTIOM improvement loop is:

**Assess → Prioritise → Engineer → Validate → Measure → Improve → Assess**

The cycle is continuous, not a one-off programme.

## Response Horizon

The Response Horizon explains why prepared decision authority, evidence and playbooks matter before impact. Defensive leverage generally reduces as an adversary approaches business impact, while the cost and difficulty of intervention increase.

See [Validation, Detection QA and the V-Model](05-validation-and-v-model.md).

## Phase inputs and outputs

A process view of UTIOM shows that each lifecycle phase consumes knowledge and produces knowledge that becomes input to the next phase. This is why UTIOM should not be implemented as seven disconnected workstreams.

## Framework-family view

The framework-family view distinguishes the operating model from its supporting capability models and context sources:

- UTIOM — operating model;
- TID-CMM — detection capability depth;
- TIR-CMM — response capability depth;
- RSMM — SIEM/platform maturity perspective;
- KEVMAP — exploitation/exposure context.

Supporting products are not additional UTIOM phases.

## Canonical visual library

The canonical website contains the broader visual reference library, including additional process, standards and comparison views.

Canonical diagrams page: https://utiom.de/diagrams/
