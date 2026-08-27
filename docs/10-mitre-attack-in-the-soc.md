# MITRE ATT&CK in the SOC — The UTIOM Approach

MITRE ATT&CK is a knowledge base of adversary behaviour. UTIOM uses ATT&CK to help translate relevant threats and attack paths into observable behaviours, telemetry requirements, detections, validation and response.

The objective is **not to maximise ATT&CK technique coverage**. The objective is to build validated coverage for behaviours that matter to the organisation.

## Start with business consequence, not the matrix

UTIOM applies ATT&CK after the organisation has established:

1. business purpose;
2. Security Operations strategy;
3. Threat Profiling;
4. Crown Jewels and critical services;
5. threat models and realistic attack paths.

Those inputs define the relevant ATT&CK scope.

## From ATT&CK behaviour to telemetry

For each important behaviour, ask:

- Where could it occur in our environment?
- Which Crown Jewel or dependency could it affect?
- What evidence would the behaviour produce?
- Do we collect that evidence?
- Is the telemetry trustworthy and usable?

If the answer to the telemetry question is no, UTIOM creates a **Telemetry Engineering** requirement.

## From telemetry to detection

Detection Engineering then connects:

**relevant ATT&CK behaviour → required evidence → assured telemetry → versioned detection → validation → operational response**

Detection rules should be traceable to the threat model and business consequence that justified them.

## Detection quality over technique count

A large ATT&CK heatmap does not automatically demonstrate security capability. Coverage can be misleading when:

- techniques are irrelevant to the environment;
- required data sources are absent;
- rules have never been tested;
- detections are too noisy to operate;
- analysts cannot make a decision from the alert;
- responders cannot act in time.

UTIOM therefore combines ATT&CK with Threat Profiling, Crown Jewels, Telemetry Engineering, Detection QA, Purple Teaming and response readiness.

## DeTT&CT and TID-CMM

MITRE DeTT&CT can support visibility and detection coverage analysis. TID-CMM provides deeper measurement of threat-informed detection capability across the engineering span.

UTIOM supplies the operating context that answers **what should be measured and why**.

## Purple Team validation

Relevant ATT&CK behaviours can be emulated through Purple Team exercises to test the full chain:

**attack path → telemetry → detection → alert → analysis → decision → response**

Failed coverage becomes an engineering or operational improvement item rather than a cosmetic change to a heatmap.

## Practical outcome

The desired result is not “we cover ATT&CK.” It is:

> We know which adversary behaviours matter to our critical services, we can observe them, we have tested detections for them, and we can respond before unacceptable impact.

Canonical page: https://utiom.de/mitre-attack-soc/
