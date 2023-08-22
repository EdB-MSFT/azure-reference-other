---
title: Azure Monitor Logs reference - UCDeviceAlert
description: Reference for UCDeviceAlert table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UCDeviceAlert

Update Compliance - These alerts are activated as a result of an issue that is device-specific, and is not specific to a specific update and a specific device. Like UpdateAlerts, the AlertType indicates where the Alert comes from (ServiceDeviceAlert, ClientDeviceAlert). For example, an EndOfService alert is a ClientDeviceAlert, as the fact it is on a build no longer being serviced (EOS) is a client-wide state. Meanwhile, DeviceRegistrationIssues in WUfB DS will be a ServiceDeviceAlert, as it is a device-wide state in the service to not be correctly registered.

## Solutions

- LogManagement
- WaaSUpdateInsights




## Columns

| Column | Type | Description |
|---|---|---|
| AlertClassification | string | Whether this Alert is an Error, a Warning, or Informational. |
| AlertData | string | An optional string formatted as a json payload containing metadata for the alert. |
| AlertId | string | The unique identifier of this Alert. |
| AlertRank | int | Integer ranking of Alert for prioritization during troubleshooting. |
| AlertStatus | string | Whether this Alert is Active, Resolved, or Deleted. |
| AlertSubtype | string | The Subtype of Alert. |
| AlertType | string | The type of Alert this is, ClientUpdateAlert, ServiceUpdateAlert. Indicates which fields will be present. |
| AzureADDeviceId | string | A GUID corresponding to the AAD Tenant to which the device belongs. |
| AzureADTenantId | string | A GUID corresponding to this device's AAD Device ID. |
| _BilledSize | real | The record size in bytes |
| Description | string | A localized string translated from a combination of other Alert fields + language preference that describes the issue in detail. |
| DeviceName | string | Device's given name. |
| ErrorCode | string | The Error Code, if any, that triggered this Alert. In the case of Client-based explicit alerts, error codes can have extended error codes, which are appended to the error code with a underscore separator. |
| ErrorSymName | string | The symbolic name that maps to the Error Code, if any. Otherwise empty. |
| GlobalDeviceId | string | Microsoft internal Global Device Identifier. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Recommendation | string | A localized string translated from RecommendedAction, Message, and other fields (depending on source of Alert) that provides a recommended action. |
| ResolvedTime | datetime | The time this alert was resolved, else empty. |
| SCCMClientId | string | A GUID corresponding to the SCCM Client ID on the device. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StartTime | datetime | The time this alert was activated. |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Time at which this event is generated and logged. |
| Type | string | The name of the table |
| URL | string | An optional URL to get more in-depth information related to this alert. |
