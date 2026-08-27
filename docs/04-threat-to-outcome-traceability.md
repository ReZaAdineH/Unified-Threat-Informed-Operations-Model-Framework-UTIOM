# UTIOM Threat-to-Outcome Traceability

UTIOM requires security-operations work to be traceable from business purpose to operational outcome. A tool, log source, detection rule or playbook should not exist merely because it is available; it should be connected to a relevant business consequence and threat.

## Canonical traceability chain

**Vision**  
→ **Security Operations Strategy**  
→ **Threat Profiling**  
→ **Crown Jewels and Critical Services**  
→ **Threat Models**  
→ **Dependencies and Trust Boundaries**  
→ **Attack Paths**  
→ **Required Adversary Evidence**  
→ **Threat Visibility / Telemetry Engineering**  
→ **Assured Telemetry**  
→ **Threat Detection / Detection Engineering**  
→ **Detection Validation**  
→ **Analysis and Decision**  
→ **Response**  
→ **Metrics and Evidence**  
→ **Continuous Improvement**

## Why the order matters

UTIOM begins with purpose and consequence rather than sensors and tools. The organisation first decides what matters, which threats are relevant, and how those threats could reach critical services. Only then can it determine what evidence must exist, which telemetry must be engineered, which detections are justified, and what response must be prepared.

This prevents a common failure mode: producing technically impressive detection coverage without knowing whether it covers the behaviours that could materially affect the organisation.

## Crown jewels are more than an asset list

A crown-jewel view includes the critical service or asset and the systems that make its compromise possible or consequential:

- dependencies;
- enabling systems;
- identities and privileged access;
- shared infrastructure;
- trust boundaries;
- data flows;
- realistic attack paths.

Threat Profiling and threat modelling connect these business-critical elements to relevant adversary behaviour.

## Required adversary evidence

For each important attack path, UTIOM asks what evidence an adversary would necessarily or plausibly leave behind. That evidence requirement drives Threat Visibility.

If an important behaviour must be observable but the evidence is not currently available, the answer is not to accept a permanent detection blind spot. The gap becomes a **Telemetry Engineering requirement**.

A useful telemetry-engineering pipeline is:

**Generate / Enable → Collect → Transport → Parse → Normalise → Enrich → Validate → Maintain**

The objective is not merely log ingestion. It is **assured telemetry**: evidence that is available, trustworthy, usable and maintained for the behaviours the organisation has decided matter.

## From evidence to detection

Detection Engineering consumes:

- relevant threats and high-priority behaviours;
- crown jewels and attack paths;
- available and assured telemetry;
- hunting and operational findings.

It produces versioned, testable detection logic with traceability back to the threat and consequence that justified it.

## From detection to outcome

A detection only creates value when the operational chain works:

**Detection → alert → analysis → decision → response → measurable outcome**

The result must then feed back into metrics, validation and Continuous Improvement. This makes the full chain bidirectional: strategic assumptions shape operations, while operational evidence challenges strategic assumptions.

## The UTIOM test

A mature implementation should be able to answer:

1. What business outcome or crown jewel is this capability protecting?
2. Which relevant threat or attack path justifies it?
3. Which adversary evidence is required?
4. Is that telemetry available and trustworthy?
5. Which detection uses it?
6. Has the detection been validated?
7. Can an analyst make the required decision?
8. Can responders act within the required horizon?
9. What evidence shows that the capability reduced risk or improved resilience?
10. What did the system learn and change?

Canonical website: https://utiom.de
