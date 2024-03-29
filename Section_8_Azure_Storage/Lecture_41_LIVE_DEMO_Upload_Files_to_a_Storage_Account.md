# Lecture 41 LIVE DEMO Upload Files to a Storage Account

![Alt text](image-7.png)

Go to Resource

![Alt text](image-8.png)

Contains 4 types of data
* Containers
* File shares
* Queues
  * One to put in
  * One to pull out
* Tables
  * effectively DB, not as reliable as a Cosmos DB

![Alt text](image-21.png)

Create new storage container

Add some files

Can make the storage hot or cold on these files

Can tag it

Leave all the defaults

![Alt text](image-20.png)

Upload

![Alt text](image-19.png)

Not only the way to access a storage account (explorer in the next video)

Remember storage acct are accessible to the internet

Properties has the fully qualified name

![Alt text](image-18.png)

Problem is you need a security key in order to access it.

Pasting the URL in the search bar will yeild

![Alt text](image-9.png)

We need the security key

Back out to the container level, then in "Security + networking"

Storage keys are hidden by default. Keys need to be kept private. Very sensative.

![Alt text](image-17.png)

You could also generate SAS or "Shared access signature" on a specific resource

![Alt text](image-10.png)

![Alt text](image-11.png)

Example URL:
```
https://storagedemo2924.blob.core.windows.net/firstone/space1.png?sp=r&st=2024-02-09T17:08:25Z&se=2024-02-10T01:08:25Z&spr=https&sv=2022-11-02&sr=b&sig=3Y8GPwlMRN3B2Nxc8ir098u%2FQiTwNWpvFuJ0sOETjRM%3D
```

which does indeed get you the photo accessed

![Alt text](image-12.png)

Storage accounts have lots of optional tools

Redundancy - Map View

![Alt text](image-13.png)

Lifecycle management

You can automate the push of hot to cool and from cool to hot

New Rule:

![Alt text](image-14.png)

Base blobs:

![Alt text](image-15.png)

You can also move to archive as seen here:

![Alt text](image-16.png)

This will effectively take it offline where it can take hours to access

Storage explorer in the next video
