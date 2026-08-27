# UTIOM Assessment, Measurement and Continuous Improvement

UTIOM v1.3 includes a public assessment system designed to answer three different questions: **Where are we? What should we improve? Did the improvement work?** The outputs can then be combined into an improvement roadmap and capability dashboard.

## 1. Maturity Assessment

**50 gated criteria across six maturity levels.**

Question answered: **Where are we, honestly?**

The maturity model is staged rather than averaged. Advanced practices do not compensate for a missing lower-level foundation. If a required criterion at a lower level is not met, the maturity result is capped accordingly.

This is intended to prevent maturity scores that look high because sophisticated activity exists in isolated areas while basic operating foundations remain absent.

## 2. Capability Assessment

**105 indicators across ten lifecycle domains, scored from 0–5.**

Question answered: **What should we fix first?**

The capability view provides more granular evidence about where operational depth is strong or weak. It complements the staged maturity result by exposing specific capability gaps that can be prioritised for engineering or governance action.

## 3. Metrics Calculator

**70 leading and lagging metrics with explicit formulas.**

Question answered: **Did the fix actually work?**

The current public metric set includes operational measures such as:

- Mean Time to Detect (MTTD);
- Mean Time to Contain (MTTC);
- Mean Time to Respond / Recover where applicable;
- validation rate;
- crown-jewel coverage;
- telemetry and detection quality measures;
- response timing against relevant adversary breakout windows.

Metrics are not intended to reward activity volume. They should show whether the operating system is becoming more capable and whether risk-reduction decisions are producing measurable effects.

## 4. Improvement Roadmap

The roadmap combines assessment results into a sequenced improvement view.

Question answered: **So what do we actually do about it?**

The objective is to turn findings into a practical backlog rather than leave them as maturity scores. The roadmap supports prioritised near-term work, including a 90-day improvement horizon where appropriate.

## 5. Capability Dashboard

The dashboard is a **derived view** of completed assessments.

Question answered: **Why is the operation where it is?**

It presents:

- the seven UTIOM lifecycle phases;
- supporting capability domains;
- a derived STRATA lens that helps identify likely organisational constraints.

The dashboard does not add assessment questions and does not change the underlying scores.

## The continuous improvement cycle

UTIOM expresses improvement as a repeating operating cycle:

**Assess → Prioritise → Engineer → Validate → Measure → Improve → Assess**

**Continuous — not a one-off programme.**

The important distinction is that assessment is not the destination. Assessment identifies what needs attention; engineering changes the system; validation proves whether it works; metrics show whether outcomes changed; Continuous Improvement feeds the evidence back into the next decision cycle.

## Privacy model

The current public browser-based tools are designed with no UTIOM assessment backend, no UTIOM assessment database, no analytics and no signup. Assessment answers remain in the user’s browser/device so the tools can combine results locally.

For organisations that prefer an offline or internal workflow, UTIOM also provides:

- an assessment workbook;
- a complete self-hosted toolkit;
- Docker/nginx bootstrap configuration.

Public downloads: https://utiom.de

## Using UTIOM for a new or existing SOC

### Building from scratch

Start at Vision and work forward. Define purpose, operating model, Crown Jewels, threat priorities, visibility requirements, detection engineering, response capability and measurement before technology begins to determine the design.

### Improving an existing SOC

Use the assessments and roadmap to identify gaps and prioritise improvement. The same logic applies to internal, outsourced and hybrid Security Operations, whether reactive or already mature.

UTIOM does not require the organisation to discard its existing tools, teams, standards or providers. It provides the operating logic that connects them.

Canonical assessment site: https://utiom.de/#tools
