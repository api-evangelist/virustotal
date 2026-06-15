# VirusTotal (virustotal)

VirusTotal — the Google-owned (since 2012) threat intelligence platform that aggregates anti-malware engines and URL scanners to analyse files, URLs, IP addresses, and domains. The v3 API surfaces seven major areas: Access Control, IoC Feeds, IoC Investigation, Private Scanning, Threat Graphs, Threat Landscape & Vulnerability Intelligence, and YARA Hunting (Livehunt, Retrohunt, IoC Stream). Now also branded "Google Threat Intelligence" (GTI) for Enterprise customers, integrating Mandiant intelligence, Digital Threat Monitoring (DTM), and Attack Surface Management (ASM).

**APIs.json:** [https://docs.virustotal.com/reference/overview](https://docs.virustotal.com/reference/overview)

## Tags

- Anti-Malware
- Threat Intelligence
- Security
- File Analysis
- URL Analysis
- YARA
- IoC
- Sandbox
- MITRE ATT&CK
- Google Cloud

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### VirusTotal API v3 - Access Control

Manage users, groups, service accounts, API quotas, and overall account usage. The control plane that wraps every other VirusTotal API surface.

- **Human URL:** [https://docs.virustotal.com/reference/overview](https://docs.virustotal.com/reference/overview)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Access Control
- Administration
- Quotas

#### Properties

- [Documentation](https://docs.virustotal.com/reference/overview)
- [API Reference](https://gtidocs.virustotal.com/reference/overview)
- [OpenAPI](openapi/virustotal-access-control-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/virustotal-access-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-access-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VirusTotal API v3 - IoC Feeds

Per-minute and hourly intelligence feed batches for files, URLs, domains, IP addresses, and sandbox analyses. Premium tier required. The bulk pipeline behind SIEM / SOAR / data-lake integrations.

- **Human URL:** [https://docs.virustotal.com/reference/feeds](https://docs.virustotal.com/reference/feeds)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Threat Intelligence
- Feeds
- Sandbox
- Premium

#### Properties

- [Documentation](https://docs.virustotal.com/reference/feeds)
- [OpenAPI](openapi/virustotal-ioc-feeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/virustotal-ioc-feeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-ioc-feeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VirusTotal API v3 - IoC Investigation

Investigate files, URLs, IP addresses, and domains. Submit and analyse samples, retrieve verdicts, traverse the relationships graph, fetch sandbox behaviour, post comments and votes, search the corpus. The day-one surface for SOC and incident response.

- **Human URL:** [https://docs.virustotal.com/reference/files](https://docs.virustotal.com/reference/files)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Threat Intelligence
- Investigation
- Files
- URLs
- Domains
- IP Addresses
- Sandbox
- MITRE ATT&CK

#### Properties

- [Documentation](https://docs.virustotal.com/reference/files)
- [OpenAPI](openapi/virustotal-ioc-investigation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/virustotal-ioc-investigation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-ioc-investigation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VirusTotal API v3 - Private Scanning

Submit files and URLs for analysis without sharing the artefact with the VirusTotal community. Mirrors the public scanning surface (Files / URLs / Analyses / Behaviours / Zip Files). Premium tier required.

- **Human URL:** [https://docs.virustotal.com/reference/private-scanning](https://docs.virustotal.com/reference/private-scanning)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Threat Intelligence
- Private Scanning
- Premium
- Sandbox

#### Properties

- [Documentation](https://docs.virustotal.com/reference/private-scanning)
- [OpenAPI](openapi/virustotal-private-scanning-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/virustotal-private-scanning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-private-scanning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VirusTotal API v3 - Threat Graphs

Create, share, edit, and search Threat Graphs — visualisations of how IoCs and threats relate. Includes the editor / viewer ACL surface for collaboration.

- **Human URL:** [https://docs.virustotal.com/reference/graphs](https://docs.virustotal.com/reference/graphs)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Threat Intelligence
- Graphs
- Collaboration

#### Properties

- [Documentation](https://docs.virustotal.com/reference/graphs)
- [OpenAPI](openapi/virustotal-threat-graphs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/virustotal-threat-graphs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-threat-graphs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VirusTotal API v3 - Threat Landscape & Vulnerability Intelligence

Threat Landscape — Collections, Threat Actors, Malware & Tools, Campaigns, Reports, Vulnerabilities, and the curated IoC catalogue. Premium tier; this is where Mandiant-curated intelligence surfaces.

- **Human URL:** [https://docs.virustotal.com/reference/collections](https://docs.virustotal.com/reference/collections)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Threat Intelligence
- Threat Actors
- Malware Families
- Campaigns
- Vulnerabilities
- Premium

#### Properties

- [Documentation](https://docs.virustotal.com/reference/collections)
- [OpenAPI](openapi/virustotal-threat-landscape-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/virustotal-threat-landscape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-threat-landscape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VirusTotal API v3 - YARA Hunting (Livehunt, Retrohunt, IoC Stream)

Livehunt (real-time YARA matching on incoming corpus), Retrohunt (historical YARA scans), the IoC Stream, and crowdsourced YARA rules. The hunting and notification surface. Premium tier required for write operations; rule reads are free.

- **Human URL:** [https://docs.virustotal.com/reference/livehunt](https://docs.virustotal.com/reference/livehunt)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Threat Intelligence
- YARA
- Hunting
- Premium

#### Properties

- [Documentation](https://docs.virustotal.com/reference/livehunt)
- [OpenAPI](openapi/virustotal-yara-hunting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/virustotal-yara-hunting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-yara-hunting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Threat Intelligence - Attack Surface Management (ASM)

Enterprise add-on (formerly Mandiant Advantage ASM). Discovers and monitors an organisation's external attack surface, scoring exposures and prioritising remediation.

- **Human URL:** [https://gtidocs.virustotal.com/reference/openapi-specs](https://gtidocs.virustotal.com/reference/openapi-specs)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Attack Surface Management
- Enterprise
- GTI

#### Properties

- [API Reference](https://gtidocs.virustotal.com/openapi/asm-attack-surface-management.json)
- [Product Page](https://cloud.google.com/security/products/threat-intelligence)
- [Postman Collection](collections/virustotal-access-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-access-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-ioc-feeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-ioc-feeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-ioc-investigation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-ioc-investigation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-private-scanning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-private-scanning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-threat-graphs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-threat-graphs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-threat-landscape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-threat-landscape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-yara-hunting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-yara-hunting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Threat Intelligence - Digital Threat Monitoring (DTM)

Enterprise add-on (formerly Mandiant Advantage DTM). Monitors the open, deep, and dark web for credential leaks, brand abuse, and adversary chatter referencing the customer.

- **Human URL:** [https://gtidocs.virustotal.com/reference/openapi-specs](https://gtidocs.virustotal.com/reference/openapi-specs)
- **Base URL:** `https://www.virustotal.com/api/v3`

#### Tags

- Digital Threat Monitoring
- Dark Web
- Brand Protection
- Enterprise
- GTI

#### Properties

- [API Reference](https://gtidocs.virustotal.com/openapi/dtm-digital-threat-monitoring.json)
- [Product Page](https://cloud.google.com/security/products/threat-intelligence)
- [Postman Collection](collections/virustotal-access-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-access-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-ioc-feeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-ioc-feeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-ioc-investigation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-ioc-investigation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-private-scanning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-private-scanning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-threat-graphs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-threat-graphs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-threat-landscape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-threat-landscape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/virustotal-yara-hunting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/virustotal-yara-hunting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.virustotal.com)
- [Documentation](https://docs.virustotal.com/reference/overview)
- [API Reference](https://gtidocs.virustotal.com/reference/overview)
- [GitHub Organization](https://github.com/VirusTotal)
- [Blog](https://blog.virustotal.com/)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [OpenAPI](https://storage.googleapis.com/gtidocresources/guides/GTI_API_v3_openapi_spec_10022025.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://gtidocs.virustotal.com/openapi/asm-attack-surface-management.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://gtidocs.virustotal.com/openapi/dtm-digital-threat-monitoring.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://github.com/VirusTotal/vt-py)
- [SDK](https://github.com/VirusTotal/vt-go)
- [SDK](https://github.com/VirusTotal/vt-graph-api)
- [C L I](https://github.com/VirusTotal/vt-cli)
- [Tools](https://github.com/BurtTheCoder/mcp-virustotal)
- [Tools](https://github.com/alephnan/MCP-VirusTotal)
- [Tools](https://github.com/barvhaim/virustotal-mcp-server)
- [Tools](https://github.com/VirusTotal/yara)
- [Tools](https://github.com/VirusTotal/yara-x)
- [Tools](https://github.com/VirusTotal/yara-python)
- [Tools](https://github.com/VirusTotal/yara-x-benchmarks)
- [Tools](https://github.com/VirusTotal/go-yara)
- [Tools](https://github.com/VirusTotal/protoc-gen-yara)
- [Tools](https://github.com/VirusTotal/CAPEv2)
- [Tools](https://github.com/VirusTotal/vt-ida-plugin)
- [Tools](https://github.com/VirusTotal/vt-windows-event-stream)
- [Tools](https://github.com/VirusTotal/qt-virustotal-uploader)
- [Integration](https://github.com/VirusTotal/gti-Microsoft-Defender)
- [Integration](https://github.com/VirusTotal/gti-aws-GuardDuty)
- [Integration](https://github.com/VirusTotal/gti-google-secops-siem)
- [Integration](https://github.com/VirusTotal/gti-misp-connector)
- [Integration](https://github.com/VirusTotal/gti-soar-playbooks)
- [Integration](https://github.com/VirusTotal/GTI-Integrations-UserGuides)
- [Tutorials](https://github.com/VirusTotal/gti-dev-kit)
- [Plans](plans/virustotal-plans-pricing.yml)
- [Rate Limits](rate-limits/virustotal-rate-limits.yml)
- [Fin Ops](finops/virustotal-finops.yml)
- [Spectral Ruleset](rules/virustotal-rules.yml)
- [Vocabulary](vocabulary/virustotal-vocabulary.yml)
- [J S O N L D Context](json-ld/virustotal-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
