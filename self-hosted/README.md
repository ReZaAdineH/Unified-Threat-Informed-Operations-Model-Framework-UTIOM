# UTIOM self-hosted assessment toolkit

The public UTIOM assessment toolkit can be run locally or inside an organisation's own network when assessment data should remain under local control.

## Versions

- UTIOM framework: **v1.3**
- Website and tools: **v1.3**
- Assessment workbook: **v1.3**
- Self-hosted toolkit: **v1.3**
- UTIOM Framework Book: **v1.1** — a newer book edition is in preparation and will be published separately.

## Full toolkit download

Download the complete packaged toolkit from the canonical UTIOM site:

https://utiom.de/utiom-assessment-toolkit.zip

The package contains the static site, assessment instruments, diagrams, workbook, framework book and Docker configuration required to run the public toolkit locally.

## Docker quick start

From the extracted toolkit directory:

```bash
docker compose up -d --build
```

Then open:

```text
http://localhost:8080
```

The public self-hosted edition is designed to operate without a UTIOM backend. Assessment answers remain in the browser/local environment.

## Security posture of the supplied container configuration

The published configuration runs nginx as a non-root user on port 8080, uses a read-only container filesystem, drops Linux capabilities, enables `no-new-privileges`, disables access logging by default, and applies restrictive browser security headers including a Content Security Policy with `connect-src 'none'`.

## Public edition boundary

This directory contains configuration for the intentionally released **public/community self-hosted edition**. It does not represent or expose private production infrastructure, private administrative functionality, future enterprise services, credentials, deployment secrets or proprietary commercial implementation material.

UTIOM · Unified Threat-Informed Operations Model  
https://utiom.de
