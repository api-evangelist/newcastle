# Newcastle University (newcastle)

Newcastle University is a public research university in Newcastle upon Tyne, United Kingdom, ranked #129 in the QS World University Rankings 2025. This repository catalogs the university's real, public developer and API footprint as an APIs.json provider profile. Rather than a single central developer portal, Newcastle's footprint is distributed across research and open-data initiatives — most notably the Urban Observatory, the Digitised Objects Repository, and the data.ncl research data repository.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/newcastle/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=newcastle-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Open Data, Research Data, Smart Cities, Digital Library

## APIs

- **Newcastle Urban Observatory API** — REST API for urban-sensing data (entities, feeds, timeseries) in JSON/CSV. Docs: https://api.usb.urbanobservatory.ac.uk/ — OpenAPI: https://api.usb.urbanobservatory.ac.uk/openapi.json
- **Digitised Objects Repository Search and Data API** — programmatic search and data access to digitised collections. Docs: https://api-dor.ncl.ac.uk/
- **ECPPEC Electoral Data API** — historical British electoral datasets (pollbooks, election directory). Docs: https://ecppec.ncl.ac.uk/api/
- **data.ncl Research Data Repository (Figshare)** — institutional research data repository with Figshare API access. Docs: https://www.ncl.ac.uk/library/academics-and-researchers/lrs/rdm/sharing/datancl/
- **EPrints Institutional Repository (OAI-PMH)** — eprints.ncl.ac.uk and theses.ncl.ac.uk expose OAI-PMH metadata harvesting. Docs: https://eprints.ncl.ac.uk/

## Plans

- [plans/newcastle-plans-pricing.yml](plans/newcastle-plans-pricing.yml)

## Rate Limits

- [rate-limits/newcastle-rate-limits.yml](rate-limits/newcastle-rate-limits.yml)

## FinOps

- [finops/newcastle-finops.yml](finops/newcastle-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ncl.ac.uk/
- GitHub: https://github.com/newcastleuniversity (verified org, domain ncl.ac.uk)
- LinkedIn: https://www.linkedin.com/school/newcastle-university
- Twitter/X: https://x.com/UniofNewcastle

## Notes

All APIs and URLs were verified live during research on 2026-06-03 (see review.yml for HTTP statuses). Newcastle has no single unified developer portal; the cataloged APIs are real, separately operated services. The ECPPEC apex API host (api-ecppec.ncl.ac.uk) returned HTTP 400 and was therefore not cataloged as a baseURL — only the documented endpoint form is listed. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
