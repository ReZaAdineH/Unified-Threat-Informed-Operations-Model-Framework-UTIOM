# Build a SOC from Scratch or Improve an Existing SOC with UTIOM

UTIOM is designed for both greenfield Security Operations and existing SOCs at different maturity levels. The framework does not require a new technology stack; it provides the operating logic for deciding what should exist, what should improve first and how the result should be validated.

## Building a SOC from scratch

Start at **Vision** and work forward.

### Vision

Define why Security Operations exists, which business outcomes matter, scope, ownership and success measures.

### Strategy

Develop the Security Operations strategy and Threat Profile. Identify relevant adversaries, business context and priority scenarios before choosing sensors or detection content.

### Crown Jewels

Identify critical services, assets, data and identities together with dependencies, trust boundaries and realistic attack paths.

### Threat Visibility

Determine the adversary evidence required along those paths. Design the telemetry architecture and create Telemetry Engineering requirements for missing evidence.

### Threat Detection

Engineer versioned detections from relevant threats, protected assets, attack paths and assured telemetry. Define tests and Detection QA from the beginning.

### Response

Prepare analysis, escalation, authority, Crown-Jewel-specific playbooks, decision gates and containment options before an incident requires them.

### Continuous Improvement

Establish metrics, validation, exercises, review cycles and an improvement backlog so the SOC can learn as it operates.

The technology stack should emerge from these requirements rather than become the starting architecture.

## Improving an existing SOC

An existing operation can begin with the public UTIOM assessment system:

1. **Assess** maturity, capability and metrics.
2. **Prioritise** gaps by business consequence and operational dependency.
3. **Engineer** the required governance, telemetry, detection or response changes.
4. **Validate** them through Detection QA, Purple Teaming and response exercising.
5. **Measure** whether capability and outcomes changed.
6. **Improve** the backlog and Strategy.
7. **Reassess**.

This creates the repeating cycle:

**Assess → Prioritise → Engineer → Validate → Measure → Improve → Assess**

## Internal SOC

UTIOM can clarify end-to-end ownership inside one organisation, especially where governance, architecture, detection and Incident Response are split between departments.

## Outsourced SOC or MDR/MSSP

Outsourcing execution does not outsource accountability for the operating model. The customer still needs to define Crown Jewels, threat priorities, evidence requirements, escalation, decision authority and expected outcomes.

A service provider can own parts of the lifecycle, but the links between phases must remain explicit.

## Hybrid SOC

Hybrid environments are a natural UTIOM use case because responsibilities are distributed. The model provides a shared traceability chain across internal engineering, service providers, cloud teams, IT operations, Incident Response and leadership.

## Low-maturity SOC

UTIOM can provide basic structure: purpose, ownership, priorities, staged maturity foundations, essential telemetry and repeatable response.

## Higher-maturity SOC

UTIOM can expose subtler weaknesses such as undirected detection coverage, insufficient validation, decision latency, telemetry trust problems or weak feedback between operational evidence and Strategy.

## The principle

Whether the SOC is new or established, the goal is the same: **one measurable Security Operations system focused on relevant threats and business consequence rather than disconnected activity.**

Canonical website: https://utiom.de
