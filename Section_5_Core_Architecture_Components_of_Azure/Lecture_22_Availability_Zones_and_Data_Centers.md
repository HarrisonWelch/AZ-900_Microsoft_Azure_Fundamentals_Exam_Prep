# Lecture 22 Availability Zones and Data Centers

Availability zones are datacenters or sets of DCs that are physcially seperate location within each Azure region.

Canada East as a zone, there are multiple available zone
* Own power
* Own cooling
* Own internet connection
* Own "Infrastructure"

Not every region support availability zones

Example Regions with AZ
* Americas
  * Brazil South
  * Canada Central
  * Central US, East US
  * etc.
* EU
  * France Central
  * etc.
* Middle East
  * Quatar
  * UAE North
* Africa
  * South Africa North
* Asia Pacific
  * Australia East
  * etc.

Not every service supports AZs

Three types of AZ Services
* Zonal Services
* Zone Redundant Services
* Always available Services

Zonal Services
* Deploy to a specifc zone (option)
* Why? to have your resources in that region
* Duplicate should be deployed to another region
* Eg: Virtual Machines

Zone Redundant Services
* Auto deployed across zones for you
* You don't have to manage this
* Ex: Azure SQL database

Always-Available (Global) Services
* MS runs them global
* Ensure availability
  * If any AZ goes down, they will not be affected
* Non-Regional services
  * Azure Portal
  * Azure Active Directory

Some services give you the choice between zonal and zone-redundant

