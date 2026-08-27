# UTIOM Lifecycle and Three Pillars

UTIOM has exactly seven canonical lifecycle phases and three canonical operating pillars. The lifecycle is ordered, but it is not a rigid waterfall. It uses **ordered dependencies with iterative engineering and operational feedback loops**.

## Seven canonical phases

### 1. Vision

Vision defines why Security Operations exists, what business outcomes matter, what must not fail, and how success will be measured.

Typical outputs include a clear Security Operations purpose, scope, ownership model and success metrics.

### 2. Strategy

Strategy converts Vision into priorities. It includes Security Operations strategy, risk context and **Threat Profiling** so the organisation can identify the adversaries, behaviours and threat scenarios that matter most.

### 3. Crown Jewels

Crown Jewels identifies the critical services, assets, data, identities and business capabilities whose compromise would create material consequence. The scope also includes dependencies, enabling systems, shared infrastructure, trust boundaries and realistic attack paths.

### 4. Threat Visibility

Threat Visibility engineers the evidence required to observe the relevant adversary behaviours and attack paths. Visibility is deliberately designed rather than passively accumulated.

If evidence is required but unavailable, the gap becomes a **Telemetry Engineering** requirement.

### 5. Threat Detection

Threat Detection turns relevant threats, crown jewels, attack paths and assured telemetry into engineered detection capability. Detection is treated as an engineering lifecycle: versioned, testable, maintainable and traceable.

### 6. Response

Response is the operational continuation of detection. UTIOM expects prepared escalation, decision authority, crown-jewel-specific playbooks, containment options, analysis and recovery rather than improvisation after impact.

### 7. Continuous Improvement

Continuous Improvement converts incidents, exercises, metrics, validation findings and operational lessons into a prioritised improvement backlog that feeds Strategy and engineering.

## Three canonical pillars

### Leadership & Governance

Contains the strategic and consequence-defining work:

- Vision
- Strategy
- Crown Jewels

Its role is to establish purpose, ownership, priorities, relevant threats and the business consequence lens that guides the rest of the system.

### Engineering & Enablement

Contains the capability-building work:

- Threat Visibility
- Threat Detection

Its role is to design telemetry, engineer detections, automate where appropriate, validate engineering assumptions and maintain operational capability.

### Operations & Analysis

Contains the operational execution and learning work:

- Response
- Continuous Improvement

Its role is to analyse, decide, contain, recover, learn and feed operational reality back into the rest of the lifecycle.

## Two OODA feedback loops

The current UTIOM operating model shows two OODA cycles that differ mainly in tempo.

**Incident-tempo OODA loop:** runs between Engineering & Enablement and Operations & Analysis. Operational findings drive rapid engineering changes, and engineering changes are tested through operations.

**Strategic-tempo decision loop:** carries operational evidence and outcomes back to Leadership & Governance so Strategy, threat priorities, crown-jewel assumptions and investment decisions can be updated.

## One system, not three silos

The pillars clarify responsibility but do not create separate operating silos. Each phase consumes and produces knowledge; the output of one becomes the input to the next.

Canonical website: https://utiom.de
