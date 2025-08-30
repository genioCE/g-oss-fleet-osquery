# g-oss-fleet-osquery — FleetDM (osquery)

**What:** Fleet server + MySQL + Redis; manage osquery on endpoints and ship query results to your SIEM.

**Why:** Asset inventory, configuration drift, vuln snapshots without per-endpoint license creep.

**Quick start**
```bash
cp .env.example .env
docker compose up -d
# Fleet UI: http://localhost:8080  (init on first run)
```
