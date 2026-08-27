# UTIOM Validation, Detection QA and the V-Model

UTIOM does not treat design intent as proof of capability. The V-Model pairs design decisions on the left with validation activities on the right so that important assumptions are tested operationally.

## The canonical UTIOM V-Model

### Design and intent

- **Vision** — purpose and metrics
- **Strategy** — Security Operations threat profile
- **Crown Jewels** — attack paths
- **Threat Visibility** — telemetry design

### Engineering base

- **Detection Engineering** — detection-as-code

### Validation and operation

- **Detection QA** — is the telemetry and detection chain proven?
- **Purple Team** — are the relevant attack paths and behaviours proven?
- **Response** — are operational priorities, authority and playbooks proven?
- **Improvement** — are the outcomes and strategic assumptions proven?

The core rule is simple: **every important design decision should have a corresponding validation activity.**

## The validation rail

UTIOM uses Purple Teaming, Detection QA and response exercising to validate the operational chain:

**Attack path → telemetry → detection → alert → analysis → decision → response**

A weakness discovered during validation belongs to the part of the system that owns it:

- missing evidence → **Telemetry Engineering**;
- unusable or unreliable telemetry → telemetry assurance and data quality;
- silent, noisy or brittle detection → **Detection Engineering / Detection QA**;
- unclear triage or analysis → operational analysis design;
- slow or blocked containment → response authority and playbook design;
- repeated systemic weakness → **Continuous Improvement**.

## Detection QA

Detection QA is not simply checking whether a rule compiles. UTIOM expects evidence that the detection can work in the environment it is supposed to protect.

Useful validation layers include:

1. **logic and syntax testing** — does the detection behave as designed?
2. **telemetry validation** — does the required evidence actually arrive with sufficient quality?
3. **adversarial validation** — does realistic behaviour trigger the expected detection and operational workflow?

Failed detections should be treated as engineering defects rather than accepted as unavoidable SOC noise.

## Purple Teaming

Purple Teaming validates the assumptions connecting Threat Profiling, threat models, attack paths, telemetry and detections. Exercises should emulate behaviours that matter to the organisation rather than pursue technique counts for their own sake.

This is why UTIOM links Purple Teaming to crown jewels and relevant adversaries.

## Response Horizon

The **Response Horizon** expresses a central UTIOM response principle: defensive leverage is usually greatest before business impact, while the cost and difficulty of intervention rise as an adversary moves closer to impact.

UTIOM therefore tries to move response decisions left by preparing before the incident:

- decision authority;
- escalation thresholds;
- crown-jewel playbooks;
- containment options;
- required evidence;
- communications and ownership;
- exercises under realistic time pressure.

The objective is not simply a lower MTTR after impact. It is the ability to make the right decision and act while meaningful options still exist.

## Why the right arm matters

The V-Model protects UTIOM from becoming a framework of untested intentions. Threat models, logging plans, detection repositories and response documents can all look mature on paper. Validation asks whether they work together under realistic conditions.

Canonical V-Model: [`../diagrams/utiom-v-model.svg`](../diagrams/utiom-v-model.svg)

Canonical website: https://utiom.de
