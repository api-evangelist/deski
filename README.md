# DESKi

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

DESKi is a French medical-device software company founded in 2016 in Bordeaux by brothers Bertrand and Olivier Moal, trading publicly under its HeartFocus brand. Its flagship product, HeartFocus, is an FDA-cleared AI cardiac imaging app that runs on iPhone and iPad with Butterfly Network iQ+ and iQ3 handheld ultrasound probes, giving any healthcare professional real-time probe guidance, automatic diagnostic-quality clip recording and live view validation across the 10 standard transthoracic echocardiographic views (PLAX, PSAX-AV, PSAX-MV, PSAX-PM, A4C, A5C, A2C, A3C, SC-4C, SC-IVC). A second product, HeartFocus Link, adds the same AI guidance to existing cart-based ultrasound systems from GE HealthCare, Philips, Siemens Healthineers, Mindray, FUJIFILM Sonosite, Samsung and Canon over a plain HDMI capture path, for education and training only. DESKi holds two FDA 510(k) clearances (K242807, 2025-04-04; K260780, 2026-06-03, product code QJU) and publishes a Coordinated Vulnerability Disclosure process, a HIPAA & HBNR applicability statement, per-probe list pricing and dated electronic instructions for use. Its only machine-facing integration surface is DICOM: exams are transferred from the mobile app to a customer-configured PACS server (server and client AE titles, host, port, optional TLS), and the DICOM conformance statement and CycloneDX SBOM are available only by emailing support. DESKi publishes no public REST or GraphQL API, no OpenAPI or AsyncAPI specification, no SDK, no CLI, no MCP server and no developer portal; portal.heartfocus.ai is a customer licence-management application, not a developer surface.

**Areas:** Company · Health Tech · Medical Imaging · Cardiology · Ultrasound · Point-of-Care Ultrasound · Artificial Intelligence · Medical Devices · DICOM · France

## DESKi on APIs.io

Everything profiled for DESKi is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/deski/](https://apis.io/providers/deski/)** — or go straight to one of the APIs or properties below.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Deski Domain Security](https://apis.io/security/deski/deski-domain-security/)
- [Deski Vulnerability Disclosure](https://apis.io/security/deski/deski-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Deski Plans Pricing](https://apis.io/plans/deski/deski-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Deski Rate Limits](https://apis.io/rate-limits/deski/deski-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.heartfocus.ai/)
- [Documentation](https://www.heartfocus.ai/user-manuals)
- [Pricing](https://www.heartfocus.ai/pricing)
- [Sign up](https://portal.heartfocus.ai/signup)
- [Support](https://www.heartfocus.ai/contact-us)
- [Blog](https://www.heartfocus.ai/news)
- [Security](https://www.heartfocus.ai/security/cvd)
- [Compliance](https://www.heartfocus.ai/hipaa-hbnr-applicability-statement)
- [Terms of service](https://www.heartfocus.ai/heartfocus-software-license-agreement)
- [Privacy policy](https://www.heartfocus.ai/privacy-policy)

## API Evangelist rating

**Kin Score 29.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 55.4 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 10.5 |
| Developer ergonomics | 16.7 |
| Access clarity | 77.6 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 22.1** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/deski/](https://apis.io/providers/deski/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for DESKi: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/deski/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
