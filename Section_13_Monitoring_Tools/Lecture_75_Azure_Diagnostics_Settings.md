# Lecture 75 Azure Diagnostics Settings

Last topic of Azure Monitor

Monitor all sorts of Az resources in one location
* Applications
* Storage
* etc

Not every type of resource is here

There is a process of getting data into Azure Monitor for queries.

"az900course" storage account

Monitoring -> Alerts
* Create Alert rule

Metrics
* Report of data exiting over the past 24 hours

Once you have report you like.
* Save to Dashboard in the top right and then "Pin to dashboard"

Back to alerts
* Larger than 10GiB/hr
* Data
* Period
* Evaluate per 15 mins
* 10 cents per rule

Diagnostic settings
* Diagnostic logs
* Read, Write, Delete, Transaction

Add settings
* Give it a name
* Logs
  * StorageRead
  * StorageWrite
  * StorageDelete
* Metrics
  * Transaction

4 options of output

Destination details
* Archive to storage account
* Send to Log Analytics Workspace
  * This is important to Azure Diagnostics
  * Choose sub and LogAnalytics workspace
* Send to Partner
  * 3rd party is going to dig through the dianostics
* Stream to event hub
  * Go into an analytics solution for real time processing

Save with just the Log Analytics workspace
* Lag between turning on diagnostics and running queries against the diagnostics data.

Azure changes the diagnostics view and makes the "classic view" available to some Azure accts still.

App services can also have diagnotics settings against each one
* Same with VMs
* Same with a ton of other services.
