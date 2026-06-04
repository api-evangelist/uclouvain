# UCLouvain (uclouvain)

UCLouvain (Universite catholique de Louvain) is Belgium's largest French-speaking university, based in Louvain-la-Neuve, and is ranked #203 in the QS World University Rankings 2025. This repository catalogs the institution's public, machine-readable developer/API footprint as an [APIs.json](https://apisjson.org) profile. UCLouvain's footprint is concentrated in open science and library infrastructure — an institutional Dataverse open-data repository and the DIAL institutional repository — plus a public GitHub organization and the open-source OSIS project.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/uclouvain/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=uclouvain-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Open Science, Research Data, Library, OAI-PMH, Belgium

## APIs

- **Open Data @ UCLouvain Dataverse API** — Dataverse (v6.8) Native and Search API for datasets, files, and metadata. Docs: https://guides.dataverse.org/en/latest/api/ — base: `https://dataverse.uclouvain.be/api`
- **Open Data @ UCLouvain Dataverse OAI-PMH** — OAI-PMH 2.0 metadata harvesting. Docs: https://guides.dataverse.org/en/latest/api/oai.html — base: `https://dataverse.uclouvain.be/oai`
- **DIAL UCLouvain OAI-PMH** — OAI-PMH 2.0 harvesting for the DIAL institutional publications repository. Docs: https://www.openarchives.org/OAI/openarchivesprotocol.html — base: `https://dial.uclouvain.be/oai`
- **OSIS - Open Student Information System** — Open-source Django higher-education management platform originated by UCLouvain. Docs/Source: https://github.com/uclouvain/osis

## Plans

[plans/uclouvain-plans-pricing.yml](plans/uclouvain-plans-pricing.yml)

## Rate Limits

[rate-limits/uclouvain-rate-limits.yml](rate-limits/uclouvain-rate-limits.yml)

## FinOps

[finops/uclouvain-finops.yml](finops/uclouvain-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://uclouvain.be/en/index.html
- GitHub: https://github.com/uclouvain
- LinkedIn: https://be.linkedin.com/school/uclouvain/
- Plans: plans/uclouvain-plans-pricing.yml
- Rate Limits: rate-limits/uclouvain-rate-limits.yml
- FinOps: finops/uclouvain-finops.yml
- Review: review.yml

## Notes

All cataloged APIs were probed live on 2026-06-03. The Dataverse Search/version APIs and both OAI-PMH endpoints (Dataverse and DIAL) returned valid responses. UCLouvain does not appear to operate a single unified, key-issuing developer portal; the APIs here are standards-based open-data, library-harvesting, and open-source-project interfaces. The `uclouvain` GitHub organization is official. No published rate limits or pricing were found; the Plans/Rate Limits/FinOps files capture the open/free posture. Nothing was fabricated — only confirmed properties are listed.

## Maintainers

- Kin Lane — kin@apievangelist.com
