# Commerce Bank (commerce-bancshares)

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

Commerce Bank is the principal banking subsidiary of Commerce Bancshares, Inc. (NASDAQ: CBSH), a Missouri-based regional bank holding company with roughly $32 billion in assets and dual headquarters in Kansas City and St. Louis. Founded in 1865, Commerce Bank is a Missouri state-chartered bank and Federal Reserve member offering personal, business, commercial, payments/treasury, and wealth-management services across the U.S. Midwest.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/commerce-bancshares/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/commerce-bancshares/refs/heads/main/apis.yml)

## Open Finance / API Posture

The U.S. has no single mandated open-banking contract; open finance is voluntary and fragmented. Commerce Bank's posture is corporate- and embedded-banking oriented rather than a fully open, self-serve public API program:

- **First-party developer portal:** Commerce Bank runs an external developer portal at [developers.commercebank.com](https://developers.commercebank.com/). It is genuinely live but sits behind an Imperva/Incapsula bot wall and requires registration — no anonymous `200` and no publicly downloadable OpenAPI/Swagger were obtained during this review.
- **CommercePayments developer platform:** Commerce is building an outward-facing developer platform exposing APIs and batch file transfers for real-time data exchange with customers' business systems.
- **Embedded banking:** Commerce Connections® Direct embeds payments and banking utilities directly into ERP/accounting systems (Sage, QuickBooks, NetSuite, Microsoft Business Central).
- **Aggregator / partner access:** Consumer-permissioned data and payment initiation are largely intermediated through aggregators such as **Plaid** and platforms like **Modern Treasury**, not a documented first-party self-serve API.
- **FDX / CFPB Section 1033:** No public Financial Data Exchange (FDX) participation statement or CFPB Section 1033 data-access posture is documented on Commerce Bank's public pages.

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- Payments
- Treasury Management
- Embedded Banking
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Commerce Bank Developer APIs

Commerce Bank's corporate API program, published through a registration-gated external developer portal and the CommercePayments developer platform, covering payments, treasury, and embedded-banking integrations for business and ERP systems. Access is partner/registration-gated; no public self-serve OpenAPI is published.

- **Human URL:** [https://developers.commercebank.com/](https://developers.commercebank.com/)

#### Tags

- Payments
- Treasury Management
- Embedded Banking

#### Properties

- [Developer Portal](https://developers.commercebank.com/)
- [Embedded Banking (Commerce Connections Direct)](https://www.commercebank.com/corporate/solutions/payments-treasury/payables/embedded-banking)
- [CommercePayments overview](https://www.commercebank.com/business/trends-and-insights/2024/how-commercepayments-is-transforming-corporate-finance-processes)

## Common Properties

- [Website](https://www.commercebank.com/)
- [Developer Portal](https://developers.commercebank.com/)
- [Blog](https://www.commercebank.com/business/trends-and-insights)
- [Terms of Service](https://www.commercebank.com/terms-of-use)
- [Privacy Policy](https://www.commercebank.com/security-center/privacy-statement)
- [Support](https://www.commercebank.com/contact-us)
- [LinkedIn](https://www.linkedin.com/company/commerce_bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
