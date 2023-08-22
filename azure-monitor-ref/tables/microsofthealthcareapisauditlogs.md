---
title: Azure Monitor Logs reference - MicrosoftHealthcareApisAuditLogs
description: Reference for MicrosoftHealthcareApisAuditLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# MicrosoftHealthcareApisAuditLogs

Azure API for FHIR audit logs

## Categories

- Azure Resources
- Audit
## Solutions

- LogManagement
## Resource types

- Azure API for FHIR




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| CallerIdentity | dynamic | The caller's identity. |
| CallerIdentityIssuer | string | The JWD token Issuer. |
| CallerIdentityObjectId | string | The AAD object ID. |
| CallerIPAddress | string | The IP address of the caller. |
| CorrelationId | string | The correlation id of the request. |
| FhirResourceType | string | The resource type the operation was executed for. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Location | string | The location of the server that processed the request (e.g., South Central US). |
| LogCategory | string | The audit event category. |
| OperationDuration | int | The duration of the operation in ms. |
| OperationName | string | The name of the operation represented by this event. |
| Properties | dynamic | Additional properties. |
| RequestUri | string | The URI of the request. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultType | string | The result type. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StatusCode | int | The HTTP status code. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of the log. |
| Type | string | The name of the table |
