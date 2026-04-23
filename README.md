# CargoDocs (cargodocs)
CargoDocs, operated by EssDocs, is a digital trade documentation platform that eliminates paper-based shipping documents by letting carriers, shippers, banks, and partner platforms issue, sign, transfer, and surrender original electronic bills of lading (eBoL), sea waybills (SWB), warehouse warrants (eWW), and supporting trade documents. CargoDocs DocEx is used by container lines, NVOCCs, bulk/tanker carriers, commodity shippers, and trade finance banks to move documents in minutes rather than days while retaining negotiability and legal effect. Developers interact with CargoDocs through three OpenAPI-described REST APIs hosted on ReadMe - the Partner API (embed DocEx in third-party platforms), the Issuer API (carrier/NVOCC issuance and amendments), and the Customer Data/Docs API (exporter drafting and back-office integration).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
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

## Overview

CargoDocs DocEx is the product that underpins EssDocs' electronic trade document service. It supports both straight and negotiable bills of lading, sea waybills, warehouse warrants, and associated trade docs - keeping legal effect through digital signature, title transfer, and surrender flows that are acceptable to banks, carriers, and regulators. The platform ships with three API surfaces: a Partner API that lets TMS/trade finance platforms embed DocEx natively, an Issuer API for carriers and NVOCCs to sign, amend, and split eBoL/SWB, and a Customer Data/Docs API that lets exporters draft documents from ERP/CTRM/TMS/WMS data and download copy documents for back-office automation. Each API is described by its own OpenAPI specification and is complemented by JSON Schemas for the core domain entities (customer, counterparty, transaction, document, bill of lading) plus a shared JSON-LD context.

## APIs

### CargoDocs Partner API
The CargoDocs Partner API enables platform providers and trade finance/trade management platforms to embed CargoDocs DocEx functionality, including original electronic bills of lading (eBoL) and warehouse warrants (eWW). The API exposes Partner Exchange endpoints to retrieve customer, counterparty, document, and transaction data using conditions and filters, and Action endpoints to perform operations over transactions such as signing, transferring, and surrendering documents.

**Human URL:** [https://cargodocs-partner.readme.io/](https://cargodocs-partner.readme.io/)

#### Features

- Retrieve customer, counterparty, and transaction data with filters
- Perform signing, transferring, and surrendering actions
- Embed DocEx workflows in partner platforms
- Sandbox and production API environments
- JSON document retrieval plus PDF rendering
- Partner-scoped authentication and audit trail

#### Use Cases

- Trade finance platforms embedding eBoL workflows
- TMS/CTRM providers offering native digital docs
- Freight forwarder portals with integrated surrender flows
- Bank-held eBoL custody during letter-of-credit settlement

### CargoDocs Issuer API
The CargoDocs Issuer API enables container lines, NVOCCs, and bulk/tanker carriers to manage electronic straight and negotiable bills of lading and sea waybills at origin or destination from within their TMS. It supports sharing draft eBoL/SWB for shipper approval, signing and issuing original eBoL/SWB, receiving surrendered original electronic bills of lading, and managing amendment requests or splits of an eBoL.

**Human URL:** [https://cargodocs-issuer.readme.io/](https://cargodocs-issuer.readme.io/)

#### Features

- Draft, sign, and issue original eBoL / SWB
- Shipper approval workflow for drafts
- Receive surrendered original eBoL at destination
- Amendment requests and eBoL split handling
- Straight and negotiable bill of lading support
- Carrier-side legal audit trail

#### Use Cases

- Container line TMS integration
- NVOCC issuance automation
- Bulk/tanker carrier documentation
- Origin/destination eBoL surrender workflows

### CargoDocs Customer Data/Docs API
The CargoDocs Customer Data/Docs API enables exporters and commodity shippers to draft trade and shipping documents, including tanker, bulker, or barge bills of lading, from data imported out of ERP, CTRM, TMS, or WMS systems. It also enables any party using CargoDocs to download copy documents and structured transaction data to automate back-office steps such as invoicing, reconciliation, and reporting.

**Human URL:** [https://cargodocs-customer.readme.io/](https://cargodocs-customer.readme.io/)

#### Features

- Drafting of tanker, bulker, and barge bills of lading
- ERP/CTRM/TMS/WMS data import
- Copy document and structured data download
- Transaction metadata for back-office automation
- Exporter-friendly document templates

#### Use Cases

- Commodity shipper documentation automation
- ERP-driven eBoL drafting
- Back-office reconciliation of shipping documents
- Data feeds into trade finance and invoicing systems

## Common Properties

- [Website](https://www.essdocs.com/)
- [Product](https://www.essdocs.com/cargodocs)
- [CargoDocs JSON-LD Context](json-ld/cargodocs-context.jsonld)
- [Partner API Docs](https://cargodocs-partner.readme.io/)
- [Issuer API Docs](https://cargodocs-issuer.readme.io/)
- [Customer API Docs](https://cargodocs-customer.readme.io/)
- [Blog](https://www.essdocs.com/blog)
- [Contact](https://www.essdocs.com/contact)
- [Terms of Service](https://www.essdocs.com/terms)
- [Privacy Policy](https://www.essdocs.com/privacy)
- [LinkedIn](https://www.linkedin.com/company/essdocs)

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
