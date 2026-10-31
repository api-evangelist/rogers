# Rogers Communications

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

Rogers Communications is Canada's largest wireless carrier and, following its 2023 acquisition of Shaw Communications, one of the country's largest cable, internet, and media companies. It operates a national 5G mobile network, broadband and TV services under the Rogers, Fido, chatr, and Shaw/Ignite brands, and owns Rogers Sports & Media. In the telecom API value chain Rogers sits squarely on the network-operator side, not the developer-facing side: it has no first-party developer portal, publishes no OpenAPI or Swagger definitions, runs no sandbox, and ships no first-party SDKs. Its legacy developer programme, Rogers Catalyst, is dead — www.rogers.com/developer still 301s to a meta-refresh page pointing at rogerscatalyst.com, a domain that no longer belongs to Rogers (re-registered through NameCheap with registrant privacy in December 2023) and that now serves a one-byte blank page. Rogers' network capabilities reach developers only through intermediaries: EnStream LP, the identity and fraud joint venture it co-owns with Bell Mobility and TELUS, which resells Canadian carrier Number Verification and SIM Swap data on a sales-led, contract-first basis with no public documentation; Aduna, the Ericsson-and-carrier joint venture that announced an EnStream partnership in February 2025 to bring Bell, Rogers, and TELUS network APIs onto a CAMARA-aligned platform; and, historically, a Canada-exclusive private preview of Microsoft's Azure Programmable Connectivity announced at MWC 2023, whose public documentation has since been retired. On 2026-06-30 Vonage commercially launched SIM Swap Detection and Silent Authentication across Canada, connecting to Bell, Rogers and TELUS via Aduna's integration with EnStream — the first documented, self-serve way to buy Rogers-derived network signals, though the contract, docs and sandbox all belong to Vonage. Rogers is partner-gated and reachable only through aggregators — the CAMARA posture is real but wholesale, and nothing is callable from a Rogers-owned domain.

**Areas:** Telecommunications · Canada · Mobile Network Operator · Broadband · 5G · Network APIs · CAMARA · Identity Verification · SIM Swap · IoT · Media

## Rogers Communications on APIs.io

Everything profiled for Rogers Communications is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rogers/](https://apis.io/providers/rogers/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Rogers Control Centre IoT APIs](https://apis.io/apis/rogers/rogers-control-centre-iot-api/) — Rogers Control Centre is Rogers' managed IoT and M2M connectivity management platform, a white-labelled deployment of Cisco IoT Control Center (formerly…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Rogers Push Api Webhooks](https://apis.io/asyncapis/rogers/rogers-push-api-webhooks/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Rogers Authentication](https://apis.io/security/rogers/rogers-authentication/)
- [Rogers Domain Security](https://apis.io/security/rogers/rogers-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Rogers Plans](https://apis.io/plans/rogers/rogers-plans/)

#### Rate limits (1)

Published request limits.

- [Rogers Rate Limits](https://apis.io/rate-limits/rogers/rogers-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.rogers.com/)
- [Documentation](https://www.rogers.com/business/iot)
- [Pricing](https://www.rogers.com/business/wireless/plans)
- [Support](https://www.rogers.com/support)
- [Blog](https://www.rogers.com/business/blog)
- [Terms of service](https://www.rogers.com/support/terms/rogers-terms-of-service-acceptable-use-policy-and-privacy-policy)
- [Privacy policy](https://www.rogers.com/support/privacy/rogers-privacy-policy)
- [Status](https://www.rogers.com/support/outage)

## API Evangelist rating

**Kin Score 50.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 74.1 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 47.4 |
| Developer ergonomics | 51.2 |
| Access clarity | 69.7 |

**Agent readiness 25.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 25.8** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rogers/](https://apis.io/providers/rogers/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rogers Communications: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rogers/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
