# Rogers Communications (rogers)

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

Rogers Communications is Canada's largest wireless carrier and, following its 2023 acquisition of Shaw Communications, one of the country's largest cable, internet, and media companies. It operates a national 5G mobile network, broadband and TV services under the Rogers, Fido, chatr, and Shaw/Ignite brands, and owns Rogers Sports & Media. In the telecom API value chain Rogers sits on the network-operator side, not the developer-facing side: no first-party developer portal, no published OpenAPI or Swagger, no sandbox, and no first-party SDKs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rogers/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rogers/refs/heads/main/apis.yml)

## Tags

- Telecommunications
- Canada
- Mobile Network Operator
- Broadband
- 5G
- Network APIs
- CAMARA
- Identity Verification
- SIM Swap
- IoT
- Media

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

### Rogers Control Centre IoT APIs

Rogers' managed IoT and M2M connectivity management platform, a white-labelled deployment of Cisco IoT Control Center (formerly Jasper). Rogers' own product content lists "Access to applicable REST APIs" and "Access to applicable REST and SOAP APIs" as tier features, so the surface is real and named by Rogers — but Rogers documents no endpoints itself. The REST, SOAP, and PUSH API functions are documented by Cisco on Cisco DevNet, and a live tenant requires a Rogers Business contract plus platform credentials. Authentication is an API key for REST, a license key for SOAP, and a shared secret used to validate inbound PUSH callbacks. Customer-gated; no self-serve signup.

- **Human URL:** [https://www.rogers.com/business/iot/control-centre](https://www.rogers.com/business/iot/control-centre)

#### Tags

- IoT
- M2M
- Connectivity Management
- SIM Lifecycle
- Canada

#### Properties

- [Documentation](https://www.rogers.com/business/iot/control-centre)
- [Documentation](https://www.rogers.com/business/blog/en/optimize-and-scale-your-iot-solutions-with-rogers-control-centre)
- [API Reference](https://developer.cisco.com/docs/control-center/rest-api-functions/)

## The Developer Programme That Is Not There

`https://www.rogers.com/developer` returns **301** to `/developer/`, which returns **200** and serves a bare HTML meta-refresh to `http://www.rogerscatalyst.com`. That host does not resolve. The apex, `rogerscatalyst.com`, resolves to a Hetzner IP in Germany and returns 200 with a **one-byte body**; WHOIS shows it was created 2023-12-12 through NameCheap behind registrant privacy. The legacy Rogers Catalyst developer programme is gone and Rogers' own website still points at a domain it no longer controls.

`developer.rogers.com`, `developers.rogers.com`, `docs.rogers.com`, `apis.rogers.com`, `opengateway.rogers.com`, `developers.opengateway.rogers.com`, and `developer.rogers.ca` all fail DNS resolution. `api.rogers.com` resolves and returns 200, but serves the consumer marketing SPA — its canonical is `http://www.rogers.com/consumer/home`. `www.rogers.com/api` and `www.rogers.com/opengateway` both 404.

## CAMARA and GSMA Open Gateway Posture

**Real but wholesale and indirect.** Nothing CAMARA is callable, documented, or even named on any Rogers-owned domain.

- **CAMARA APIs with evidence:** Number Verification, SIM Swap — both named in the [Ericsson/Aduna press release of 2025-02-27](https://www.ericsson.com/en/press-releases/2025/2/aduna-and-enstream-partner-to-unlock-canadas-telecom-network-apis-for-global-innovation) announcing the Aduna–EnStream partnership, which states the collaboration "will enable seamless access to telecom network APIs from Bell, Rogers, and TELUS."
- **Channel:** [EnStream LP](https://enstream.com/), the identity and fraud joint venture Rogers co-owns with Bell Mobility and TELUS. EnStream markets Verify / Authenticate / Protect, names its three carrier owners, and mentions neither CAMARA nor Open Gateway. `enstream.com/developers`, `/api`, and `/docs` all 404; `developer.enstream.com` and `docs.enstream.com` do not resolve. Sales-led, contract-first, no public documentation.
- **A press release is not an implementation.** The Ericsson release is forward-looking — EnStream's APIs "will be integrated into Aduna's platform." As of this review, Aduna's own operator page lists Airtel, AT&T, Deutsche Telekom, KDDI, Orange, Reliance Jio, Singtel, T-Mobile, Telefónica, Telstra, Verizon, and Vodafone, and does **not** name Canada, Rogers, Bell, TELUS, or EnStream.
- **GSMA Open Gateway:** unconfirmed. Rogers publishes no Open Gateway page, and the GSMA supporter roster returns 403 to anonymous fetches, so membership could be neither confirmed nor disproved.
- **Microsoft Azure Programmable Connectivity:** Rogers announced a Canada-exclusive private preview at MWC on 2023-02-28 — "select Canadian developers will gain secure access to a location-based API on Rogers' national 5G network." CAMARA is not named in the Rogers announcement, and Microsoft's APC documentation has since been retired (the docs URLs 301 away to a marketing page).

## Other Findings

- **Auth:** no first-party auth surface. `/.well-known/openid-configuration` and `/.well-known/oauth-authorization-server` return 404 on both `www.rogers.com` and `api.rogers.com`. **CIBA does not appear anywhere on a Rogers property.**
- **Specs:** none. Every `/openapi.json`, `/openapi.yaml`, `/swagger.json`, `/api-docs`, `/spec`, and `/v1/openapi.json` path probed returned 404. No `openapi/` directory is included in this repository.
- **GraphQL / gRPC:** none. `/graphql` returns 404 on both hosts; no published `.proto` files.
- **SDKs:** no first-party packages on npm, PyPI, Maven, or NuGet. npm `rogers` is an unrelated Marvel API wrapper; PyPI `rogers-api` is described by its own author as an "Unofficial Python wrapper for Rogers Bank credit card data."
- **GitHub:** no verifiable Rogers organization. `Rogers-Communications` and `RogersCommunications` both exist with zero public repositories and no metadata; neither is claimed here.
- **Postman:** no public workspace found.
- **TM Forum:** no Open API conformance certification found in Rogers' name. Broadcom publishes a Rogers case study on internal API management, but that is BSS/OSS estate, not a published or certified Open API surface.
- **3GPP exposure:** no NEF or SCEF surface, no network-slicing API, no edge/MEC API.

## Links

- [Rogers Communications](https://www.rogers.com/)
- [About Rogers](https://about.rogers.com/)
- [Rogers Business IoT](https://www.rogers.com/business/iot)
- [LinkedIn](https://www.linkedin.com/company/rogers-communications)

## Maintainers

- Kin Lane — kin@apievangelist.com
