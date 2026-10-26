# UCLouvain (uclouvain)

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

UCLouvain (Universite catholique de Louvain) is Belgium's largest French-speaking university -- a private institution subsidised by public authorities, based in Louvain-la-Neuve, ranked #203 in the QS World University Rankings 2025. This repository catalogs the institution's public, machine-readable footprint as an [APIs.json](https://apisjson.org) profile.

UCLouvain operates **no public developer portal and issues no API keys**; `api.uclouvain.be` resolves but answers 503 with no backend. What it does operate, verified live on 2026-08-30, is the Orthanc medical-imaging API (its own open-source project), four OAI-PMH 2.0 repositories, and a SAML 2.0 / Shibboleth identity provider federated through Belnet into eduGAIN.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/uclouvain/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=uclouvain-api-evangelist&utm_content=repo

## Type

Index / Consumer / Public — `x-type: university`, `x-category: Private Research University`

## Tags

University, Higher Education, Education, Belgium, Private Research University, Open Data, Research Data, Open Science, Institutional Repository, OAI-PMH, Identity Federation, Open Source, Medical Imaging, Library

## Who operates what

Every surface below carries an `x-operator` in `apis.yml`. A university is a federation of buyers, and most of what looks like an institutional API is a product's contract running on an institutional host.

### Institution-operated

- **Orthanc API** — `institution`. Free and open-source vendor-neutral DICOM server, authored and maintained by UCLouvain's Health Informatics Lab (ICTEAM) and hosted by INGI. 239 paths / 299 operations, OpenAPI 3.0. Contract: [openapi/uclouvain-orthanc-api-openapi.yml](openapi/uclouvain-orthanc-api-openapi.yml) — base: `https://orthanc.uclouvain.be/demo/`
- **UCLouvain Shibboleth Identity Provider** — `institution`. SAML 2.0 entity metadata, scope `uclouvain.be`, registered with the Belnet federation since 2012 and exported to eduGAIN, SIRTFI asserted. See [authentication/uclouvain-identity-federation.yml](authentication/uclouvain-identity-federation.yml) — base: `https://idp.uclouvain.be/idp/shibboleth`
- **Open Data @ UCLouvain Dataverse OAI-PMH** — `institution` — base: `https://dataverse.uclouvain.be/oai`
- **DIAL.pr OAI-PMH** — `institution` — base: `https://research.dial.uclouvain.be/server/oai/request`
- **DIAL.mem OAI-PMH** — `institution` — base: `https://thesis.dial.uclouvain.be/server/oai/request`
- **OER-UCLouvain OAI-PMH** — `institution` — base: `https://oer.uclouvain.be/oai/request`

### Tenant deployments (institution's data, vendor's contract)

- **Open Data @ UCLouvain Dataverse Native + Search API** — `tenant`. Dataverse 6.8 on UCLouvain infrastructure — base: `https://dataverse.uclouvain.be/api`
- **DIAL.pr (BOREAL) DSpace-CRIS REST API** — `tenant`. DSpace-CRIS 8.1 — base: `https://research.dial.uclouvain.be/server/api`
- **DIAL.mem DSpace-CRIS REST API** — `tenant`. DSpace-CRIS 8.1 — base: `https://thesis.dial.uclouvain.be/server/api`

## Domain standards (Kin Score `education` regime)

Confirmed live, with evidence in [conformance/uclouvain-education-standards.yml](conformance/uclouvain-education-standards.yml): **oai-pmh**, **shibboleth**, **saml**, **orcid**, **crossref** (UCLouvain is Crossref member 5552, prefix 10.14428, 4,408 works). Explicitly negative: **datacite** — the prefix is a Crossref prefix, and the DataCite REST API holds no record of it. Not found: lti, scim, oneroster, ed-fi, caliper, qti.

## Plans / Rate Limits / FinOps

[plans/uclouvain-plans-pricing.yml](plans/uclouvain-plans-pricing.yml) · [rate-limits/uclouvain-rate-limits.yml](rate-limits/uclouvain-rate-limits.yml) · [finops/uclouvain-finops.yml](finops/uclouvain-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://uclouvain.be/en
- GitHub Organization: https://github.com/uclouvain
- Open Data: https://dataverse.uclouvain.be/
- Research Repository: https://research.dial.uclouvain.be/home
- Identity Federation: https://idp.uclouvain.be/idp/shibboleth
- Research Computing: https://uclouvain.be/en/cism/cism-platform
- Course Catalog: https://uclouvain.be/en/study-programme
- AI Policy: https://uclouvain.be/en/ai/documents
- AI Tooling: https://uclouvain.be/en/ai
- Privacy: https://uclouvain.be/en/privacy
- LinkedIn: https://be.linkedin.com/school/uclouvain/

## Attribution correction, 2026-08-30

This repository previously credited UCLouvain with **36 OpenAPI definitions**. They were one document: the Dataverse project's own product contract (`info.title: Dataverse API`, `description: Open source research data repository software.`), fetched, re-based onto `dataverse.uclouvain.be` and split by tag. Eight institutions in this catalog ship the same contract. All 36, their pristine source, and everything derived from them — 72 Postman/OpenCollection files, the Dataverse-shaped JSON Schema and JSON Structure, the JSON-LD context, the vocabulary, both Spectral rulesets, a 541-operation agentic-access classification and one recorded Dataverse search example — have been removed. The **deployment** is kept, correctly labelled `x-operator: tenant`.

Two pointers were confirmed dead and removed: `https://dial.uclouvain.be/oai` (the host is TCP-unreachable on 80 and 443; DIAL has migrated to DSpace-CRIS) and `https://github.com/uclouvain/osis` (404 — the `uclouvain` GitHub org now holds four public repositories, and OSIS is not among them).

This correction **lowers** the repository's artifact count and very likely its Kin Score. That is the pipeline working: the previous number measured Dataverse's engineering, not UCLouvain's.

## Maintainers

- Kin Lane — kin@apievangelist.com
