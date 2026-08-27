# The UTIOM Framework Family

UTIOM is the **operating model**. Supporting models and tools add measurement depth or exploitation context without becoming additional UTIOM lifecycle phases.

The family shares one central premise: Security Operations should be directed by business consequence and relevant threats, then engineered, validated, measured and improved as one connected system.

## UTIOM

**Unified Threat-Informed Operations Model**  
Role: **the operating model**  
Current public framework release: **v1.3**  
Architecture: **7 phases · 3 pillars · 4 assessment instruments plus capability dashboard**

UTIOM defines how leadership intent, engineering discipline and operational execution should connect. It answers the system-level question: **How should Security Operations be run as one threat-informed operating model?**

Website: https://utiom.de

## TID-CMM

**Threat-Informed Detection Capability Maturity Model**  
Role: **the detection capability module**  
Current public site reference: **v1.5 · 8 domains · 58 sub-capabilities · MITRE ATT&CK Enterprise v19.2**

TID-CMM measures whether detection capability is genuinely threat-informed: whether relevant behaviours have been prioritised, the necessary telemetry exists, detection logic is engineered and traceable, and the capability has been validated.

It complements UTIOM by measuring the depth of the Threat Visibility and Threat Detection span. UTIOM supplies the strategic direction—threat profile, Crown Jewels and attack paths—that tells detection capability what it should be pointed at.

Website: https://tid-cmm.com

## TIR-CMM

**Threat-Informed Response Capability Maturity Model**  
Role: **the response capability module**  
Current public site reference: **v1.0 · 58 sub-capabilities · 3 assessment tiers**

TIR-CMM asks whether an organisation can turn detection into timely action: whether response authority exists before the incident, whether playbooks can be executed under time pressure, whether containment options are realistic, and whether the organisation can act inside the relevant adversary window.

The current public description includes concepts such as the **Containment Lattice**, **Containment Margin**, and explicit treatment of decision latency rather than hiding all delay inside MTTR.

Website: https://tir-cmm.com

## RSMM

**Realistic SIEM Maturity Model**  
Role: **the platform module**

RSMM focuses on the SIEM and monitoring platform that supports operational detection and analysis. It helps distinguish platform capability from the broader Security Operations operating model.

UTIOM does not define the SOC by its SIEM. The platform should serve the threat-informed operating model rather than become the operating model itself.

Website: https://rsmm.rezaadineh.com/

## KEVMAP

Role: **exploitation and exposure context**

KEVMAP is **not a maturity model and not a UTIOM lifecycle phase**. It supplies known-exploited-vulnerability and exposure context that can sharpen decisions already being made inside UTIOM.

It can inform:

- **Strategy** — which exploitation conditions and threats are currently important;
- **Crown Jewels** — which exposed technologies or dependencies change attack-path risk;
- **Threat Visibility** — which evidence is required around active exploitation paths;
- **Threat Detection** — which exploitation behaviours deserve priority.

Website: https://kevmap.io

## How the family connects

A useful way to interpret the relationships is:

**UTIOM decides direction. The capability models measure depth. Context services sharpen prioritisation.**

Examples:

- Crown Jewels and attack paths establish the scope that detection capability should protect.
- Threat Profiling establishes the adversaries and behaviours TID-CMM should measure against.
- Threat Visibility produces the telemetry-assurance evidence required for credible detection assessment.
- Detection-as-code and Detection QA connect UTIOM engineering to TID-CMM maturity.
- Response authority, playbooks and Response Horizon connect UTIOM Response to TIR-CMM.
- KEVMAP can change the priority of a threat or attack path without changing UTIOM's canonical architecture.

The order matters. A precise detection-maturity score without a Crown Jewel registry or threat profile can still describe an **undirected capability**: it tells the organisation how well it detects without first proving that it detects the right things.

## STRATA lens

The UTIOM Capability Dashboard also uses a derived **STRATA lens** to help identify organisational constraints affecting capability. STRATA supports interpretation; it is not an additional UTIOM lifecycle phase.

Canonical UTIOM website: https://utiom.de
