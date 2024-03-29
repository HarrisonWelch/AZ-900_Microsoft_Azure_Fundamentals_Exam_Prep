# Lecture 13 Elasticity Benefit of Cloud Computing

Elacticity

Mentioned in earlier video. This is the availability to quickly and easily scale up or down the amount of resources that a system uses in response to changing demand

Key: quickly and easily
* Has to involve some sort of automation
* Often called "Autoscaling" in cloud computing
* The system monitors some metric (CPU utilization) to determine how busy a system is
* Adds resources when it exceeds a limit for being busy
* Remove them when it falls below a certain limit

Why is it needed?
* More efficient and cost-effective use of resources
* Minimizes computing "waste" - resources paid for and not used
* Self-hosted systems tend to have a large percentage of "over-provisioned" resources for anticipated future growth
  * Plan 6-12 months to plan the growth out

Save Here, Spend There
* Also have the potential to have maximum capacity higher than you could afford if you had a static provisioning of resources.

Diagram of user demand vs capacity
* Cap is higher but moves in sine waves above the demand line\
* Fixed capacity would not scale. Point of failure, wait for demand to come back down.
