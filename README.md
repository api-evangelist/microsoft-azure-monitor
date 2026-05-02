# Azure Monitor (microsoft-azure-monitor)
Azure Monitor helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/apis.yml)

## Tags:

 - Application Insights, Cloud, Logs, Metrics, Monitoring, Observability

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-28

## APIs

### Azure Monitor Metrics API
Provides access to Azure Monitor platform metric definitions and values for Azure resources, including performance counters, custom metrics, and time-series data.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported)

#### Tags:

 - Metrics, Performance, Resource Monitoring, Time Series

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/metrics)
- [OpenAPI](openapi/azure-monitor-metrics-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-metric-schema.json)
- [Authentication](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/rest-api-walkthrough)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/rest-api-walkthrough)

### Azure Monitor Metric Definitions API
Retrieves the list of available metric definitions for a given Azure resource, including metric names, units, aggregation types, and dimensions.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions](https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions)

#### Tags:

 - Definitions, Metadata, Metrics, Resource Monitoring

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions)
- [OpenAPI](openapi/azure-monitor-metric-definitions-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-metric-definition-schema.json)

### Azure Monitor Metrics Batch API
A high-volume API designed for retrieving metric values across multiple Azure resources in a single request. All resources in a batch must be in the same subscription and region.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch](https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch)

#### Tags:

 - Batch, High Volume, Metrics, Performance

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch)
- [OpenAPI](openapi/azure-monitor-metrics-batch-openapi.yml)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/migrate-to-batch-api)

### Azure Monitor Logs API
Query and retrieve log data from Azure Monitor Logs and Application Insights using the Kusto Query Language (KQL).

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview)

#### Tags:

 - Analytics, KQL, Logs, Query

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/loganalytics/)
- [OpenAPI](openapi/azure-monitor-logs-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-log-query-schema.json)
- [Query Language](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview)

### Azure Monitor Logs Ingestion API
Sends custom log data to a Log Analytics workspace using a REST API call or client libraries. Supports sending data to both supported Azure tables and custom tables via data collection rules and endpoints.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview)

#### Tags:

 - Custom Logs, Data Collection, Ingestion, Logs

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview)
- [OpenAPI](openapi/azure-monitor-logs-ingestion-openapi.yml)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-api)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-code)

### Azure Monitor Alerts API
Create, update, and manage alert rules and action groups for monitoring Azure resources. Supports metric alerts, log search alerts, and activity log alerts.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview)

#### Tags:

 - Action Groups, Alerts, Monitoring, Notifications

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/alertrules)
- [OpenAPI](openapi/azure-monitor-alerts-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-alert-rule-schema.json)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview)

### Azure Monitor Scheduled Query Rules API
Create and manage log search alert rules that automatically evaluate log queries at regular intervals and fire alerts when conditions are met.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules](https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules)

#### Tags:

 - Alerts, Automation, Log Search, Scheduled Query

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules)
- [OpenAPI](openapi/azure-monitor-scheduled-query-rules-openapi.yml)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-log-api-switch)

### Azure Monitor Action Groups API
Create and manage action groups that define notification and automation actions triggered by Azure Monitor alerts, including email, SMS, webhooks, and Azure Functions.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups)

#### Tags:

 - Action Groups, Automation, Notifications, Webhooks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/action-groups)
- [OpenAPI](openapi/azure-monitor-action-groups-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-action-group-schema.json)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups)

### Azure Monitor Autoscale API
Configure autoscale settings for Azure resources based on metric thresholds, schedules, or predictive rules to automatically adjust resource capacity.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview)

#### Tags:

 - Autoscale, Capacity Management, Performance, Scaling

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/autoscale-settings)
- [OpenAPI](openapi/azure-monitor-autoscale-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-autoscale-setting-schema.json)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-best-practices)

### Azure Application Insights API
Access Application Insights telemetry data including requests, dependencies, exceptions, traces, and custom events for application performance monitoring.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)

#### Tags:

 - APM, Application Performance, Telemetry, Tracing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/application-insights/)
- [OpenAPI](openapi/azure-monitor-application-insights-openapi.yml)
- [SDKs](https://learn.microsoft.com/en-us/azure/azure-monitor/app/api-custom-events-metrics)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-enable)

### Azure Monitor Diagnostic Settings API
Configure diagnostic settings to route platform logs and metrics from Azure resources to destinations such as Log Analytics workspaces, Storage Accounts, and Event Hubs.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings)

#### Tags:

 - Configuration, Diagnostics, Logs, Routing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/diagnostic-settings)
- [OpenAPI](openapi/azure-monitor-diagnostic-settings-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-diagnostic-setting-schema.json)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings)

### Azure Monitor Activity Log API
Access Azure Activity Log events for subscription-level operations including resource creation, updates, deletions, and administrative actions.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log)

#### Tags:

 - Activity Log, Audit, Compliance, Events

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/activity-logs)
- [OpenAPI](openapi/azure-monitor-activity-log-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-activity-log-event-schema.json)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log-schema)

### Azure Monitor Data Collection Rules API
Create and manage data collection rules that define how data is collected, transformed, and routed to destinations within Azure Monitor.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-overview)

#### Tags:

 - Configuration, Data Collection, Ingestion, Rules

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/data-collection-rules)
- [OpenAPI](openapi/azure-monitor-data-collection-rules-openapi.yml)
- [JSONSchema](json-schema/azure-monitor-data-collection-rule-schema.json)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-create-edit)

### Azure Monitor Data Collection Endpoints API
Create and manage data collection endpoints that provide unique ingestion and configuration endpoints for data collection in Azure Monitor.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview)

#### Tags:

 - Configuration, Data Collection, Endpoints, Ingestion

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/data-collection-endpoints)
- [OpenAPI](openapi/azure-monitor-data-collection-endpoints-openapi.yml)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview)

### Azure Monitor Private Link Scopes API
Create and manage Azure Monitor Private Link Scopes to connect Azure Monitor resources to private endpoints, enabling secure network access to monitoring data.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-security](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-security)

#### Tags:

 - Configuration, Networking, Private Link, Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/monitor/private-link-scopes)
- [OpenAPI](openapi/azure-monitor-private-link-scopes-openapi.yml)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-configure)
- [Reference](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-design)

## Common Properties

- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/azure-monitor/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-monitor/overview)
- [Authentication](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/access-api)
- [Blog](https://azure.microsoft.com/en-us/blog/topics/monitor/)
- [Change Log](https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/whats-new)
- [SDKs](https://learn.microsoft.com/en-us/azure/azure-monitor/app/platforms)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/monitor/)
- [Status](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://azure.microsoft.com/en-us/explore/trusted-cloud/privacy)
- [GitHub Organization](https://github.com/Azure)
- [Community](https://techcommunity.microsoft.com/t5/azure-monitor/bd-p/AzureMonitor)
- [Website](https://azure.microsoft.com/en-us/products/monitor)
- [Login](https://portal.azure.com)
- [Sign Up](https://azure.microsoft.com/en-us/free)
- [JSON-LD](json-ld/azure-monitor-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
