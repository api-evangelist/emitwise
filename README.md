# Emitwise (emitwise)

Emitwise is a London-based AI carbon accounting platform that measures and reports product carbon footprint (PCF) and Scope 3 supply-chain emissions for large enterprises. The Emitwise developer API exposes facilities, sustainability projects, activity-data file uploads, schema metadata, and aggregated supplier emissions so customers can wire carbon accounting into procurement, ERP, and sustainability-reporting workflows. In July 2025, Emitwise was acquired by Green Project Technologies; the platform, team, and existing API at `api.emitwise.com` remain live as part of Green Project's end-to-end decarbonization solutions.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/emitwise/refs/heads/main/apis.yml)

## Tags

- Carbon Accounting, Greenhouse Gas, Scope 3, Supply Chain Emissions, Product Carbon Footprint, Sustainability, ESG, CDP, CSRD, GHG Protocol, Climate, Procurement, AI

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Emitwise API

The Emitwise REST API at `api.emitwise.com` is documented at [docs.emitwise.com](https://docs.emitwise.com/). It uses bearer authentication with per-customer API keys created from Company settings in the Emitwise dashboard. Access is granted on request through your Emitwise customer success manager. The API surface covers:

- **Facilities** — physical or virtual locations (offices, factories, business units) used to group emissions data.
- **Projects** — sustainability initiatives that scope and track decarbonization work.
- **Schema** — the active schema describing how activity-data files must be structured before upload.
- **Files** — upload tabular activity data so emissions can be calculated against the customer's footprint.
- **Suppliers** — paginated, filtered access to aggregated Scope 3 supplier emissions auto-identified from spend data via `POST /suppliers/list`.

**Human URL:** [https://docs.emitwise.com/](https://docs.emitwise.com/)

- [Documentation — Getting Started](https://docs.emitwise.com/)
- [Documentation — v1 Reference](https://docs.emitwise.com/v1)
- [OpenAPI](openapi/emitwise-api-openapi.yml)
- [JSON Schema — Facility](json-schema/emitwise-facility-schema.json)
- [JSON Schema — Supplier](json-schema/emitwise-supplier-schema.json)
- [JSON-LD Context](json-ld/emitwise-context.jsonld)

## Common Properties

- [Website](https://emitwise.com/)
- [Documentation](https://docs.emitwise.com/)
- [Dashboard](https://dash.emitwise.com/)
- [PCF Calculator](https://emitwise.com/pcf-calculator/)
- [Procurewise — Supply Chain Emissions](https://emitwise.com/solutions/procurewise-supply-chain-emissions/)
- [Privacy](https://emitwise.com/privacy/)
- [Terms of Service](https://emitwise.com/terms/)
- [Blog](https://emitwise.com/home/feed/)
- [Parent Company — Green Project Technologies](https://www.greenprojecttech.com/)
- [Contact — Green Project](https://www.greenprojecttech.com/contact/get-in-touch)
- [GitHub — emitwise](https://github.com/emitwise)

## Notes

- **Acquisition:** Emitwise was acquired by Green Project Technologies in July 2025. Sales and demos route to Green Project, but the Emitwise developer portal, dashboard, and `api.emitwise.com` endpoints remain in operation for existing customers.
- **GitHub presence:** The `github.com/emitwise` org currently exposes only a single fork of IBM's `carbon` design system; SDKs, code samples, and the canonical OpenAPI specification are not published openly. The OpenAPI in this repo is reconstructed from the public documentation at `docs.emitwise.com`.
- **Access model:** Not a self-serve developer API — customers request API access through their Emitwise / Green Project customer success manager, then generate keys from the dashboard's API Keys area.

## Maintainers

- Kin Lane — kin@apievangelist.com
