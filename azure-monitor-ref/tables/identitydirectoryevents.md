---
title: Azure Monitor Logs reference - IdentityDirectoryEvents
description: Reference for IdentityDirectoryEvents table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# IdentityDirectoryEvents

Captures various identity-related events, like password changes, password expiration, and user principal name (UPN) changes.

## Categories

- Security
## Solutions

- SecurityInsights




## Columns

| Column | Type | Description |
|---|---|---|
| AccountDisplayName | string | Name of the account user displayed in the address book |
| AccountDomain | string | Domain of the account |
| AccountName | string | User name of the account |
| AccountObjectId | string | Unique identifier for the account in Azure AD |
| AccountSid | string | Security Identifier (SID) of the account |
| AccountUpn | string | User principal name (UPN) of the account |
| ActionType | string | Type of activity that triggered the event |
| AdditionalFields | dynamic | Additional information about the entity or event |
| Application | string | Application that performed the recorded action |
| _BilledSize | real | The record size in bytes |
| DestinationDeviceName | string | Name of the device running the server application that processed the recorded action |
| DestinationIPAddress | string | IP address of the device running the server application that processed the recorded action |
| DestinationPort | string | Destination port of related network communications |
| DeviceName | string | Fully qualified domain name (FQDN) of the device |
| IPAddress | string | IP address assigned to the endpoint and used during related network communications |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ISP | string | Internet service provider (ISP) associated with the endpoint IP address |
| Location | string | City, country, or other geographic location associated with the event |
| Port | string | TCP port used during communication |
| Protocol | string | Protocol used during the communication |
| ReportId | string | Unique identifier for the event |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TargetAccountDisplayName | string | Display name of the account that the recorded action was applied to |
| TargetAccountUpn | string | User principal name (UPN) of the account that the recorded action was applied to |
| TargetDeviceName | string | Fully qualified domain name (FQDN) of the device that the recorded action was applied to |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Date and time (UTC) when the record was generated |
| Type | string | The name of the table |
