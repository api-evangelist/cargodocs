# CargoDocs (cargodocs)

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
