# Curtin University (curtin)

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
