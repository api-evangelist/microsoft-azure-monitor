# Azure Monitor (microsoft-azure-monitor)

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

Azure Monitor helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.

**APIs.json:** [https://azure.microsoft.com/en-us/services/monitor/](https://azure.microsoft.com/en-us/services/monitor/)

## Tags

- Application Insights
- Cloud
- Logs
- Metrics
- Monitoring
- Observability

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Azure Monitor Metrics API

Provides access to Azure Monitor platform metric definitions and values for Azure resources, including performance counters, custom metrics, and time-series data.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported)
- **Base URL:** `https://management.azure.com`

#### Tags

- Metrics
- Performance
- Resource Monitoring
- Time Series

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/metrics)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metrics_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-metrics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-metric-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/rest-api-walkthrough)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/rest-api-walkthrough)

### Azure Monitor Metric Definitions API

Retrieves the list of available metric definitions for a given Azure resource, including metric names, units, aggregation types, and dimensions.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions](https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions)
- **Base URL:** `https://management.azure.com`

#### Tags

- Definitions
- Metadata
- Metrics
- Resource Monitoring

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metricDefinitions_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-metric-definitions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-metric-definitions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-metric-definitions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-metric-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Azure Monitor Metrics Batch API

A high-volume API designed for retrieving metric values across multiple Azure resources in a single request. All resources in a batch must be in the same subscription and region.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch](https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch)
- **Base URL:** `https://management.azure.com`

#### Tags

- Batch
- High Volume
- Metrics
- Performance

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch)
- [OpenAPI](openapi/azure-monitor-metrics-batch-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-metrics-batch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-metrics-batch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/migrate-to-batch-api)

### Azure Monitor Logs API

Query and retrieve log data from Azure Monitor Logs and Application Insights using the Kusto Query Language (KQL).

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview)
- **Base URL:** `https://api.loganalytics.io`

#### Tags

- Analytics
- KQL
- Logs
- Query

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/loganalytics/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/operationalinsights/data-plane/Microsoft.OperationalInsights/stable/2022-10-27/OperationalInsights.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-logs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-log-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Query  Language](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview)

### Azure Monitor Logs Ingestion API

Sends custom log data to a Log Analytics workspace using a REST API call or client libraries. Supports sending data to both supported Azure tables and custom tables via data collection rules and endpoints.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview)
- **Base URL:** `https://management.azure.com`

#### Tags

- Custom Logs
- Data Collection
- Ingestion
- Logs

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview)
- [OpenAPI](openapi/azure-monitor-logs-ingestion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-logs-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-logs-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-api)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-code)

### Azure Monitor Alerts API

Create, update, and manage alert rules and action groups for monitoring Azure resources. Supports metric alerts, log search alerts, and activity log alerts.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview)
- **Base URL:** `https://management.azure.com`

#### Tags

- Action Groups
- Alerts
- Monitoring
- Notifications

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/alertrules)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2016-03-01/alertRules_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-alerts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-alerts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-alerts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-alert-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview)

### Azure Monitor Scheduled Query Rules API

Create and manage log search alert rules that automatically evaluate log queries at regular intervals and fire alerts when conditions are met.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules](https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules)
- **Base URL:** `https://management.azure.com`

#### Tags

- Alerts
- Automation
- Log Search
- Scheduled Query

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-08-01/scheduledQueryRule_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-scheduled-query-rules-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-scheduled-query-rules.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-scheduled-query-rules.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-log-api-switch)

### Azure Monitor Action Groups API

Create and manage action groups that define notification and automation actions triggered by Azure Monitor alerts, including email, SMS, webhooks, and Azure Functions.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups)
- **Base URL:** `https://management.azure.com`

#### Tags

- Action Groups
- Automation
- Notifications
- Webhooks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/action-groups)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-06-01/actionGroups_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-action-groups-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-action-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-action-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-action-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups)

### Azure Monitor Autoscale API

Configure autoscale settings for Azure resources based on metric thresholds, schedules, or predictive rules to automatically adjust resource capacity.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview)
- **Base URL:** `https://management.azure.com`

#### Tags

- Autoscale
- Capacity Management
- Performance
- Scaling

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/autoscale-settings)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-10-01/autoscale_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-autoscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-autoscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-autoscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-autoscale-setting-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-best-practices)

### Azure Application Insights API

Access Application Insights telemetry data including requests, dependencies, exceptions, traces, and custom events for application performance monitoring.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)
- **Base URL:** `https://api.applicationinsights.io`

#### Tags

- APM
- Application Performance
- Telemetry
- Tracing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/application-insights/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/applicationinsights/data-plane/Microsoft.Insights/stable/v1/AppInsights.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-application-insights-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-application-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-application-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [S D Ks](https://learn.microsoft.com/en-us/azure/azure-monitor/app/api-custom-events-metrics)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-enable)

### Azure Monitor Diagnostic Settings API

Configure diagnostic settings to route platform logs and metrics from Azure resources to destinations such as Log Analytics workspaces, Storage Accounts, and Event Hubs.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings)
- **Base URL:** `https://management.azure.com`

#### Tags

- Configuration
- Diagnostics
- Logs
- Routing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/diagnostic-settings)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-05-01-preview/diagnosticsSettings_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-diagnostic-settings-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-diagnostic-settings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-diagnostic-settings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-diagnostic-setting-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings)

### Azure Monitor Activity Log API

Access Azure Activity Log events for subscription-level operations including resource creation, updates, deletions, and administrative actions.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log)
- **Base URL:** `https://management.azure.com`

#### Tags

- Activity Log
- Audit
- Compliance
- Events

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/activity-logs)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2015-04-01/activityLogs_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-activity-log-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-activity-log.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-activity-log.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-activity-log-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log-schema)

### Azure Monitor Data Collection Rules API

Create and manage data collection rules that define how data is collected, transformed, and routed to destinations within Azure Monitor.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-overview)
- **Base URL:** `https://management.azure.com`

#### Tags

- Configuration
- Data Collection
- Ingestion
- Rules

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/data-collection-rules)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionRules_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-data-collection-rules-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-data-collection-rules.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-data-collection-rules.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-monitor-data-collection-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-create-edit)

### Azure Monitor Data Collection Endpoints API

Create and manage data collection endpoints that provide unique ingestion and configuration endpoints for data collection in Azure Monitor.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview)
- **Base URL:** `https://management.azure.com`

#### Tags

- Configuration
- Data Collection
- Endpoints
- Ingestion

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/data-collection-endpoints)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionEndpoints_API.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-monitor-data-collection-endpoints-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-data-collection-endpoints.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-data-collection-endpoints.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview)

### Azure Monitor Private Link Scopes API

Create and manage Azure Monitor Private Link Scopes to connect Azure Monitor resources to private endpoints, enabling secure network access to monitoring data.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-security](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-security)
- **Base URL:** `https://management.azure.com`

#### Tags

- Configuration
- Networking
- Private Link
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/private-link-scopes)
- [OpenAPI](openapi/azure-monitor-private-link-scopes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-monitor-private-link-scopes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-monitor-private-link-scopes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-configure)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-design)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/azure-monitor/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/overview)
- [Authentication](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/access-api)
- [Blog](https://azure.microsoft.com/en-us/blog/topics/monitor/)
- [Changelog](https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/whats-new)
- [S D Ks](https://learn.microsoft.com/en-us/azure/azure-monitor/app/platforms)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/monitor/)
- [Status Page](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://azure.microsoft.com/en-us/explore/trusted-cloud/privacy)
- [GitHub Organization](https://github.com/Azure)
- [Community](https://techcommunity.microsoft.com/t5/azure-monitor/bd-p/AzureMonitor)
- [Website](https://azure.microsoft.com/en-us/products/monitor)
- [Login](https://portal.azure.com)
- [Sign Up](https://azure.microsoft.com/en-us/free)
- [JSON-LD](json-ld/azure-monitor-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
