---
ms.service: azure-monitor
ms.topic: include
ms.date: 02/19/2024
ms.author: edbaynash
author: EdB-MSFT
ms.custom: Microsoft.ConnectedCache/enterpriseMccCustomers, naam

# NOTE:  This content is automatically generated using API calls to Azure. Any edits made on these files will be overwritten in the next run of the script. 
 
---


|Metric|Name in REST API|Unit|Aggregation|Dimensions|Time Grains|DS Export|
|---|---|---|---|---|---|---|
|**Egress Mbps**<br><br>Egress Throughput |`egressbps` |BitsPerSecond |Average |`cachenodeid`|PT1M |Yes|
|**Hit Ratio**<br><br>Cache hit ratio is a measurement of how many content requests a cache is able to fill successfully, compared to how many requests it receives. |`hitRatio` |Percent |Average |`cachenodeid`|PT1M |Yes|
|**Hits**<br><br>Count of hits |`hits` |Count |Count |`cachenodeid`|PT1M |Yes|
|**Hit Mbps**<br><br>Hit Throughput |`hitsbps` |BitsPerSecond |Average |`cachenodeid`|PT1M |Yes|
|**Inbound**<br><br>Inbound Throughput |`inboundbps` |BitsPerSecond |Average |`cachenodeid`|PT1M |Yes|
|**Misses**<br><br>Count of misses |`misses` |Count |Count |`cachenodeid`|PT1M |Yes|
|**Miss Mbps**<br><br>Miss Throughput |`missesbps` |BitsPerSecond |Average |`cachenodeid`|PT1M |Yes|
|**Outbound**<br><br>Outbound Throughput |`outboundbps` |BitsPerSecond |Average |`cachenodeid`|PT1M |Yes|