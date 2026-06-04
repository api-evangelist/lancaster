# Lancaster University (lancaster)

Lancaster University is a collegiate public research university in Lancaster, United Kingdom, ranked #141 in the QS World University Rankings 2025. This repository catalogs the institution's public, machine-accessible developer/API footprint as an [APIs.json](https://apisjson.org) profile. Lancaster's public footprint is modest and research/library oriented — a live EPrints OAI-PMH interface, open-source library integration code on GitHub, and gated Ex Libris Alma/Primo library services that back the iLancaster mobile app — rather than a single self-service API developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/lancaster/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=lancaster-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Research, Library, Open Data

## APIs

- **Lancaster EPrints OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the Lancaster EPrints institutional repository (EPrints 3.4.5). Verified live. Docs: https://eprints.lancs.ac.uk/cgi/oai2?verb=Identify — Base URL: https://eprints.lancs.ac.uk/cgi/oai2
- **Lancaster Library Alma Webhook Handler** — Open-source AWS serverless app (Lancaster University Library) for Ex Libris Alma webhook events. Docs: https://github.com/lulibrary/alma-webhook-handler
- **Lancaster Library Services (Ex Libris Alma/Primo)** — Library user/fine/loan/renewal web services powering the iLancaster app and student portal; documented but internal/gated. Docs: https://developers.exlibrisgroup.com/blog/student-portal-and-institutional-mobile-app-at-lancaster-university/

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/lancaster-plans-pricing.yml](plans/lancaster-plans-pricing.yml)
- Rate Limits: [rate-limits/lancaster-rate-limits.yml](rate-limits/lancaster-rate-limits.yml)
- FinOps: [finops/lancaster-finops.yml](finops/lancaster-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.lancaster.ac.uk/
- GitHub (main org): https://github.com/lancaster-university
- GitHub (Library): https://github.com/lulibrary
- LinkedIn: https://www.linkedin.com/school/lancaster-university/
- Repository: https://eprints.lancs.ac.uk/

## Notes

All entries reflect publicly verifiable sources as of 2026-06-03. The EPrints OAI-PMH endpoint was confirmed live (HTTP 200, valid Identify response). The `www.lancaster.ac.uk/api/` path returns a "Not authorised" page and is not a public API/developer portal. The Ex Libris Alma/Primo library web services are documented but internal/gated. No endpoints were fabricated. See [review.yml](review.yml) for probed URLs and HTTP statuses.

## Maintainers

- Kin Lane — kin@apievangelist.com
