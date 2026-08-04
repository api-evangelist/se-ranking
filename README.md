# SE Ranking

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

SE Ranking is an SEO platform providing a REST API for keyword rank tracking, competitor analysis, backlink monitoring, on-page auditing, AI search visibility, and generating white-label SEO reports. The platform covers 5.4B keywords, 2.2B domain profiles, and 188+ regions.

## APIs

SE Ranking exposes two API layers:

- **Data API** — Pay-as-you-go credit-based access to SE Ranking's SEO datasets: keyword research, backlink analysis, domain analysis, SERP data, website audits, and AI search visibility. Base URL: `https://api.seranking.com`
- **Project API** — Programmatic management of SEO tracking projects, including keyword monitoring, competitor tracking, website audits, and backlink management. Consumes subscription plan limits rather than separate API credits.

## Authentication

All API requests require an API key obtained from the SE Ranking account dashboard. The recommended method is passing the key in the `Authorization: Token YOUR_API_KEY` header. Query parameter (`apikey=YOUR_API_KEY`) is also supported.

## Links

- Website: https://seranking.com
- API Overview: https://seranking.com/api.html
- Data API Reference: https://seranking.com/api/data/reference/
- Project API Reference: https://seranking.com/api/project/
- API Pricing: https://seranking.com/api-pricing.html
- Rate Limits: https://seranking.com/api/rate-limits/
- Credit System: https://seranking.com/api/api-credits-system/
- Blog: https://seranking.com/blog/
- Status: https://status.seranking.com
- GitHub: https://github.com/seranking
- LinkedIn: https://www.linkedin.com/company/se-ranking
- X: https://x.com/SERanking
- Postman: https://www.postman.com/serankingdev/se-ranking-developers/overview

## Maintainer

Kin Lane (kin@apievangelist.com)
