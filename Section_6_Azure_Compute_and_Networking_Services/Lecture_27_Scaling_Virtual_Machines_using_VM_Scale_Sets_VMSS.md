# Lecture 27 Scaling Virtual Machines using VM Scale Sets VMSS

* You can increase the size of a VM easily, turning a 4 vCPU into an 8 vCPU VM in minutes (scale up)
  * Can go to 64 vCPUs or higher
    * Some fam have 96
    * Some have 120, but thats it
* Or you can add more VMs and have them work together to handle the work (scale out)
  * Not really a limit

Virtual Machine Scale Set
* A group of virtual Machines that can grow and shrink in quantity based on a predefined rule
* Usually based on monitoring demand
* Can be based on time (Schedule)
  * Day shift
* Can be based on many other factors
  * Queue length or quantity of queues used

VM Scale Sets
* Elasticity
* Two or more VMs running the exact same code
* With a "load" balancer in front to direct traffic randomly to one of the machines
* Able to add more machines as demand grows (autoscalig)
* Able to reduce machines as demand slows
* Can handles up to 100 VMs in 1 scale set, can be configured to handle 1000
* Can add more scale sets.
  * Bump against subscription-wide limits

