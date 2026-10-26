# CargoDocs (cargodocs)

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

CargoDocs, operated by EssDocs, is a digital trade documentation platform that eliminates paper-based shipping documents by letting carriers, shippers, banks, and partner platforms issue, sign, transfer, and surrender original electronic bills of lading (eBoL), sea waybills (SWB), warehouse warrants (eWW), and supporting trade documents. CargoDocs DocEx is used by container lines, NVOCCs, bulk/tanker carriers, commodity shippers, and trade finance banks to move documents in minutes rather than days while retaining negotiability and legal effect. Developers interact with CargoDocs through three OpenAPI-described REST APIs hosted on ReadMe - the Partner API (embed DocEx in third-party platforms), the Issuer API (carrier/NVOCC issuance and amendments), and the Customer Data/Docs API (exporter drafting and back-office integration).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Bills of Lading
- Documentation
- eBoL
- EssDocs
- MLETR
- Shipping
- Supply Chain
- Trade
- Trade Finance
- Warehouse Warrants

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### CargoDocs Partner API

The CargoDocs Partner API enables platform providers and trade finance/trade management platforms to embed CargoDocs DocEx functionality, including original electronic bills of lading (eBoL) and warehouse warrants (eWW). The API exposes Partner Exchange endpoints to retrieve customer, counterparty, document, and transaction data using conditions and filters, and Action endpoints to perform operations over transactions such as signing, transferring, and surrendering documents.

- **Human URL:** [https://cargodocs-partner.readme.io/](https://cargodocs-partner.readme.io/)
- **Base URL:** `https://api.essdocs.com`

#### Tags

- Bills of Lading
- Shipping
- Trade

#### Properties

- [Documentation](https://cargodocs-partner.readme.io/)
- [Getting Started](https://cargodocs-partner.readme.io/docs/api-environments)
- [OpenAPI](openapi/cargodocs-partner-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cargodocs-partner.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cargodocs-partner.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cargodocs-customer.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cargodocs-counterparty.json) — [JSON Schema](https://json-schema.org/specification)

### CargoDocs Issuer API

The CargoDocs Issuer API enables container lines, NVOCCs, and bulk/tanker carriers to manage electronic straight and negotiable bills of lading and sea waybills at origin or destination from within their TMS. It supports sharing draft eBoL/SWB for shipper approval, signing and issuing original eBoL/SWB, receiving surrendered original electronic bills of lading, and managing amendment requests or splits of an eBoL.

- **Human URL:** [https://cargodocs-issuer.readme.io/](https://cargodocs-issuer.readme.io/)
- **Base URL:** `https://api.essdocs.com`

#### Tags

- Bills of Lading
- Issuance
- Shipping

#### Properties

- [Documentation](https://cargodocs-issuer.readme.io/)
- [Getting Started](https://cargodocs-issuer.readme.io/docs/first-api-call)
- [OpenAPI](openapi/cargodocs-issuer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cargodocs-issuer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cargodocs-issuer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cargodocs-bill-of-lading.json) — [JSON Schema](https://json-schema.org/specification)

### CargoDocs Customer Data/Docs API

The CargoDocs Customer Data/Docs API enables exporters and commodity shippers to draft trade and shipping documents, including tanker, bulker, or barge bills of lading, from data imported out of ERP, CTRM, TMS, or WMS systems. It also enables any party using CargoDocs to download copy documents and structured transaction data to automate back-office steps such as invoicing, reconciliation, and reporting.

- **Human URL:** [https://cargodocs-customer.readme.io/](https://cargodocs-customer.readme.io/)
- **Base URL:** `https://api.essdocs.com`

#### Tags

- Documents
- Shipping
- Trade

#### Properties

- [Documentation](https://cargodocs-customer.readme.io/)
- [OpenAPI](openapi/cargodocs-customer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cargodocs-customer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cargodocs-customer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cargodocs-transaction.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cargodocs-document.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [Website](https://www.essdocs.com/)
- [Product](https://www.essdocs.com/cargodocs)
- [J S O N L D Context](json-ld/cargodocs-context.jsonld)
- [Partner  Docs](https://cargodocs-partner.readme.io/)
- [Issuer  Docs](https://cargodocs-issuer.readme.io/)
- [Customer  Docs](https://cargodocs-customer.readme.io/)
- [Blog](https://www.essdocs.com/blog)
- [Contact](https://www.essdocs.com/contact)
- [Terms of Service](https://www.essdocs.com/terms)
- [Privacy Policy](https://www.essdocs.com/privacy)
- [LinkedIn](https://www.linkedin.com/company/essdocs)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
