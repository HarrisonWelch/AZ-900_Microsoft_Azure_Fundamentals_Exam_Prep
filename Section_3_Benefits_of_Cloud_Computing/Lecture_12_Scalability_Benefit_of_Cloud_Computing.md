# Lecture 12 Scalability Benefit of Cloud Computing

Scalaibity
* Ability to accomodate increasing demand by adding or removing resources as needed.
* Elasticity is for automatic. This is more system-design wise control of application size

What is it?
* It allows a system to adapt to changing usage patterns and handle increased traffic without requiring changes to the application code system design.

Does Traffic Fluctuate?
* Some businesses have traffic that fluctuates based on time of day or day of year
  * Holiday times in December
  * Dropping new products
* E-Commerce websites have Black Friday.
* School registrations are busy in September
  * August and/or January
* Tax systems are busy in April
  * July and August are minimal

The $1M Question
* Can you expand the capacity of a system easily, by adding more servers?
* Or will it be a massive undertaking to do that?

Vertical Scaling
* Scale up or down
* Single server made more or less powerful
* CPU add, speed upgrade
* Memory (RAM) add
* Pay money for this
* There is an upper limit
* Only go so high before you've reached the largest server
* Azure - 96 vCPUs, 384 GB memory (Oct 2023)
* Does not improve availability

Horizontal Scaling
* Scaling Out or Scaling In
* Adding more servers or a system
* Adding 4 servers is scaling out
* No limits to the amount you can scale: 4, 8, 80, 1000, inf...
  * Across Region US East, West, India, etc
* Additional complexities for load balancing

Impact on System Cost
* Adding more resources to sytem adds to cost
* 4 to 8 CPUs doubles cost
* 4 to 8 servers doubles cost
* Good news is you can reduce costs
* Having a scalable system allows for a system to be peferctly sized.
  * Quick and easy to add more
* Optimizes cost
  * Not trying to account for future growth

The level of max capacity can keep being rasied after Number concurrent users continues to increase.

