# Lavante

Lavante was a SaaS **supplier information management (SIM)** and **profit-recovery** company built on its
patented **Lavante Connect** platform. Its products — Lavante SIM, Lavante Recovery and Vendor File Cleanse
— cleansed vendor master files, verified addresses and TINs, ran OFAC screening, onboarded suppliers onto
the Lavante Supplier Network, and drove dispute resolution and recovery audit across the procure-to-pay
(P2P) ecosystem for Fortune 1000 clients.

## Status: acquired — no API surface

Lavante was **acquired by PRGX Global** (banner "PRGX Global Completes Acquisition of Lavante" appears on
the site from November 2016). The Lavante-branded site ran on as a PRGX property until mid-2022, then was
retired: `www.lavante.com` has returned an HTTP **302 to `www.prgx.com`** since 2023. The supplier-facing
capability lives on as **[PRGX Supplier Connect](https://www.prgx.com/solutions/supplier-connect/)**.

**Lavante never published a public API, developer portal, SDKs, or API documentation.** A sweep of the
Internet Archive's full URL index for `lavante.com` returned no `api`/`developer`/`docs`/`swagger`/`oauth`/
`webhook` paths. Package registries (npm, PyPI, RubyGems, NuGet, Packagist, crates.io) hold no first-party
Lavante libraries. Accordingly the spec-bearing artifacts — OpenAPI, overlays, errors, data model, skills,
scopes, conventions, MCP, sandbox, CLI, components, AsyncAPI, gRPC — are **not applicable** and were
deliberately not generated.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Lifecycle (acquisition + domain retirement) | `lifecycle/lavante-lifecycle.yml` | searched |
| Conformance (historical SOC / OFAC claims) | `conformance/lavante-conformance.yml` | searched |
| Well-Known index (all absent) | `well-known/lavante-well-known.yml` | searched |
| llms.txt (successor entity, PRGX) | `llms/lavante-llms.txt` | searched |
| Domain security | `security/lavante-domain-security.yml` | probed |

Investors: **Sapphire Ventures**, **PointGuard Ventures**, **ATA Ventures**.
