# Lecture 14 Reliability Benefit of Cloud Computing

All three relating to High Quality Service
* Availablity
* Reliability
* Predictability

Reminder: Availability
* The ability of a system to be accessible and usable when they need it. At any point usually

Reliability
* Ability of a system to perform its intended function without interupption and with a high degree of accuracy
* Doing a good job at available

Availabilty vs Reliability
* A system can be highly availalbe to users
* In that it responds instanly to every request
* However, don't look behind the curtain
* The system itself might be highly unreliable
* What use is a calculator that can answer every question with the wrong answer?
* Or an app that loses your data sometimes randomly?

Availability vs Reliability
* Availability is apperance of working
* Reliability is an underlying truth

Reliability
* How dependable a system is
* The ability to perform without interupption

Why is it needed?
* You have to trust that your clod provider is doing everything it can to make its platform reliable
* Includes transparency during service issues

How is it Achieved?
* Auto-scaling
  * Go above capacity = problems, errors, crashes
* Multi-region deployments
* Data backup and replication
* Health probes and self-healing
  * Create a new instance or restart
