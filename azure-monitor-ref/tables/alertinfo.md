---
title: Azure Monitor Logs reference - AlertInfo
description: Reference for AlertInfo table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AlertInfo

Alerts from Microsoft Defender for Endpoint, Microsoft Defender for Office 365, Microsoft Cloud App Security, and Microsoft Defender for Identity, including severity information and threat categorization.

## Categories

- Security
## Solutions

- SecurityInsights




## Columns

| Column | Type | Description |
|---|---|---|
| AlertId | string | Unique identifier for the alert. |
| AttackTechniques | string | MITRE ATT&CK techniques associated with the activity that triggered the alert. |
| _BilledSize | real | The record size in bytes |
| Category | string | Type of threat indicator or breach activity identified by the alert. |
| DetectionSource | string | Detection technology or sensor that identified the notable component or activity. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ServiceSource | string | Product or service that provided the alert information. |
| Severity | string | Indicates the potential impact (high, medium, or low) of the threat indicator or breach activity identified by the alert. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Date and time (UTC) when the record was generated. |
| Title | string | Title of the alert. |
| Type | string | The name of the table |
