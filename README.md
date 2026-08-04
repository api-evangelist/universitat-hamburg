# Universität Hamburg (universitat-hamburg)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
