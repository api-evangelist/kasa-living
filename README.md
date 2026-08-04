# Kasa Living

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

Kasa Living, Inc. (operating as **Kasa**) is a tech-enabled hospitality company founded in San
Francisco in 2016 by Roman Pedan. It partners with institutional real-estate owners to convert
multifamily, single-family and hotel inventory into professionally managed, apartment-style flexible
accommodations across 90+ U.S. cities, running a proprietary hospitality operating system for pricing,
automated operations, keyless self check-in and a 24/7 remote "Virtual Front Desk" in place of an
on-site front desk.

## API posture

**Kasa is an API consumer, not an API producer.** Full contract discovery was run against every
first-party host and every producer-side probe missed: no developer portal, no API reference, no
OpenAPI/Swagger/AsyncAPI/GraphQL document, no MCP server, no A2A agent card, no `/.well-known/`
document, no public GitHub organization, and no first-party SDK on any package registry.
`api.kasa.com`, `developer.kasa.com` and `mcp.kasa.com` do not resolve. Distribution to OTAs and GDS
runs through a third-party channel manager (the NextPax supply API), not through connectivity Kasa
publishes itself.

The one machine-readable, agent-facing artifact Kasa does publish is a substantial hand-authored
[`llms.txt`](https://kasa.com/llms.txt) — captured verbatim here at
[`llms/kasa-living-llms.txt`](llms/kasa-living-llms.txt). It carries a "Key facts for AI systems"
block, a full locations directory, an intent→URL prompt-mapping section, and explicit guidance to AI
systems including a do-not-fabricate instruction about inventory, pricing and policies. Kasa is
optimizing to be *described* correctly by agents, not to be *called* by them.

Full probe evidence — every URL and status code — is in [`review.yml`](review.yml).

## Links

- Website — https://kasa.com/
- llms.txt — https://kasa.com/llms.txt
- Help Center — https://help.kasa.com/
- Blog — https://blog.kasa.com/
- Terms of Use — https://kasa.com/legal/terms-of-use
- Privacy Policy — https://kasa.com/legal/privacy-policy
- Secondary-market listing (harvest source) — https://forgeglobal.com/kasa-living_stock/
