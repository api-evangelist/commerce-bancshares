# Commerce Bank (commerce-bancshares)

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
