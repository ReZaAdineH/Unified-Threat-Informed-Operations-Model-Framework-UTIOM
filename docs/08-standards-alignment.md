# UTIOM Standards and Framework Alignment

UTIOM does not replace established cybersecurity standards, regulations or knowledge bases. It provides an operating model that helps translate them into connected Security Operations work.

The canonical UTIOM site provides a more detailed domain-by-domain standards mapping. This page records the public high-level relationships in a citation-friendly form.

## NIST Cybersecurity Framework 2.0

NIST CSF 2.0 defines cybersecurity outcomes. UTIOM provides an operating model for delivering those outcomes through day-to-day Security Operations.

At a high level:

- **Vision and Strategy** support **Govern** by connecting purpose, accountability, risk ownership and operational priorities.
- **Crown Jewels** support **Identify** by prioritising critical services, assets, dependencies and business consequence.
- preventive guardrails and architectural decisions support **Protect** where relevant.
- **Threat Visibility and Threat Detection** operationalise **Detect** through telemetry and detection engineering.
- **Response** operationalises **Respond** through analysis, decision, escalation, containment and recovery workflows.
- **Continuous Improvement** supports improvement and recovery by feeding operational lessons back into the system.

A useful distinction is: **NIST CSF defines outcomes; UTIOM defines an operating model that can deliver and evidence them.**

## ISO/IEC 27001:2022

UTIOM aligns operational work to governance, planning, asset management, logging, monitoring, incident-management and continual-improvement requirements found in ISO/IEC 27001:2022 and its Annex A controls.

The relationship is complementary: ISO establishes management-system and control requirements; UTIOM connects relevant requirements to a threat-informed operational lifecycle.

## MITRE ATT&CK

MITRE ATT&CK describes adversary behaviour. UTIOM uses ATT&CK as a behaviour knowledge base rather than as a coverage target by itself.

The UTIOM logic is:

**business consequence → relevant threats → attack paths → in-scope adversary behaviours → required evidence → telemetry → detection → validation → response**

This prevents technique count from replacing risk prioritisation.

## MITRE DeTT&CT

DeTT&CT can help evaluate visibility and detection coverage against ATT&CK behaviours. UTIOM provides the strategic context that determines which behaviours and Crown Jewels should receive priority.

## SOC-CMM

SOC-CMM measures Security Operations maturity. UTIOM provides an operating mechanism for improving the system across governance, engineering and operational execution.

A useful distinction is: **SOC-CMM asks how mature the SOC is; UTIOM helps define how the operating system should work and improve.**

## DORA

The Digital Operational Resilience Act requires operational resilience, incident management and evidence of effective ICT-risk capabilities. UTIOM supports those objectives through:

- Crown-Jewel-driven prioritisation;
- threat-informed risk context;
- engineered visibility and detection;
- structured incident classification and escalation;
- prepared response authority and playbooks;
- measurable continuous improvement.

UTIOM does not claim that implementing the framework automatically establishes regulatory compliance. It helps create operational processes and evidence that can support a wider DORA compliance programme.

## NIS2

NIS2 requires organisations in scope to implement and assess appropriate cybersecurity risk-management measures. UTIOM can support the operational side of that requirement by making security capability traceable from governance and business consequence through detection, response, validation and evidence.

As with DORA, UTIOM is not a substitute for legal or compliance analysis.

## Detection and response standards

UTIOM can also coexist with recognised incident-response, detection, logging, CSIRT and engineering guidance. The framework's role is to preserve end-to-end traceability so that external requirements do not become disconnected checklists.

## Core principle

**Standards can map to UTIOM; they do not redefine UTIOM.**

The canonical seven phases remain:

**Vision → Strategy → Crown Jewels → Threat Visibility → Threat Detection → Response → Continuous Improvement**

Canonical detailed alignment page: https://utiom.de/standards-alignment/
