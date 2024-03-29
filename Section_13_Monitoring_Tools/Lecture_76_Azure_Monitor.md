# Lecture 76 Azure Monitor

Azure Monitor
* See all of the storage accounts together
* E2E latency
  * Download time
* Server latency on first connection

Logs section
* Run query
* Storage accounts
* Built-in reports here
  * Show anonymous requests
  * Operations with the high latency

KQL - Kusto Query Language

```kql
StorageBlobLogs
    WHERE TimeGenerated > ago(3d)
    top 10 by DurationMs
    project TimeGenerated, OperationName, DurationMs, ServerLatencyMs, ClientLatencyMs = DurationMs - ServerLatencyMs
```

Show anonymous requests
* built-in query

All the data is anonymous

Preset query and modify for your relevance

Virtual Machine
* AzureActivity
* View all then. 
* Can see which resource group was used.

Can write elaborate queries or use pre-mades.

### Workbooks
* Built up a set of reports
* Share them with others
* Custom set of really good metrics

