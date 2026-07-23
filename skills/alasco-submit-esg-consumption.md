---
name: Submit ESG utility meters and consumption data
description: Register buildings' utility meters, upsert tenants, and bulk-load meter readings and consumption intervals into Alasco ESG for sustainability reporting.
api: openapi/alasco-esg-openapi.json
operations:
- get_buildings_buildings__get
- add_utility_meter_utility_meters__post
- upsert_tenant_tenants__post
- bulk_create_utility_meter_readings_meter_readings_bulk__post
- bulk_create_consumption_intervals_consumption_intervals_bulk__post
---

# Submit ESG utility meters and consumption data (Alasco ESG)

Base URL `https://api.alasco.de/esg/v1`. Auth via `X-API-KEY` + `X-API-TOKEN`; trailing slashes required.

## Steps
1. **List buildings** — `get_buildings_buildings__get` (`GET /buildings/`) to resolve `building_uuid`.
2. **Register a utility meter** — `add_utility_meter_utility_meters__post` (`POST /utility-meters/`); bulk via `bulk_add_utility_meter_import_partial_utility_meters_bulk_import_partial__post`.
3. **Upsert tenants** — `upsert_tenant_tenants__post` (`POST /tenants/`) to create or update building tenants.
4. **Load meter readings** — `bulk_create_utility_meter_readings_meter_readings_bulk__post` (`POST /meter-readings/bulk/`), keyed by external meter id.
5. **Load consumption intervals** — `bulk_create_consumption_intervals_consumption_intervals_bulk__post` (`POST /consumption-intervals/bulk/`).
6. **Read the CO2 analysis** — `get_analysis_result_buildings__building_uuid__analysis_result__get` (`GET /buildings/{building_uuid}/analysis-result/`).

## Notes
- Bulk endpoints may return **207 Multi-Status** with per-item results — inspect each item's status, do not assume all-or-nothing.
- Audit trails are available via `get_events_raw_audit__get` (`GET /raw-audit/`).
