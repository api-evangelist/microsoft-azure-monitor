# Azure Monitor (microsoft-azure-monitor)

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
