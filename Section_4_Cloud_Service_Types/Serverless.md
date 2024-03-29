# Serverless

Bit of a buzzword

* Some services in Azure have a "Serverless" option
* Serverless is effectively a different pricing model
* Paying for service not renting hardware
* It's NO-server but really no-knowledge of a server. Not picking them.

Standard S-series
* Per month SQL DB access based on a simply measure

Vcore
* Cores your DB has, storage, memory
* Complicated but business want to separate out the limits to the S-series

Serverless
* One option - one price
* 4 different CPUs it __could__ use
* min and max CPU, Azure handles the needed amount
* Scales from 0.5 CPU to 80 CPUs
* Paying per CPU-second. 1/100 of a cent per CPU second. Much more difficult to calc. Can flucate
* Can spin down for zero cost.
* This can be the cheaper option for an underused DB.

Serverless Services
* Functions
  * 1 mil free function execution. Fraction of a penny per 10,000 exe after that.
* Container Apps
* Kubernetes
* SQL Database
* Cosmos DB
