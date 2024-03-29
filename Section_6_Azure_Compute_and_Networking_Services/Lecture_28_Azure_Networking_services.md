# Lecture 28 Azure Networking services

Networking services
* Virtual Neworks
* VPN Gateway
* VNet Peering
* ExpressRoute

In AWS, a Virtual Network is called a Virtual Private Cloud (VPC)

Types of Networking Services
* Connectivity Services
* Protection Services
* Delivery Services
* Monitoring Services

Connectivity
* Virtual Network - emulating a phyiscal network
* MSGN (Global Network) - already exists, so a Virtual network is just a software config
* Subnet - a subdivision of a Virtual network, that you control, that has its own sec rules
* Virtual Private Network (VPN) - connecting to networks as if they were on the same network uses network gateway
* ExpressRoute - high speed priv connection to Azure
  * Encrypted means they wont understand but they a can still see it.
* DNS Services - domain name resolution
  * Domain name hosted in azure, DNS would route the request
  * Still need to register it in a registrar

Protection
* DDoS Protection - Distributed Denial of Service
* Firewall
* Network Sec Group
* Private Link

Delivery - Not on Exam
* Load Balancer - distribute traffic evenly between multiple servers
* Application Gateway - a higher-level of load balancer with an optional firewall
* Content Delivery Network (CDN) - stores common static files on the edge, closer to the users for (perceived) improved performance
* Azure Front Door Services - a load balancer, CDN, and firewall all in one.

Monitoring - Management Tools Section of the Course
* Network Watcher
  * Not on exam
* ExpressRoute Monitor
  * Not on exam
* Azure Monitor
  * Yes this is on the exam.
