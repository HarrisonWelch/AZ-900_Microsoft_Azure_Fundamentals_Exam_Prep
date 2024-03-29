# High Availability Benefit of Cloud Computing

2nd objective of Cloud Concepts

Include
* Availability
* Scale
* Elastic
* Reliable
* Predictable
* Secure
* Governable
* Manageable

High Available (HA)
* Ability of a system to remain operational during planned or unplanned outages

24/7 all 365 days is 100%.

No one truely has 100% uptime. Everyone has intermissions.

Planned Outages
* OS security patches
* Application updates
* Hardware replacement
* Migrating to a new hosting provider

These are all predictable. Control the window - 3am on a Sat night...

Unplanned Outages:
* Hardware failure
* Network disruptions
* Power outages
* Natural disaster (Tornado, Fire)
* Cyber attackes
* Software bugs
* Poor scaling / architecture design.

Methods to Mitigate Planned Outages
* Gradual deployment strategy
  * 1-10-100-etc
  * Facebook exmaple. Deploy to 1 server, then 10, etc. Until its fully rolled out
* Testing and monitoring of deployment
  * Stop deployment if adverse expect. File missing and corrupt file
* Easy rollback plan
  * Mitigate damage of failed deploy.
* Small deployment
  * If you have less features, less things to go wrong
* More frequent deployment
  * Everyday means the chances are very low
* Automation
  * Reduce manual interferance
  * DevOps

Methods to Mitigate Unplanned Outages
* Everyone single core component has redundancy
* Use Azure's built-in features for availability
  * Availability Sets
  * Availability Zones
  * Cross-Region Load Balancing / Front Door
* Constant Health Monitoring / Probes
  * Don't wait - be proactive
* Automation
  * Reboot
  * Add additional servers
  * Fallback strategy

Methods to Mitigate Unplanned Outages continued
* Security practices
  * 2FA
  * No Hackers
* Geographically distributed
  * If a disaster happened or power outage - this is removed, they takeover while bad region recovers
* Disaster recovery plan
  * Fire evacuation plan
  * If there is a fire alarm. Warden on the floor and meet at the big tree.
  * This is like a fire escape plan
* Test the disaster plan
  * Like a fire drill!
* Load testing
  * Too popular means shutting down
  * 100s of concurrent users
  * Find the limit
  * Could spur you to fix the bottleneck

High-Availability Is...
* A conscious effort to avoid the obvious sources of downtime

