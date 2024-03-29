# Lecture 26 Azure Compute Services

Azure Compute section plus Networking

Number of options, not really a part of this course to explain why an option is best

Also talking about networking

Getting Deep into Technical
* Compute services
* Network
* Storage
* DB

2 of the top 4 sercies

Computer services offered
* Virtual Machine - VM
* VM Scale sets
* App sercies (Web apps)
* Azure Container Instances (ACI)
* Azure Kubernetes Service (AKS)
* Windows Virtual Desktop

Compute - "Executing Code" in the cloud
* Run your code in cloud
* End of day - running a program
* MS Word is a program for example. Running using the compute your personal computer.

Running something in the cloud utilizes the MS Cloud. They have millions of computer and pay for what you want/use.

Virtual Machine
* IaaS
* Take existing machine into the cloud
* Windows or Linux systems - several of each
* A "slice" of a physical machine shared with other customers
* Full control over it, as if it was your machine
* Virtual because you are given a slice.
* Ex: Renting an apartment of a building. Rent a portion with "full" control.
* Just as if you were working on a phyisical computer

In AWS, a VM is called an EC2

VM Types
* 700 possibilities to choose from (Oct 2023)
* Number of CPU cores, CPU speed, RAM size, disk size, IOPS, etc
* All of those combinations

VM Scale Sets
* 2 or more VMs that run the exact same code
* Website example
* With load balanceer in front to direct traffic randomly to one of the machines
* Able to add more machines as demand grows (autoscaling)
* Able to reduce machines as demand slows
* Can handle up to 100 VMs in a single scale set
* can be config to 1000 VMs
* If you need more, you can create more than 1 scale sets

App Services
* A new paradigm for running code in the cloud
* Give your code and config to Azure and they run it
* Promise of performance but your not in control of the hardware
* Platform as a Service (PaaS)

Containers
* Another paradigm for running code in the cloud
* Containers contain everything in the app needs to run in a container image
* Fastest and easiest to deploy
* ACI - Azure Container Instance - single instance, quickest way to deploy a container
* Azure Container Apps - easy to use like a web service, with advanced features
* AKS - Azure Kubernetes Service (AKS) - runs on a cluster of servers, enterprise-grade

Azure Virtual Desktop
* Desktop verison of Windows that runs in the cloud
* Your software install, your files - available from anywhere
* Can even see your desktop on iOS and Android, or from any browser
* Runs on Azure
* Windows that follows you around.

