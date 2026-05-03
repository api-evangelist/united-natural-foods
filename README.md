# United Natural Foods (united-natural-foods)

United Natural Foods, Inc. (UNFI) is the largest publicly traded wholesale distributor of health and specialty food in the United States and Canada. UNFI supplies natural, organic, specialty, and conventional foods to over 30,000 retail locations. UNFI provides digital portals and APIs for suppliers and retailers including the Harmony Core API, supplier portal, myUNFI customer portal, and EDI integration.

**URL:** [View APIs.json](https://raw.githubusercontent.com/api-evangelist/united-natural-foods/refs/heads/main/apis.yml)

## Scope

- **Type:** Company
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Food Distribution
- Wholesale
- Natural Foods
- Supply Chain
- Fortune 500

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-03

## APIs

### UNFI Harmony Core API

UNFI's Harmony Core API provides read-only access to 42 data files covering supplier, product, inventory, and sales data. Supports SQL-style queries for data analytics platforms.

- **Human URL:** [https://suppliers.unfi.com](https://suppliers.unfi.com)
- **Base URL:** https://api.unfi.com/v1

#### Properties

| Type | URL |
|---|---|
| Documentation | [https://suppliers.unfi.com](https://suppliers.unfi.com) |
| OpenAPI | [unfi-supplier-openapi.yml](openapi/unfi-supplier-openapi.yml) |

### UNFI EDI Integration

EDI-based automated exchange of purchase orders, invoices, and fulfillment data for suppliers and retailers in UNFI's distribution network.

- **Human URL:** [https://suppliers.unfi.com](https://suppliers.unfi.com)

## Common Properties

| Type | URL |
|---|---|
| Website | [https://www.unfi.com](https://www.unfi.com) |
| Supplier Portal | [https://suppliers.unfi.com](https://suppliers.unfi.com) |
| Customer Portal | [https://www.myunfi.com](https://www.myunfi.com) |
| Investor Relations | [https://ir.unfi.com](https://ir.unfi.com) |
| LinkedIn | [https://www.linkedin.com/company/unfi](https://www.linkedin.com/company/unfi) |
| X | [https://twitter.com/UNFIInc](https://twitter.com/UNFIInc) |

## Artifacts

### OpenAPI Specifications

- [openapi/unfi-supplier-openapi.yml](openapi/unfi-supplier-openapi.yml) — Supplier and Data API covering products, orders, insights, and supplier management (12 operations)

### Spectral Rules

- [rules/unfi-supplier-rules.yml](rules/unfi-supplier-rules.yml) — Spectral ruleset for UNFI API conventions

### Naftiko Capabilities

- [capabilities/supplier-management.yaml](capabilities/supplier-management.yaml) — Unified supplier management workflow (11 MCP tools)
- [capabilities/shared/unfi-supplier.yaml](capabilities/shared/unfi-supplier.yaml) — Shared per-API supplier definition

### JSON Schema

- [json-schema/unfi-supplier-product-schema.json](json-schema/unfi-supplier-product-schema.json) — Product catalog schema
- [json-schema/unfi-supplier-order-schema.json](json-schema/unfi-supplier-order-schema.json) — Purchase order schema

### JSON Structure

- [json-structure/unfi-supplier-product-structure.json](json-structure/unfi-supplier-product-structure.json) — Product data structure

### JSON-LD Context

- [json-ld/united-natural-foods-context.jsonld](json-ld/united-natural-foods-context.jsonld) — Linked data context with GS1 and schema.org mappings

### Examples

- [examples/unfi-supplier-listProducts-example.json](examples/unfi-supplier-listProducts-example.json)
- [examples/unfi-supplier-getSalesInsights-example.json](examples/unfi-supplier-getSalesInsights-example.json)
- [examples/unfi-supplier-listOrders-example.json](examples/unfi-supplier-listOrders-example.json)

### Vocabulary

- [vocabulary/united-natural-foods-vocabulary.yml](vocabulary/united-natural-foods-vocabulary.yml) — Domain vocabulary (fill rates, EDI, certifications, distribution channels, etc.)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
