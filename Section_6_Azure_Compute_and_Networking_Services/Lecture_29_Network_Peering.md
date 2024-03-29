# Lecture 29 Network Peering

Virtrual Networks in Azure are pretty secure things

"vnetdemo1"
* Address space 10.0.0.0/16
  * 16 is range
  * starting at 10.0.0.0
  * range to 10.0.255.255
* Subnets
  * Used /24 subnet as the defount
  * Can simply create a new subnet
  * Subnet address can only go up to 251 b/c Azure reserves the ones higher

Resource group
* Vnet1 needs to talk to Vnet2
* By default this is blocked
* What you have to do is:
  * "Peering"
  * Scroll to settings for Peering
  * Set 1way or 2way traffic
* name it (ex: vnet1-to-vnet2)
* name the return traffic. Can be different (ex: vnet2-to-vnet1)
* Now we can talk, IP addresses will be able to resolve
* 10.0.0.0 <=> 10.0.1.0 network

Peering allows two networks to talk to each other

Note you have to pay ingress an egress charges which might be in different countries
