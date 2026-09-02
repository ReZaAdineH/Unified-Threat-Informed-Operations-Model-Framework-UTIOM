# UTIOM self-hosted assessment toolkit

The UTIOM self-hosted toolkit supports local/internal operation when assessment data should remain under organisational control.

## Versions

- UTIOM framework / methodology: **v1.4**
- Website and tools: **v1.4**
- Assessment workbook: **v1.4**
- Self-hosted toolkit: **v1.4**
- UTIOM Framework Book: **v1.2**

Download the versioned package:

https://utiom.de/utiom-assessment-toolkit-v1.4.zip

## Docker quick start

```bash
docker compose up -d --build
```

Open:

```text
http://localhost:8080
```

## Security posture

The supplied bootstrap uses nginx 1.30.4-alpine, runs as a non-root user on port 8080, uses a read-only container filesystem, drops all Linux capabilities, enables no-new-privileges, disables access logging by default and applies a restrictive CSP including `connect-src 'none'`.

The toolkit is designed without a UTIOM assessment backend; assessment answers remain in the browser/local environment.

## Licence

The software/self-hosted implementation is provided under **PolyForm Internal Use License 1.0.0**. Framework/content included in the package remains subject to its applicable content licence, and assessment materials remain subject to their applicable assessment terms.

See [`../LICENSE`](../LICENSE) for the licensing map.

The self-hosted public/free package does not expose private infrastructure, customer data, unreleased enterprise automation or future proprietary commercial functionality.

UTIOM — Unified Threat-Informed Operations Model by Reza Adineh  
https://utiom.de
