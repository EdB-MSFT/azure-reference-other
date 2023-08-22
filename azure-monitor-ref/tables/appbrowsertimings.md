---
title: Azure Monitor Logs reference - AppBrowserTimings
description: Reference for AppBrowserTimings table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AppBrowserTimings

Application Insights browser timings.

## Categories

- Applications
## Solutions

- LogManagement
## Resource types

- Application Insights




## Columns

| Column | Type | Description |
|---|---|---|
| AppRoleInstance | string | Role instance of the application. |
| AppRoleName | string | Role name of the application. |
| AppVersion | string | Version of the application. |
| _BilledSize | real | The record size in bytes |
| ClientBrowser | string | Browser running on the client device. |
| ClientCity | string | City where the client device is located. |
| ClientCountryOrRegion | string | Country or region where the client device is located. |
| ClientIP | string | IP address of the client device. |
| ClientModel | string | Model of the client device. |
| ClientOS | string | Operating system of the client device. |
| ClientStateOrProvince | string | State or province where the client device is located. |
| ClientType | string | Type of the client device. |
| IKey | string | Instrumentation key of the Azure resource. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ItemCount | int | Number of telemetry items represented by a single sample item. |
| Measurements | dynamic | Application-defined measurements. |
| Name | string | Name of the page. |
| NetworkDurationMs | real | Page load network time in milliseconds. |
| OperationId | string | Application-defined operation ID. |
| OperationName | string | Application-defined name of the overall operation. The OperationName values typically match the Name values for AppRequests. |
| ParentId | string | ID of the parent operation. |
| ProcessingDurationMs | real | Page DOM processing time in milliseconds. |
| Properties | dynamic | Application-defined properties. |
| ReceiveDurationMs | real | Page load recieve response duration in milliseconds. |
| ResourceGUID | string | Unique, persistent identifier of an Azure resource. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SDKVersion | string | Version of the SDK used by the application to generate this telemetry item. |
| SendDurationMs | real | Send request time in milliseconds. |
| SessionId | string | Application-defined session ID. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| SyntheticSource | string | Synthetic source of the operation. |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Date and time when request was recorded. |
| TotalDurationMs | real | Page loading total time in milliseconds. |
| Type | string | The name of the table |
| Url | string | URI of the page view. |
| UserAccountId | string | Application-defined account associated with the user. |
| UserAuthenticatedId | string | Persistent string that uniquely represents each authenticated user in the application. |
| UserId | string | Anonymous ID of a user accessing the application. |
