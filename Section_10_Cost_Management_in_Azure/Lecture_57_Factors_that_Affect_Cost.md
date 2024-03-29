# Lecture 57 Factors that Affect Cost

Last Objective of this exam. Describe Azure management and governance.
* Cost
* Compliance and Gove
* Tools
* Monitoring

This section is just cost

Recap from the top of the course.

Diff services are billed based on different factors

Free services
* Resource Groups
* Virtual Network (up to 50)
* Load Balancer (Basic)
* Azure Active Directory (Basic)
* Network security groups
* Free-tier web apps (up to 10)

Rest of azure has some type of metrics being tracked: time, execution, data, etc.

More you use, more you pay.

Opportunity for cost savings, Azure Functions:
* 1 million executions free per month
* $0.20 per million executions
* Cheapest virtual machine is $20 per month

Pay per usage
* Functions
* Logic apps
* Storage (up to 65 GB)
* Outbound bandwidth
* Cognitive Services API

Per for time (per second)
* billing stops with the VM is stopped
* Keep in mind they take time to start and stop and that is included
* Finite duration usually

Stability in pricing
* Pay a fixed price per month for computing power or storage capacity
* Whether you use it or not
* Discounts for 1-year or 3-year commitment in VM (Reserved instances)

Multi-tenant or isolated environment

Pay for bandwidth
* First 5 GB is free
* Inbound is free. MS wants you to use their services

Bandwidth costs:
* Outbound data, 0.05 to 0.0875 / GB for Zone 1 (NA and EU)
* Outbound data, 0.08 to 0.12 / GB for Zone 2 (Asia, Africa, and Oceania)
* Outbound data, 0.16 to 0.181 / GB for Zone 3 (Brazil)

(Availability zone pricing is different)

1 PB of data transfer = $52,000 in data transfer charges (Example)

- Hard to move data out of Azure into AWS.
