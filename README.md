# Universität Hamburg (universitat-hamburg)

Universität Hamburg is a public research university in Hamburg, Germany, ranked #191 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer footprint as an APIs.json profile for the API Evangelist network. That footprint is concentrated in library and open-access infrastructure operated by the Staats- und Universitätsbibliothek (SUB) and the Regionales Rechenzentrum (RRZ), rather than a single branded developer portal.

APIs.json: https://raw.githubusercontent.com/api-evangelist/universitat-hamburg/refs/heads/main/apis.yml

Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=universitat-hamburg-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Germany, Open Access, Library, Metadata, OAI-PMH

## APIs

- **E-Dissertationen (ediss.sub.hamburg) OAI-PMH** — OAI-PMH 2.0 metadata-harvesting endpoint for the DSpace institutional repository of electronic dissertations/habilitations. Verified live.
  - Docs: https://www.sub.uni-hamburg.de/service/publizieren/dissertationen/e-dissertationen-der-uhh.html
  - Base URL: https://ediss.sub.uni-hamburg.de/oai/request
- **Open-Access-Portal Universität Hamburg** — Discovery portal for open-access publications, research data, and collections; harvestable metadata infrastructure via RRZ, no single documented public REST API.
  - Docs: https://www.openaccess.uni-hamburg.de/en.html

## Plans

- [plans/universitat-hamburg-plans-pricing.yml](plans/universitat-hamburg-plans-pricing.yml)

## Rate Limits

- [rate-limits/universitat-hamburg-rate-limits.yml](rate-limits/universitat-hamburg-rate-limits.yml)

## FinOps

- [finops/universitat-hamburg-finops.yml](finops/universitat-hamburg-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uni-hamburg.de/en.html
- GitHub: https://github.com/Uni-Hamburg
- LinkedIn: https://www.linkedin.com/school/universitaet-hamburg/
- SourceCode (GitLab): https://gitlab.rrz.uni-hamburg.de/
- Authentication (Shibboleth/SAML SSO): https://www.rrz.uni-hamburg.de/services/weitere/authentifizierung/shibboleth/configure.html

## Notes

- No fabricated endpoints or properties. Only URLs probed live or confirmed via authoritative sources were cataloged.
- The ediss OAI-PMH endpoint was verified live (HTTP 200, valid OAI-PMH 2.0 Identify response, DSpace XOAI).
- STiNE (CampusNet campus-management) and Shibboleth/SAML SSO exist but are gated and not published as public, documented APIs.
- Universität Hamburg maintains an official GitHub organization (Uni-Hamburg, 3 public repos) and an RRZ-hosted GitLab instance (access gated).
- The LinkedIn school page returns HTTP 999 to automated probes (LinkedIn anti-bot); the URL is valid in a browser.

## Maintainers

- Kin Lane — kin@apievangelist.com
