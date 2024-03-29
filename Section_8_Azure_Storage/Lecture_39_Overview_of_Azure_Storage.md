# Lecture 39 Overview of Azure Storage

Next Category. Describe Azure storage services.

Azure services covered
* Blob
* Disk
* File
* Storage Tiers

Azure storage is a foundational technology

The Azure storage account
* General Purpose v2 (gpv2) is the most common type
* Blobs, Tables*, Queue*, Files
* Azure Data Lake Storage Gen2
* Cheapest type of storage
* Pay Per GB (~1.8 cents per GB)

Storage account is the cheapest

BLOB is a "Backronym" for Binary Large OBject

A colletion of binary data. That binary data could be in the form of a file (stored in a storage account) or data stored in a database.

In AWS a Storage Account is called Simple Storage Service (S3)

Many Many Options
* Access Tiers - Hot, Cool, Cold, Archive
* Performance Tiers - Standard or Premium
* Location
* Redundancy / Replication
* Failover options

Disk Storage
* Azure Virtual Machine Disks
* Managed Disks
  * Charged differently
  * Unmanaged - $/GB
  * Managed - Pay for full capacity
  * Optimized for block storage.
* Reserve capacity in advance
* Optimized to virtual hard disks
