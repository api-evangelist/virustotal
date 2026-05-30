# VirusTotal (virustotal)

VirusTotal — the Google-owned (since 2012) threat intelligence platform that aggregates anti-malware engines and URL scanners to analyse files, URLs, IP addresses, and domains. The v3 API surfaces seven major areas: Access Control, IoC Feeds, IoC Investigation, Private Scanning, Threat Graphs, Threat Landscape & Vulnerability Intelligence, and YARA Hunting (Livehunt, Retrohunt, IoC Stream). Now also branded "Google Threat Intelligence" (GTI) for Enterprise customers, integrating Mandiant intelligence, Digital Threat Monitoring (DTM), and Attack Surface Management (ASM).

**URL:** [Visit API Documentation](https://docs.virustotal.com/reference/overview)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Anti-Malware, Threat Intelligence, Security, File Analysis, URL Analysis, YARA, IoC, Sandbox, MITRE ATT&CK, Google Cloud

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### VirusTotal API v3 - Access Control
Manage users, groups, service accounts, API quotas, and overall account usage.

**Human URL:** [https://docs.virustotal.com/reference/overview](https://docs.virustotal.com/reference/overview)

#### Tags
Access Control, Administration, Quotas

#### Properties
- [Documentation](https://docs.virustotal.com/reference/overview)
- [APIReference](https://gtidocs.virustotal.com/reference/overview)
- [OpenAPI](openapi/virustotal-access-control-openapi.yml)
- [NaftikoCapability — Group Management](capabilities/access-control-access-control-group-management.yaml)
- [NaftikoCapability — Quota Management](capabilities/access-control-access-control-quota-management.yaml)
- [NaftikoCapability — Service Account Management](capabilities/access-control-access-control-service-account-management.yaml)
- [NaftikoCapability — User Management](capabilities/access-control-access-control-user-management.yaml)

### VirusTotal API v3 - IoC Feeds
Per-minute and hourly intelligence feed batches for files, URLs, domains, IP addresses, and sandbox analyses. Premium tier.

**Human URL:** [https://docs.virustotal.com/reference/feeds](https://docs.virustotal.com/reference/feeds)

#### Tags
Threat Intelligence, Feeds, Sandbox, Premium

#### Properties
- [Documentation](https://docs.virustotal.com/reference/feeds)
- [OpenAPI](openapi/virustotal-ioc-feeds-openapi.yml)
- [NaftikoCapability — Domain Feed](capabilities/ioc-feeds-ioc-feeds-domain-intelligence-feed.yaml)
- [NaftikoCapability — File Feed](capabilities/ioc-feeds-ioc-feeds-file-intelligence-feed.yaml)
- [NaftikoCapability — IP Feed](capabilities/ioc-feeds-ioc-feeds-ip-intelligence-feed.yaml)
- [NaftikoCapability — Sandbox Analyses Feed](capabilities/ioc-feeds-ioc-feeds-sandbox-analyses-feed.yaml)
- [NaftikoCapability — URL Feed](capabilities/ioc-feeds-ioc-feeds-url-intelligence-feed.yaml)

### VirusTotal API v3 - IoC Investigation
Investigate files, URLs, IP addresses, and domains. Submit and analyse samples, retrieve verdicts, traverse the relationships graph, fetch sandbox behaviour, post comments and votes, search the corpus.

**Human URL:** [https://docs.virustotal.com/reference/files](https://docs.virustotal.com/reference/files)

#### Tags
Threat Intelligence, Investigation, Files, URLs, Domains, IP Addresses, Sandbox, MITRE ATT&CK

#### Properties
- [Documentation](https://docs.virustotal.com/reference/files)
- [OpenAPI](openapi/virustotal-ioc-investigation-openapi.yml)
- [NaftikoCapability — Analyses, Submissions & Operations](capabilities/ioc-investigation-ioc-investigation-analyses-submissions-operations.yaml)
- [NaftikoCapability — Attack Tactics](capabilities/ioc-investigation-ioc-investigation-attack-tactics.yaml)
- [NaftikoCapability — Attack Techniques](capabilities/ioc-investigation-ioc-investigation-attack-techniques.yaml)
- [NaftikoCapability — Comments](capabilities/ioc-investigation-ioc-investigation-comments.yaml)
- [NaftikoCapability — Domains & Resolutions](capabilities/ioc-investigation-ioc-investigation-domains-resolutions.yaml)
- [NaftikoCapability — Files](capabilities/ioc-investigation-ioc-investigation-files.yaml)
- [NaftikoCapability — Files Behaviours](capabilities/ioc-investigation-ioc-investigation-files-behaviours.yaml)
- [NaftikoCapability — IP addresses](capabilities/ioc-investigation-ioc-investigation-ip-addresses.yaml)
- [NaftikoCapability — Popular Threat Categories](capabilities/ioc-investigation-ioc-investigation-popular-threat-categories.yaml)
- [NaftikoCapability — Search & Metadata](capabilities/ioc-investigation-ioc-investigation-search-metadata.yaml)
- [NaftikoCapability — URLs](capabilities/ioc-investigation-ioc-investigation-urls.yaml)
- [NaftikoCapability — Zipping files](capabilities/ioc-investigation-ioc-investigation-zipping-files.yaml)

### VirusTotal API v3 - Private Scanning
Submit files and URLs for analysis without sharing the artefact with the VT community. Premium tier.

**Human URL:** [https://docs.virustotal.com/reference/private-scanning](https://docs.virustotal.com/reference/private-scanning)

#### Tags
Threat Intelligence, Private Scanning, Premium, Sandbox

#### Properties
- [Documentation](https://docs.virustotal.com/reference/private-scanning)
- [OpenAPI](openapi/virustotal-private-scanning-openapi.yml)
- [NaftikoCapability — Analyses](capabilities/private-scanning-private-scanning-analyses.yaml)
- [NaftikoCapability — Files](capabilities/private-scanning-private-scanning-files.yaml)
- [NaftikoCapability — Files Behaviours](capabilities/private-scanning-private-scanning-files-behaviours.yaml)
- [NaftikoCapability — URLs](capabilities/private-scanning-private-scanning-urls.yaml)
- [NaftikoCapability — Zipping files](capabilities/private-scanning-private-scanning-zipping-files.yaml)

### VirusTotal API v3 - Threat Graphs
Create, share, edit, and search Threat Graphs — visualisations of how IoCs and threats relate.

**Human URL:** [https://docs.virustotal.com/reference/graphs](https://docs.virustotal.com/reference/graphs)

#### Tags
Threat Intelligence, Graphs, Collaboration

#### Properties
- [Documentation](https://docs.virustotal.com/reference/graphs)
- [OpenAPI](openapi/virustotal-threat-graphs-openapi.yml)
- [NaftikoCapability — Threat Graphs](capabilities/threat-graphs-threat-graphs.yaml)
- [NaftikoCapability — Permissions & ACL](capabilities/threat-graphs-threat-graphs-permissions-acl.yaml)

### VirusTotal API v3 - Threat Landscape & Vulnerability Intelligence
Collections, Threat Actors, Malware & Tools, Campaigns, Reports, Vulnerabilities, and the curated IoC catalogue.

**Human URL:** [https://docs.virustotal.com/reference/collections](https://docs.virustotal.com/reference/collections)

#### Tags
Threat Intelligence, Threat Actors, Malware Families, Campaigns, Vulnerabilities, Premium

#### Properties
- [Documentation](https://docs.virustotal.com/reference/collections)
- [OpenAPI](openapi/virustotal-threat-landscape-openapi.yml)
- [NaftikoCapability — Threat Landscape](capabilities/threat-landscape-threat-landscape-vulnerability-intelligence-reports-analysis.yaml)

### VirusTotal API v3 - YARA Hunting (Livehunt, Retrohunt, IoC Stream)
Livehunt, Retrohunt, IoC Stream, and crowdsourced YARA rules. Premium tier (writes); rule reads are free.

**Human URL:** [https://docs.virustotal.com/reference/livehunt](https://docs.virustotal.com/reference/livehunt)

#### Tags
Threat Intelligence, YARA, Hunting, Premium

#### Properties
- [Documentation](https://docs.virustotal.com/reference/livehunt)
- [OpenAPI](openapi/virustotal-yara-hunting-openapi.yml)
- [NaftikoCapability — IoC Stream](capabilities/yara-hunting-yara-hunting-ioc-stream.yaml)
- [NaftikoCapability — Livehunt](capabilities/yara-hunting-yara-hunting-livehunt.yaml)
- [NaftikoCapability — Retrohunt](capabilities/yara-hunting-yara-hunting-retrohunt.yaml)
- [NaftikoCapability — Rules](capabilities/yara-hunting-yara-hunting-rules.yaml)

### Google Threat Intelligence - Attack Surface Management (ASM)
Enterprise add-on (formerly Mandiant Advantage ASM).

**Human URL:** [https://gtidocs.virustotal.com/reference/openapi-specs](https://gtidocs.virustotal.com/reference/openapi-specs)

#### Properties
- [APIReference (OpenAPI JSON)](https://gtidocs.virustotal.com/openapi/asm-attack-surface-management.json)
- [Product Page](https://cloud.google.com/security/products/threat-intelligence)

### Google Threat Intelligence - Digital Threat Monitoring (DTM)
Enterprise add-on (formerly Mandiant Advantage DTM).

**Human URL:** [https://gtidocs.virustotal.com/reference/openapi-specs](https://gtidocs.virustotal.com/reference/openapi-specs)

#### Properties
- [APIReference (OpenAPI JSON)](https://gtidocs.virustotal.com/openapi/dtm-digital-threat-monitoring.json)
- [Product Page](https://cloud.google.com/security/products/threat-intelligence)

## Common Properties

### Documentation & Homepage
- [Website](https://www.virustotal.com)
- [Documentation](https://docs.virustotal.com/reference/overview)
- [API Reference (GTI)](https://gtidocs.virustotal.com/reference/overview)
- [GitHub Organization](https://github.com/VirusTotal)
- [Blog](https://blog.virustotal.com/)
- [Public APIs Listing](https://github.com/public-apis/public-apis)

### Official OpenAPI specs (upstream)
- [GTI API v3 Full Spec (official, 1.7 MB JSON)](https://storage.googleapis.com/gtidocresources/guides/GTI_API_v3_openapi_spec_10022025.json)
- [GTI ASM — Attack Surface Management](https://gtidocs.virustotal.com/openapi/asm-attack-surface-management.json)
- [GTI DTM — Digital Threat Monitoring](https://gtidocs.virustotal.com/openapi/dtm-digital-threat-monitoring.json)

### Official SDKs
- [Python SDK (vt-py)](https://github.com/VirusTotal/vt-py)
- [Go SDK (vt-go)](https://github.com/VirusTotal/vt-go)
- [Graph API Python (vt-graph-api)](https://github.com/VirusTotal/vt-graph-api)

### CLI
- [vt-cli — Official VirusTotal Command Line Interface (Go)](https://github.com/VirusTotal/vt-cli)

### MCP Servers (community)
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal)
- [alephnan/MCP-VirusTotal](https://github.com/alephnan/MCP-VirusTotal)
- [barvhaim/virustotal-mcp-server](https://github.com/barvhaim/virustotal-mcp-server)

### VirusTotal Developer Tools
- [YARA — the pattern matching swiss knife](https://github.com/VirusTotal/yara)
- [YARA-X (Rust rewrite)](https://github.com/VirusTotal/yara-x)
- [yara-python](https://github.com/VirusTotal/yara-python)
- [yara-x-benchmarks](https://github.com/VirusTotal/yara-x-benchmarks)
- [go-yara (Go bindings)](https://github.com/VirusTotal/go-yara)
- [protoc-gen-yara](https://github.com/VirusTotal/protoc-gen-yara)
- [CAPEv2 (Malware Configuration And Payload Extraction)](https://github.com/VirusTotal/CAPEv2)
- [vt-ida-plugin (IDA Pro plugin)](https://github.com/VirusTotal/vt-ida-plugin)
- [vt-windows-event-stream](https://github.com/VirusTotal/vt-windows-event-stream)
- [qt-virustotal-uploader (Qt desktop)](https://github.com/VirusTotal/qt-virustotal-uploader)

### Integrations
- [GTI Integration — Microsoft Defender](https://github.com/VirusTotal/gti-Microsoft-Defender)
- [GTI Integration — AWS GuardDuty](https://github.com/VirusTotal/gti-aws-GuardDuty)
- [GTI Integration — Google Secops SIEM](https://github.com/VirusTotal/gti-google-secops-siem)
- [GTI Integration — MISP](https://github.com/VirusTotal/gti-misp-connector)
- [GTI SOAR Playbooks](https://github.com/VirusTotal/gti-soar-playbooks)
- [GTI Integrations — User Guides](https://github.com/VirusTotal/GTI-Integrations-UserGuides)
- [GTI Developer Kit](https://github.com/VirusTotal/gti-dev-kit)

### Plans, Rate Limits, FinOps
- [Plans / Pricing (API Commons)](plans/virustotal-plans-pricing.yml)
- [Rate Limits (API Commons)](rate-limits/virustotal-rate-limits.yml)
- [FinOps (FOCUS)](finops/virustotal-finops.yml)

### Rules, Vocabulary, JSON-LD
- [Spectral Ruleset](rules/virustotal-rules.yml)
- [Vocabulary](vocabulary/virustotal-vocabulary.yml)
- [JSON-LD Context](json-ld/virustotal-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| File / URL / IP / Domain reports | Look up any IoC and pull aggregated AV verdicts, reputation, community votes, and the relationships graph. |
| Sandbox detonation | Submit files (up to 32 MB direct, 650 MB via signed URL); pull behaviour reports including processes, registry, network, MITRE techniques. |
| Private scanning | Premium-only — submit samples that are not shared with the VT community. |
| Livehunt | YARA rules that match in real time against the inbound corpus, with email and IoC Stream notifications. |
| Retrohunt | Run YARA scans across the historical corpus over a chosen time range and fetch matching files. |
| IoC Stream | Real-time notification stream from Livehunt / Retrohunt / Intel feeds — drain into SIEM / SOAR. |
| Intel Feeds | Per-minute and hourly batches of files, URLs, domains, IPs, and sandbox analyses for bulk ingestion. |
| Threat Landscape | Curated Threat Actors, Malware & Tools, Campaigns, Reports, Vulnerabilities (Mandiant-backed under GTI). |
| Threat Graphs | Visual graph of how IoCs relate, with editor / viewer ACLs for team collaboration. |
| Crowdsourced YARA | Community-contributed YARA rules visible against every file report. |
| MITRE ATT&CK mapping | Tactic and technique objects with relationships back to files, behaviours, and malware families. |

## Use Cases

| Name | Description |
|------|-------------|
| SOC alert triage | Hash, URL, or IP arrives in a SIEM alert; SOC analyst calls /files/{id} or /urls/{id} to get a verdict in seconds. |
| Incident response IoC enrichment | IR pulls every IoC in scope and the relationships graph to build the threat picture. |
| Detection engineering | Detection engineer authors a YARA ruleset, deploys to Livehunt, monitors notifications, and ports to in-line tooling once tuned. |
| Threat hunting | Threat researcher runs Retrohunt jobs against the corpus to find historical artefacts of a newly discovered TTP. |
| Threat intelligence enrichment | TI team consumes Threat Landscape collections (Actors, Malware, Campaigns) into MISP / their TIP. |
| Attack surface monitoring | Enterprise GTI customer uses ASM to discover and rate the org's external footprint. |
| Brand and credential monitoring | Enterprise GTI customer uses DTM to monitor open / deep / dark web for credential dumps and brand abuse. |
| Sample sharing pipeline | Malware analyst submits samples via vt-py / vt-cli, pulls behaviour, and archives via /intelligence/zip_files. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft Defender | GTI integration repo with playbooks for enriching Defender alerts. |
| AWS GuardDuty | GTI integration repo for cross-referencing GuardDuty findings against VT. |
| Google Secops SIEM | GTI integration repo for pumping VT signals into Google Secops. |
| MISP | GTI MISP connector pulls VT IoCs / Collections into a MISP instance. |
| SOAR platforms | GTI SOAR playbooks repository covering common orchestration patterns. |
| IDA Pro | Official VirusTotal plugin for IDA Pro reverse-engineering workflows. |
| Shuffle (open source SOAR) | Community Shuffle apps wrap the VT v3 API. |
| Microsoft Power Platform | Archived but historically-shipped Power Automate / Power Apps / Logic Apps connectors. |

## Solutions

| Name | Description |
|------|-------------|
| Security Operations Center (SOC) | Day-one triage, IoC enrichment, automated playbooks via IoC Stream and SOAR. |
| Incident Response (IR) | Relationships traversal, sandbox behaviour, threat-actor attribution, graph collaboration. |
| Threat Intelligence (TI) | Threat Landscape collections, IoC corpus search, custom collections, vulnerability tracking. |
| Threat Hunting / Detection Engineering | Livehunt + Retrohunt + crowdsourced YARA + sandbox behaviour feeds. |
| MSSP / Managed Detection | Multi-tenant via Groups + Service Accounts; per-key quota visibility for chargeback. |
| Enterprise Security (GTI) | Mandiant intelligence + DTM (dark web) + ASM (external attack surface). |

## Artifacts

Machine-readable API specifications organised by format.

### OpenAPI (7 specs, 206 operations across 33 tags)

- [VirusTotal API v3 — Access Control](openapi/virustotal-access-control-openapi.yml) (15 paths, 23 ops)
- [VirusTotal API v3 — IoC Feeds](openapi/virustotal-ioc-feeds-openapi.yml) (15 paths, 15 ops)
- [VirusTotal API v3 — IoC Investigation](openapi/virustotal-ioc-investigation-openapi.yml) (65 paths, 74 ops)
- [VirusTotal API v3 — Private Scanning](openapi/virustotal-private-scanning-openapi.yml) (28 paths, 30 ops)
- [VirusTotal API v3 — Threat Graphs](openapi/virustotal-threat-graphs-openapi.yml) (9 paths, 17 ops)
- [VirusTotal API v3 — Threat Landscape & Vulnerability Intelligence](openapi/virustotal-threat-landscape-openapi.yml) (10 paths, 16 ops)
- [VirusTotal API v3 — YARA Hunting](openapi/virustotal-yara-hunting-openapi.yml) (20 paths, 31 ops)

### JSON Schema (19 entities)

- File, URL, Domain, IP Address, Analysis, Comment, Vote, User, Group, Graph, Collection, FileBehaviour, LivehuntRuleset, RetrohuntJob, IocStreamNotification, AttackTactic, AttackTechnique, PopularThreatCategory, YaraRule — all under [`json-schema/`](json-schema/)

### JSON Structure (19 entities)

- Same 19 entities converted to JSON Structure (https://json-structure.org) — see [`json-structure/`](json-structure/)

### JSON-LD

- [VirusTotal Context](json-ld/virustotal-context.jsonld) — 19 type declarations, 167 property terms, schema.org / MITRE / dcterms alignments.

### Examples

- 19 example payloads under [`examples/`](examples/), one per JSON Schema entity.

### Plans, Rate Limits, FinOps

- [Plans / Pricing](plans/virustotal-plans-pricing.yml) — Public / Premium / GTI Enterprise tiers (API Commons Plans 0.1)
- [Rate Limits](rate-limits/virustotal-rate-limits.yml) — Public 4 req/min / 500 req/day; Premium per SLA; per-feature quotas (API Commons Rate Limits 0.1)
- [FinOps](finops/virustotal-finops.yml) — FOCUS 1.3 alignment, 9 meters (api_requests, livehunt_rulesets_active, livehunt_notifications, retrohunt_jobs, retrohunt_bytes_scanned, feed_downloads, private_scanning_submissions, zip_downloads, seats)

## Capabilities

Naftiko capabilities — one self-contained file per OpenAPI tag. Each file declares its `consumes` block plus REST and MCP exposers in one document.

### Access Control (4 capabilities)

- [Group Management](capabilities/access-control-access-control-group-management.yaml) — 12 ops
- [Quota Management](capabilities/access-control-access-control-quota-management.yaml) — 3 ops
- [Service Account Management](capabilities/access-control-access-control-service-account-management.yaml) — 3 ops
- [User Management](capabilities/access-control-access-control-user-management.yaml) — 5 ops

### IoC Feeds (5 capabilities)

- [Domain intelligence feed](capabilities/ioc-feeds-ioc-feeds-domain-intelligence-feed.yaml) — 2 ops
- [File intelligence feed](capabilities/ioc-feeds-ioc-feeds-file-intelligence-feed.yaml) — 3 ops
- [IP intelligence feed](capabilities/ioc-feeds-ioc-feeds-ip-intelligence-feed.yaml) — 2 ops
- [Sandbox analyses feed](capabilities/ioc-feeds-ioc-feeds-sandbox-analyses-feed.yaml) — 6 ops
- [URL intelligence feed](capabilities/ioc-feeds-ioc-feeds-url-intelligence-feed.yaml) — 2 ops

### IoC Investigation (12 capabilities)

- [Analyses, Submissions & Operations](capabilities/ioc-investigation-ioc-investigation-analyses-submissions-operations.yaml) — 5 ops
- [Attack Tactics](capabilities/ioc-investigation-ioc-investigation-attack-tactics.yaml) — 3 ops
- [Attack Techniques](capabilities/ioc-investigation-ioc-investigation-attack-techniques.yaml) — 3 ops
- [Comments](capabilities/ioc-investigation-ioc-investigation-comments.yaml) — 6 ops
- [Domains & Resolutions](capabilities/ioc-investigation-ioc-investigation-domains-resolutions.yaml) — 8 ops
- [Files](capabilities/ioc-investigation-ioc-investigation-files.yaml) — 14 ops
- [Files Behaviours](capabilities/ioc-investigation-ioc-investigation-files-behaviours.yaml) — 10 ops
- [IP addresses](capabilities/ioc-investigation-ioc-investigation-ip-addresses.yaml) — 7 ops
- [Popular Threat Categories](capabilities/ioc-investigation-ioc-investigation-popular-threat-categories.yaml) — 1 op
- [Search & Metadata](capabilities/ioc-investigation-ioc-investigation-search-metadata.yaml) — 4 ops
- [URLs](capabilities/ioc-investigation-ioc-investigation-urls.yaml) — 9 ops
- [Zipping files](capabilities/ioc-investigation-ioc-investigation-zipping-files.yaml) — 4 ops

### Private Scanning (5 capabilities)

- [Analyses](capabilities/private-scanning-private-scanning-analyses.yaml) — 4 ops
- [Files](capabilities/private-scanning-private-scanning-files.yaml) — 8 ops
- [Files Behaviours](capabilities/private-scanning-private-scanning-files-behaviours.yaml) — 10 ops
- [URLs](capabilities/private-scanning-private-scanning-urls.yaml) — 4 ops
- [Zipping files](capabilities/private-scanning-private-scanning-zipping-files.yaml) — 4 ops

### Threat Graphs (2 capabilities)

- [Threat Graphs](capabilities/threat-graphs-threat-graphs.yaml) — 9 ops
- [Permissions & ACL](capabilities/threat-graphs-threat-graphs-permissions-acl.yaml) — 8 ops

### Threat Landscape (1 capability)

- [Threat Landscape & Vulnerability Intelligence](capabilities/threat-landscape-threat-landscape-vulnerability-intelligence-reports-analysis.yaml) — 16 ops

### YARA Hunting (4 capabilities)

- [IoC Stream](capabilities/yara-hunting-yara-hunting-ioc-stream.yaml) — 4 ops
- [Livehunt](capabilities/yara-hunting-yara-hunting-livehunt.yaml) — 17 ops
- [Retrohunt](capabilities/yara-hunting-yara-hunting-retrohunt.yaml) — 6 ops
- [Rules](capabilities/yara-hunting-yara-hunting-rules.yaml) — 4 ops

**Total: 33 capability files, 206 operations.** Each capability declares one `rest` adapter (port 8080) and one `mcp` adapter (port 9090, http transport).

## Vocabulary

- [VirusTotal Vocabulary](vocabulary/virustotal-vocabulary.yml) — unified taxonomy mapping 21 resources, 14 actions, 19 schemas (across 6 domain buckets), 10 workflows, and 9 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [VirusTotal Spectral Ruleset](rules/virustotal-rules.yml) — ~38 opinionated rules covering info / metadata, OpenAPI version, servers, paths, operations, tags, parameters, request bodies, responses, schemas (snake_case + JSON:API object shape), security (VTApiKey via x-apikey header), HTTP method conventions, and general quality.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
