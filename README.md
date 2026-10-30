# FlixBus

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

FlixBus is the long-distance coach brand of Flix SE (formerly FlixMobility), a Munich-headquartered mobility provider that also operates FlixTrain in Europe and Greyhound in North America. Flix runs an asset-light model: it owns the brand, network planning, pricing, distribution and technology while regional bus partners operate the vehicles. Its technology surface is split in two. A partner-facing Flix API is published through the Flix Developer Portal at developer.api.flixbus.com — a Redocly-based catalogue of API references, getting-started guides, changelogs and downloadable Postman collections — but the portal is gated behind Microsoft Entra ID (Azure AD) sign-in and the underlying gateway at global.api.flixbus.com rejects anonymous requests, so no machine-readable OpenAPI is reachable without a distribution-partner agreement (requested via online-distribution@flixbus.com). Publicly and anonymously, Flix does publish schedule data as first-party GTFS Schedule feeds for Europe, the United States and Great Britain from gtfs.gis.flix.tech, refreshed regularly and licensed ODbL-1.0 through national open-data portals.

**Areas:** Company · Transportation · Travel · Mobility · Bus · Rail · Ticketing · GTFS · Open Data · Distribution

## FlixBus on APIs.io

Everything profiled for FlixBus is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/flixbus/](https://apis.io/providers/flixbus/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Flix API](https://apis.io/apis/flixbus/flix-api/) — The partner-facing Flix API, published through the Flix Developer Portal. Documentation covers API references, getting-started guides, changelogs and…
- [Flix GTFS Schedule Feeds](https://apis.io/apis/flixbus/flix-gtfs-schedule-feeds/) — First-party GTFS Schedule feeds published by FlixMobility Tech GmbH covering the FlixBus and FlixTrain networks. Three anonymous, unauthenticated regional…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Flixbus Authentication](https://apis.io/security/flixbus/flixbus-authentication/)
- [Flixbus Domain Security](https://apis.io/security/flixbus/flixbus-domain-security/)
- [Flixbus Vulnerability Disclosure](https://apis.io/security/flixbus/flixbus-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://global.flixbus.com/)
- [Documentation](https://developer.api.flixbus.com/)
- [Sign up](https://global.flixbus.com/company/partners/affiliate-partners)
- [Support](https://help.flixbus.com/)
- [Blog](https://corporate.flix.com/newsroom/)
- [Security](https://global.flixbus.com/responsible-disclosure)
- [Terms of service](https://global.flixbus.com/terms-and-conditions)
- [Privacy policy](https://global.flixbus.com/privacy-policy)
- [GitHub](https://github.com/flix-tech)

## API Evangelist rating

**Kin Score 23.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 13.2 |
| Developer ergonomics | 19.0 |
| Access clarity | 34.2 |

**Agent readiness 13.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/flixbus/](https://apis.io/providers/flixbus/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for FlixBus: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/flixbus/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
