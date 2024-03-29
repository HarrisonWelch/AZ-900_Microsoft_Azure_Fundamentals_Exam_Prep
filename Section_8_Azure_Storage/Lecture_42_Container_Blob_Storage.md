# Lecture 42 Container Blob Storage

Blob or "Container storage"

### Binary Large Object
* Any type of file: (TXT, PDF, ZIP, CSV, XLSX, JPG, AVI,... etc)
* Stored loosely
* Public private
* No structure to it

### Container Storage
* Create multiple containers
* Each container can contain blobs
* Can be organized into folders (yes and no)
* Only pay for what you use

A storage account in AWS is called S3

### Location
* You can create multiple storage accounts in any region of the world
* Keep your data close to the person/service consuming it (for access speed reasons)
* Price varies by region

### Redundancy
* Azure keeps 3 copies of your data by default
* Locally- or zone-redundant
* Azure will almost never, ever lose a file once it's successfully received it

### Global Redundancy
* You can choose global redundancy for storage
* Azure keeps 6 copies of your data
* 3 locally, and 3 in another region of the "geo"
* Honors data sovereignty laws

### Access Tiers
* For access tiers
  * Hot - default, balanced access
  * Cool - can be set as default, cheaper storage with more expensive read/write operations
  * Cold - much cheaper storage, more expensive read/write ops
  * Archive - cannot get immediate to files, cheapest storage, most expensive operations
    * Good to for data to legally work 
    * "Thaw" data

###  Failover
* Hard disks fail every so often
* Azure takes care of this without you doing anything
* 3 copies of your data, they can recreate a hard disk behind the scenes.
