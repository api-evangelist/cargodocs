# CargoDocs (cargodocs)
CargoDocs is a digital platform that streamlines and automates the documentation process for global trade transactions. By digitizing and centralizing all shipping documents, such as bills of lading, certificates of origin, and invoices, CargoDocs eliminates the need for manual paperwork and reduces the risk of errors and delays. This innovative solution enables parties involved in the trade to easily access, manage, and share essential documents in real-time, leading to faster and more efficient transactions. Additionally, CargoDocs offers secure electronic signatures and time-stamped audit trails, ensuring the authenticity and compliance of all trade documents. Overall, CargoDocs revolutionizes the way businesses handle their shipping documentation, making international trade simpler, more transparent, and more secure.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Documentation, Shipping

## Timestamps

- **Created:** 2025-01-08 
- **Modified:** 2026-03-14 

## APIs

### CargoDocs Partner API
The CargoDocs Partner API enables partners and platform providers to embed CargoDocs DocEx functionality into their trade or trade finance platforms, handling original electronic bills of lading (eBoL) and warehouse warrants (eWW). The Partner Exchange API retrieves customer and partner data to perform specific actions, with endpoints to retrieve data based on conditions and filters and Action endpoints to action over transactions.

**Human URL:** [https://cargodocs-partner.readme.io/](https://cargodocs-partner.readme.io/)


#### Tags:

 - Shipping, Trade, Bills of Lading

#### Properties

- [Documentation](https://cargodocs-partner.readme.io/)
- [GettingStarted](https://cargodocs-partner.readme.io/docs/api-environments)
- [OpenAPI](openapi/cargodocs-partner-openapi.yml)
- [JSONSchema](json-schema/cargodocs-customer.json)
- [JSONSchema](json-schema/cargodocs-counterparty.json)

### CargoDocs Issuer API
The CargoDocs Issuer API enables container lines or NVOCCs to manage relevant tasks relating to electronic straight and negotiable bills of lading at Origin or Destination from within their TMS. The API supports sharing draft eBoL/SWB for shipper approval, signing and issuing original eBoL/SWB, receiving surrendered original electronic bills of lading, and managing Amendment Requests or Splits of an eBoL.

**Human URL:** [https://cargodocs-issuer.readme.io/](https://cargodocs-issuer.readme.io/)


#### Tags:

 - Shipping, Bills of Lading, Issuance

#### Properties

- [Documentation](https://cargodocs-issuer.readme.io/)
- [GettingStarted](https://cargodocs-issuer.readme.io/docs/first-api-call)
- [OpenAPI](openapi/cargodocs-issuer-openapi.yml)
- [JSONSchema](json-schema/cargodocs-bill-of-lading.json)

### CargoDocs Customer Data/Docs API
The CargoDocs Customer Data/Docs API enables exporters to draft trade and shipping documents, including tanker, bulker, or barge bills of lading from data imported from an ERP system, CTRM, TMS, WMS, etc. It also enables any party using CargoDocs to download copy docs and data to automate various back-office steps.

**Human URL:** [https://cargodocs-customer.readme.io/](https://cargodocs-customer.readme.io/)


#### Tags:

 - Shipping, Documents, Trade

#### Properties

- [Documentation](https://cargodocs-customer.readme.io/)
- [OpenAPI](openapi/cargodocs-customer-openapi.yml)
- [JSONSchema](json-schema/cargodocs-transaction.json)
- [JSONSchema](json-schema/cargodocs-document.json)

## Common Properties

- [JSONLDContext](json-ld/cargodocs-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
