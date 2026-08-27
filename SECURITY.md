# UTIOM Security Policy and Vulnerability Reporting

Security matters to UTIOM because the public project includes a browser-based assessment toolkit, downloadable/self-hosted artifacts, Docker and nginx configuration, and links to the canonical UTIOM service.

This repository is the **public framework and community repository**. It is not the private production application repository, but security findings affecting the public toolkit, self-hosted package, published configuration, download integrity, or the live UTIOM service should still be reported responsibly.

## Supported public versions

| Component | Supported public version |
| --- | --- |
| UTIOM framework / public site | v1.3 |
| Assessment workbook | v1.3 |
| Self-hosted assessment toolkit | v1.3 |
| UTIOM Framework Book | v1.1 — documentation only |

Security fixes are normally applied to the current public toolkit/site release rather than maintaining security branches for every historical public release.

## Report a vulnerability privately

**Do not publish a suspected vulnerability, exploit, credential, token, sensitive endpoint, or reproduction containing sensitive data in a public GitHub Issue or Discussion.**

Preferred reporting paths:

1. If GitHub displays **Report a vulnerability** in this repository's **Security** area, use that private reporting channel.
2. Otherwise, use the security contact method published on the canonical UTIOM website: https://utiom.de

Normal GitHub Issues remain appropriate for non-sensitive matters such as documentation errors, broken public links, typos, inaccurate mappings, visual problems, or framework inconsistencies that do not expose a security weakness.

## What should be reported

Examples include suspected vulnerabilities affecting:

- the public browser-based UTIOM assessment toolkit;
- the self-hosted/Docker distribution;
- published nginx or other security-relevant configuration;
- the canonical UTIOM website or public assessment service;
- authentication or authorization behaviour if such functionality is introduced;
- cross-site scripting, injection, path traversal, request forgery, unsafe file handling, or similar web vulnerabilities;
- exposure of credentials, tokens, secrets, environment variables, private keys, or sensitive configuration;
- administrative interfaces or non-public endpoints exposed unintentionally;
- download or artifact integrity;
- dependency or supply-chain weaknesses that materially affect the public toolkit;
- privacy weaknesses that could expose assessment answers or other user data;
- vulnerabilities that create an unexpected network connection or transmit assessment data contrary to the stated browser-local design;
- a public repository file that unintentionally reveals private production or infrastructure information.

## What to include in a report

Please provide enough information to reproduce and evaluate the issue safely:

- affected URL, file, component, or version;
- vulnerability type and expected security impact;
- clear reproduction steps or a minimal proof of concept;
- relevant request/response details, screenshots, logs, or configuration excerpts where useful;
- prerequisites or environmental assumptions;
- whether the issue affects the live service, self-hosted toolkit, public repository, or more than one of these;
- any suggested remediation, if known.

Please remove unrelated personal data, customer information, credentials, and secrets from reports.

## Responsible testing boundaries

Good-faith security research is welcome when it is limited to what is necessary to demonstrate the issue safely.

Please do **not**:

- access, modify, delete, or retain data that does not belong to you;
- attempt denial-of-service, resource exhaustion, or destructive testing;
- use social engineering, phishing, physical attacks, or credential theft;
- establish persistence or move laterally into unrelated systems;
- perform broad automated scanning that could degrade the live service;
- publish sensitive details before a reasonable opportunity to investigate and remediate;
- attempt to obtain private repository contents, production credentials, customer data, or proprietary implementation material beyond what is strictly necessary to demonstrate an accidental exposure.

If testing reveals sensitive data, stop further access, preserve only the minimum evidence needed for the report, and report it privately.

## Coordinated disclosure

UTIOM asks reporters to allow a reasonable period for investigation and remediation before public disclosure. Where appropriate, the maintainer may coordinate timing and technical details with the reporter.

Submitting a report does not create a promise of payment or a bug bounty. If a formal bounty or acknowledgement programme is introduced later, it will be documented separately.

## Public/private implementation boundary

The public availability of UTIOM documentation, assessment artifacts, or the community/self-hosted edition does **not** mean the following are public:

- private production source code;
- deployment architecture not intentionally published;
- credentials, tokens, keys, or secrets;
- private automation and proprietary enterprise functionality;
- administrative systems;
- non-public APIs;
- customer or assessment data;
- future commercial implementation material.

A vulnerability report may describe an accidental exposure of such material, but reporters should not intentionally seek additional private material after the exposure has been demonstrated.

## Security contact authority

The canonical project website is https://utiom.de. Security instructions published there and this repository's `SECURITY.md` are the authoritative public reporting guidance for UTIOM.
