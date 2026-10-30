# Newcastle University

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

Newcastle University is a public research university in Newcastle upon Tyne, United Kingdom, and a member of the Russell Group. Its programmable footprint is genuinely its own but it is small, decentralised and unadvertised: there is no central developer portal, no API changelog, no status page and no developer support channel anywhere on ncl.ac.uk. What the institution actually operates and runs itself, verified live on 2026-08-30, is four things — the Urban Observatory API for the Urban Sciences Building (the largest open urban-sensing platform in the UK, on a domain Newcastle registered and serves from its own nameservers), the Library's Digitised Objects Repository Search and Data API, which publishes its own OpenAPI at /info/open-api and serves 15,482 digitised objects from Special Collections, the ECPPEC eighteenth-century electoral GraphQL API with open introspection, and an OAI-PMH 2.0 endpoint over the eTheses repository. Alongside these it operates a Shibboleth SAML 2.0 identity provider registered in the UK Access Management Federation with 168 service providers under ncl.ac.uk, which is by volume the institution's largest machine-readable surface and is a login federation rather than a data API. Its research data repository, data.ncl, is a Figshare tenant: the data and the DOIs are Newcastle's, the API contract is Figshare's, and it is recorded here as a tenant relationship rather than credited to the university.

**Areas:** University · Higher Education · Education · United Kingdom · Russell Group · Research Data · Open Data · Digital Library · Identity Federation · Smart Cities · Cultural Heritage

## Newcastle University on APIs.io

Everything profiled for Newcastle University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/newcastle/](https://apis.io/providers/newcastle/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Digitised Objects Repository Search and Data API](https://apis.io/apis/newcastle/digitised-objects/) — A single point-of-truth interface for searching, browsing and displaying the digitised objects held in Newcastle University Library's Special Collections.…
- [ECPPEC Electoral Data GraphQL API](https://apis.io/apis/newcastle/ecppec/) — A GraphQL API over the Eighteenth-Century Political Participation and Electoral Culture research dataset — historical British elections, constituencies,…
- [Newcastle University eTheses OAI-PMH Endpoint](https://apis.io/apis/newcastle/etheses-oai/) — An OAI-PMH 2.0 metadata harvesting interface over Newcastle University's electronic theses repository, running on DSpace 6.3. Supports oai_dc, dim and the…
- [data.ncl Research Data Repository (Figshare tenancy)](https://apis.io/apis/newcastle/data-ncl/) — Newcastle University's institutional research data repository, operated for the university by Figshare on a Newcastle-branded custom domain. Programmatic…
- [Urban Observatory API (Urban Sciences Building) — Entity](https://apis.io/apis/newcastle/urban-observatory-entity/) — An entity ordinarily describes a spatial location, such as a room in a building or a pole in the street. In some circumstances an entity may be a mobile…
- [Urban Observatory API (Urban Sciences Building) — Feed](https://apis.io/apis/newcastle/urban-observatory-feed/) — A feed is a representation of a measurement or parametrisation, usually a metric, for example the observed temperature.
- [Urban Observatory API (Urban Sciences Building) — Summary](https://apis.io/apis/newcastle/urban-observatory-summary/) — A compact summary view over Urban Sciences Building entities and the feeds attached to them.
- [Newcastle University API Metadata Information API](https://apis.io/apis/newcastle/newcastle-api-metadata-information-api/) — A set of endpoints for gathering information about the API itself. They can be used for validation, creating types or checking if the service is live.
- [Newcastle University Collections API](https://apis.io/apis/newcastle/newcastle-collections-api/) — A set of endpoints describing the collections present in the repository.
- [Newcastle University CONTEN Tdm API](https://apis.io/apis/newcastle/newcastle-contentdm-api/) — A set of endpoints used for describing digitised objects stored in the repository, as well as all the complementary resources created based on them.
- [Newcastle University Items API](https://apis.io/apis/newcastle/newcastle-items-api/) — A set of endpoints describing the integrants of the given digitised object present in the repository.
- [Newcastle University TEI API](https://apis.io/apis/newcastle/newcastle-tei-api/) — A set of endpoints providing metadata and content definitions of documents encoded using [Text Encoding Initiative](https://tei-c.org/) guidance.
- [Newcastle University Time Series API](https://apis.io/apis/newcastle/newcastle-time-series-api/) — There may be more than one timeseries associated with a feed, provided for convenience. Ordinarily there will be a plain timeseries, representing raw data…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Newcastle Agentic Access](https://apis.io/agentic-access/newcastle/newcastle-agentic-access/)

#### JSON Schema (10)

The data models the API reads and writes.

- [DigitisedObject](https://apis.io/schemas/newcastle/newcastle-digitised-object/)
- [Collection](https://apis.io/schemas/newcastle/newcastle-dor-collection/)
- [DorError](https://apis.io/schemas/newcastle/newcastle-dor-error/)
- [DorPagination](https://apis.io/schemas/newcastle/newcastle-dor-pagination/)
- [Entity](https://apis.io/schemas/newcastle/newcastle-entity/)
- [EntitySummary](https://apis.io/schemas/newcastle/newcastle-entitysummary/)
- [Feed](https://apis.io/schemas/newcastle/newcastle-feed/)
- [HateoasLinks](https://apis.io/schemas/newcastle/newcastle-hateoas-links/)
- [Timeseries](https://apis.io/schemas/newcastle/newcastle-timeseries/)
- [TimeseriesEntry](https://apis.io/schemas/newcastle/newcastle-timeseriesentry/)

#### JSON Structure (4)

Data models expressed in JSON Structure.

- [Newcastle Entity Structure](https://apis.io/json-structure/newcastle/newcastle-entity-structure/)
- [Newcastle Feed Structure](https://apis.io/json-structure/newcastle/newcastle-feed-structure/)
- [Newcastle Timeseries Structure](https://apis.io/json-structure/newcastle/newcastle-timeseries-structure/)
- [Newcastle Timeseriesentry Structure](https://apis.io/json-structure/newcastle/newcastle-timeseriesentry-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Newcastle Context](https://apis.io/jsonld/newcastle/newcastle-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Newcastle Urban Observatory Vocabulary](https://apis.io/vocabularies/newcastle/newcastle-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Newcastle Digitised Objects Collections Example](https://apis.io/examples/newcastle/newcastle-digitised-objects-collections-example/)
- [Newcastle Digitised Objects List Example](https://apis.io/examples/newcastle/newcastle-digitised-objects-list-example/)
- [Newcastle Ecppec Graphql Example](https://apis.io/examples/newcastle/newcastle-ecppec-graphql-example/)
- [Newcastle Entity List Example](https://apis.io/examples/newcastle/newcastle-entity-list-example/)
- [Newcastle Timeseries Entry Example](https://apis.io/examples/newcastle/newcastle-timeseries-entry-example/)

#### Collections (4)

Postman and Open Collection request collections.

- [Urban Observatory API: Urban Sciences Building Entity API](https://apis.io/collections/newcastle/open-newcastle-entity-api/)
- [Urban Observatory API: Urban Sciences Building Entity Feed API](https://apis.io/collections/newcastle/open-newcastle-feed-api/)
- [Urban Observatory API: Urban Sciences Building Entity Summary API](https://apis.io/collections/newcastle/open-newcastle-summary-api/)
- [Urban Observatory API: Urban Sciences Building Entity Timeseries API](https://apis.io/collections/newcastle/open-newcastle-timeseries-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Newcastle University — jsonschema rules](https://apis.io/rules/newcastle/newcastle-jsonschema-spectral-rules/)
- [Newcastle University API Rules](https://apis.io/rules/newcastle/newcastle-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Newcastle Authentication](https://apis.io/security/newcastle/newcastle-authentication/)
- [Newcastle Domain Security](https://apis.io/security/newcastle/newcastle-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Newcastle Scopes](https://apis.io/scopes/newcastle/newcastle-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Newcastle Plans Pricing](https://apis.io/plans/newcastle/newcastle-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Newcastle Rate Limits](https://apis.io/rate-limits/newcastle/newcastle-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Newcastle Finops](https://apis.io/finops/newcastle/newcastle-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ncl.ac.uk/)
- [Blog](https://belong.ncl.ac.uk/blog)
- [GitHub](https://github.com/newcastleuniversity)

## API Evangelist rating

**Kin Score 30.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 54.0 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 31.0 |
| Access clarity | 5.3 |

**Agent readiness 33.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/newcastle/](https://apis.io/providers/newcastle/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Newcastle University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/newcastle/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
