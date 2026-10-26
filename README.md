# Neo Financial (neo-financial)

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

Neo Financial is a Calgary- and Winnipeg-based Canadian fintech (neobank) founded in 2019 by the founders of SkipTheDishes, offering credit cards, savings, money, investing, and mortgage products to consumers. Neo is not a chartered bank and holds no Canadian banking licence; it delivers CDIC-eligible deposits and card issuance through regulated partner institutions — Peoples Bank of Canada for everyday accounts, ATB Financial as Mastercard credit-card issuer, and formerly Concentra Bank (now part of Equitable Bank) for savings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/neo-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/neo-financial/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Neo Financial operates a consumer mobile and web platform only. It publishes **no first-party public developer API and no developer portal** — `developer.neofinancial.com`, `api.neofinancial.com`, and `docs.neofinancial.com` do not resolve. Third-party access to Neo accounts today is available solely through data aggregators such as **Flinks** (a National Bank-owned Canadian aggregator) and **Plaid**, via credential/screen-scraping access rather than a documented first-party API.

Canada's federal **Consumer-Driven Banking** (open banking) framework — legislated in Budget 2024 and the Fall Economic Statement 2024, and overseen by the Financial Consumer Agency of Canada (FCAC) — is **legislated but not yet operational**. Neo has published no first-party FDX/CDB data-access API and no stated Consumer-Driven Banking posture.

Neo does maintain a public **GitHub organization** ([github.com/neofinancial](https://github.com/neofinancial)) of internal engineering tooling (ESLint config, Serverless plugins, GitHub Actions, GraphQL scalars) and an **engineering blog** ([engineering.neofinancial.com](https://engineering.neofinancial.com/)), but none of these are public API products.

## Tags

- Financial Services
- Banking
- Canada
- Fintech
- Neobank
- Consumer Finance
- Credit Cards
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Neo Financial exposes no public first-party developer API. Consumer account data is reachable only through third-party aggregators (Flinks, Plaid).

## Common Properties

- [Website](https://www.neofinancial.com/)
- [GitHub Organization](https://github.com/neofinancial)
- [LinkedIn](https://www.linkedin.com/company/neo-financial)
- [Blog](https://www.neofinancial.com/blog)
- [Engineering Blog](https://engineering.neofinancial.com/)
- [Support](https://support.neofinancial.com/hc/en-ca)
- [Privacy Policy](https://www.neofinancial.com/legal/privacy-policy)
- [Terms of Service](https://legal.neo.cc/platform-terms-conditions)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
