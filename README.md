# UCLouvain

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

UCLouvain (Universite catholique de Louvain) is Belgium's largest French-speaking university -- a private institution subsidised by public authorities, Catholic in identity, based in Louvain-la-Neuve with campuses in Brussels, Mons, Tournai, Charleroi and Namur, and ranked #203 in the QS World University Rankings 2025. Its programmable footprint is small, real, and mostly NOT its own engineering. UCLouvain operates no public developer portal, issues no API keys, and api.uclouvain.be answers 503 with no backend behind it. What it does operate, verified live on 2026-08-30: the Orthanc medical-imaging ecosystem -- a genuinely UCLouvain-authored open-source project run out of ICTEAM's Health Informatics Lab, publishing a 239-path OpenAPI 3.0 contract and a public demo server; four OAI-PMH 2.0 repositories (Dataverse open data, DIAL.pr research publications, DIAL.mem master's theses, OER-UCLouvain open educational resources); a SAML 2.0 / Shibboleth identity provider registered with the Belnet federation and exported to eduGAIN; and Crossref membership in its own right, minting DOIs under prefix 10.14428. Everything else that looks like a UCLouvain API is a product's contract running on a UCLouvain host: the Dataverse 6.8 Native API and the DSpace-CRIS 8.1 REST API behind DIAL are recorded here as tenant deployments, not as UCLouvain's contracts. An earlier profile of this repository credited UCLouvain with 36 OpenAPI definitions that were in fact one Dataverse product spec split by tag -- a contract eight institutions in this catalog ship identically. Those have been removed.

**Areas:** University · Higher Education · Education · Belgium · Private Research University · Open Data · Research Data · Open Science · Institutional Repository · OAI-PMH · Identity Federation · Open Source

## UCLouvain on APIs.io

Everything profiled for UCLouvain is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/uclouvain/](https://apis.io/providers/uclouvain/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [Open Data @ UCLouvain -- Dataverse deployment (Native + Search API)](https://apis.io/apis/uclouvain/dataverse-native-api/) — Open Data @ UCLouvain is the institution's research-data repository, running Dataverse 6.8 on UCLouvain infrastructure at dataverse.uclouvain.be and minting…
- [Open Data @ UCLouvain Dataverse OAI-PMH](https://apis.io/apis/uclouvain/dataverse-oai/) — OAI-PMH 2.0 metadata-harvesting endpoint for the UCLouvain research-data repository. Identify returns repositoryName "Open Data @ UCLouvain Dataverse OAI…
- [DIAL.pr (BOREAL) -- DSpace-CRIS REST API](https://apis.io/apis/uclouvain/dial-pr-rest/) — DIAL.pr, branded BOREAL, is UCLouvain's institutional repository for the research publications of its professors and staff. It runs DSpace-CRIS 8.1…
- [DIAL.pr OAI-PMH](https://apis.io/apis/uclouvain/dial-pr-oai/) — OAI-PMH 2.0 harvesting endpoint for DIAL.pr, UCLouvain's research-publications repository. Identify returns repositoryName "Dial.pr", adminEmail…
- [DIAL.mem -- DSpace-CRIS REST API](https://apis.io/apis/uclouvain/dial-mem-rest/) — DIAL.mem is UCLouvain's institutional repository for master's theses, part of the DIAL (Digital Access to Libraries) family. It runs the same DSpace-CRIS…
- [DIAL.mem OAI-PMH](https://apis.io/apis/uclouvain/dial-mem-oai/) — OAI-PMH 2.0 harvesting endpoint for DIAL.mem, UCLouvain's master's-thesis repository. Identify returns repositoryName "Dial.mem", adminEmail…
- [OER-UCLouvain OAI-PMH](https://apis.io/apis/uclouvain/oer-oai/) — OER-UCLouvain is the institution's open educational resources repository, running DSpace JSPUI on oer.uclouvain.be (CNAME dspace.sipr.ucl.ac.be, UCLouvain's…
- [UCLouvain Shibboleth Identity Provider -- SAML 2.0 metadata](https://apis.io/apis/uclouvain/identity-federation/) — UCLouvain runs its own Shibboleth identity provider and publishes signed SAML 2.0 entity metadata at a stable, unauthenticated URL. entityID…
- [UCLouvain Instances API](https://apis.io/apis/uclouvain/uclouvain-instances-api/) — The Instances API from UCLouvain — 51 operation(s) for instances.
- [UCLouvain Jobs API](https://apis.io/apis/uclouvain/uclouvain-jobs-api/) — The Jobs API from UCLouvain — 7 operation(s) for jobs.
- [UCLouvain Logs API](https://apis.io/apis/uclouvain/uclouvain-logs-api/) — The Logs API from UCLouvain — 8 operation(s) for logs.
- [UCLouvain Networking API](https://apis.io/apis/uclouvain/uclouvain-networking-api/) — The Networking API from UCLouvain — 37 operation(s) for networking.
- [UCLouvain Other API](https://apis.io/apis/uclouvain/uclouvain-other-api/) — The Other API from UCLouvain — 6 operation(s) for other.
- [UCLouvain Patients API](https://apis.io/apis/uclouvain/uclouvain-patients-api/) — The Patients API from UCLouvain — 32 operation(s) for patients.
- [UCLouvain Series API](https://apis.io/apis/uclouvain/uclouvain-series-api/) — The Series API from UCLouvain — 33 operation(s) for series.
- [UCLouvain Studies API](https://apis.io/apis/uclouvain/uclouvain-studies-api/) — The Studies API from UCLouvain — 34 operation(s) for studies.
- [UCLouvain System API](https://apis.io/apis/uclouvain/uclouvain-system-api/) — The System API from UCLouvain — 33 operation(s) for system.
- [UCLouvain Tracking changes API](https://apis.io/apis/uclouvain/uclouvain-tracking-changes-api/) — The Tracking changes API from UCLouvain — 2 operation(s) for tracking changes.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [UCLouvain Open Data and Repository Vocabulary](https://apis.io/vocabularies/uclouvain/uclouvain-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Uclouvain Orthanc System Example](https://apis.io/examples/uclouvain/uclouvain-orthanc-system-example/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Uclouvain Domain Security](https://apis.io/security/uclouvain/uclouvain-domain-security/)
- [Uclouvain Vulnerability Disclosure](https://apis.io/security/uclouvain/uclouvain-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Uclouvain Plans Pricing](https://apis.io/plans/uclouvain/uclouvain-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Uclouvain Rate Limits](https://apis.io/rate-limits/uclouvain/uclouvain-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Uclouvain Finops](https://apis.io/finops/uclouvain/uclouvain-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://uclouvain.be/en)
- [Documentation](https://orthanc.uclouvain.be/book/)
- [API reference](https://orthanc.uclouvain.be/api/index.html)
- [Privacy policy](https://uclouvain.be/en/privacy)
- [GitHub](https://github.com/uclouvain)

## API Evangelist rating

**Kin Score 27.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 43.5 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 15.8 |

**Agent readiness 22.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/uclouvain/](https://apis.io/providers/uclouvain/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for UCLouvain: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/uclouvain/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
