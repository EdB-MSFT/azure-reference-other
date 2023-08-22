---
title: Azure Monitor Logs reference - AWSVPCFlow
description: Reference for AWSVPCFlow table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AWSVPCFlow

VPC Flow Logs, which ingested from Sentinel's connector, enables you to capture IP traffic going to and from your AWS VPC network interfaces.

## Categories

- Security
## Solutions

- SecurityInsights




## Columns

| Column | Type | Description |
|---|---|---|
| AccountId | string | The AWS account ID of the owner of the source network interface for which traffic is recorded. If the network interface is created by an AWS service, for example when creating a VPC endpoint or Network Load Balancer, the record may display unknown for this field. |
| Action | string | The action that is associated with the traffic. |
| AzId | string | The ID of the Availability Zone. |
| _BilledSize | real | The record size in bytes |
| Bytes | long | The number of bytes transferred during the flow. |
| DstAddr | string | The destination address for outgoing traffic. |
| DstPort | int | The destination port of the traffic. |
| End | datetime | The time when the last packet of the flow was received within the aggregation interval. |
| FlowDirection | string | The direction of the flow with respect to the interface where traffic is captured. |
| InstanceId | string | The ID of the instance that's associated with network interface for which the traffic is recorded. |
| InterfaceId | string | The ID of the network interface for which the traffic is recorded. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LogStatus | string | The logging status of the flow log. |
| Packets | int | The number of packets transferred during the flow. |
| PktDstAddr | string | The packet-level (original) destination IP address for the traffic. |
| PktDstAwsService | string | The name of the subset of IP address ranges for the PktDstAddr field, if the destination IP address is for an AWS service. |
| PktSrcAddr | string | The packet-level (original) source IP address of the traffic. |
| PktSrcAwsService | string | The name of the subset of IP address ranges for the PktSrcAddr field, if the source IP address is for an AWS service. |
| Protocol | int | The IANA protocol number of the traffic. |
| Region | string | The Region that contains the network interface for which traffic is recorded. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SrcAddr | string | The source address for incoming traffic. |
| SrcPort | int | The source port of the traffic. |
| SublocationId | string | The ID of the sublocation that contains the network interface for which traffic is recorded. |
| SublocationType | string | The type of sublocation that is returned in the sublocationId field. |
| SubnetId | string | The ID of the subnet. |
| TcpFlags | int | The bitmask value for the following TCP flags. |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of when the event was generated. This value will be the same as 'start' input field or the data arrival time to Azure Monitor in case the 'start' input field is empty or missing. |
| TrafficPath | string | The path that egress traffic takes to the destination. |
| TrafficType | string | The type of traffic. The possible values are: IPv4, IPv6, and EFA. For more information search for 'Elastic Fabric Adapter (EFA)'. |
| Type | string | The name of the table |
| Version | int | The VPC Flow Logs version. |
| VpcId | string | The ID of the VPC. |
