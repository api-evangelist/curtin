# Curtin University (curtin)

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

Curtin University is a public research university in Perth, Western Australia, ranked #174 in the QS World University Rankings 2025. This repository catalogs Curtin's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. Curtin does not currently operate a centralized public developer portal or a documented general-purpose API program; the verifiable footprint centers on its library/research repository (espace) and research-data registry contributions delivered through third-party platforms.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/curtin/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=curtin-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Library, Australia

## APIs

- **Curtin espace Institutional Repository** — open-access repository of Curtin research outputs and theses on Ex Libris Primo/Esploro. Docs: https://espace.curtin.edu.au/
- **Curtin Research Data (via Research Data Australia)** — Curtin research data collection records published through the national RDA registry. Docs: https://researchdata.edu.au/contributors/curtin-university

> No documented public REST/OAI-PMH endpoints could be independently verified during this review. Entries reflect confirmed platforms only; no endpoints were fabricated.

## Plans

- [plans/curtin-plans-pricing.yml](plans/curtin-plans-pricing.yml)

## Rate Limits

- [rate-limits/curtin-rate-limits.yml](rate-limits/curtin-rate-limits.yml)

## FinOps

- [finops/curtin-finops.yml](finops/curtin-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.curtin.edu.au/
- GitHub (Curtin Institute for Data Science): https://github.com/CurtinIDS
- GitHub (Curtin Open Knowledge Initiative): https://github.com/Curtin-Open-Knowledge-Initiative
- LinkedIn: https://www.linkedin.com/school/curtin-university/
- Review: [review.yml](review.yml)

## Notes

- Verification caveats: the legacy espace OAI-PMH path (OAI-PUB/2) now redirects into the Primo discovery web app rather than serving OAI-PMH responses.
- data.curtin.edu.au resolves to a static S3/CloudFront-hosted landing page, not an open-data API.
- No `api.curtin.edu.au`, `developer.curtin.edu.au`, or public status page resolved.
- There is no single official Curtin GitHub organization; only department-level orgs were found.

## Maintainers

- Kin Lane — kin@apievangelist.com
