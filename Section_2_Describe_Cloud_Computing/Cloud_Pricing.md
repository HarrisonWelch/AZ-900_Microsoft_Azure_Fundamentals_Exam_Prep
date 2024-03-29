# Cloud Pricing

Talking around the controversal topic.

Pricing for working with services in the cloud.

This is complicated or can be.

If we look at a typical Azure service. There are 2 or 3 factors on what could be needed.

This means it can be difficult to estimate the cost.

Pricing becomes different from month to month.

And this bill can fluctuate.

Could use history after 12 months, but starting from stratch and predicting this can be difficult.

Factors affecting VM Pricing.
* Geographical Location - US can differ from Canada, Brazil, etc.
* OS - Windows vs Linux, plus additions like the pro or server edition of the OS
* Instance Size - CPU count
* Disk Type, HDD vs SSD and the number of Gigs or Tibs
* Bandwidth - I/O going in and out.
* Backups - repeatedness
* Reservation/Savings Plan - Kick you out of a machine if need resources.
* Support Agreement - MS support calls and emails

^ now factor that across hunders of descisions

Factors Affecting VM Pricing
* API Choice
* Region(s)
* Storage needed
* Dedicated gateway
* Backups
* IOPS
* Standard Model or serverless

Free services.
* 55+ free services to try
* Within a certain limit
* Can choose to integrate

Most common way is to be charged by time. VM instance.
* 730 hours
* You can save by stopping the service

Pay for GB
* Usually paid by data storage used
* 0.02 $ per GB per month
* Also pay for traffic, I/O in and out

Pay for Operations
* WRiting to the disk, delete files
* Events sent thru the hub
* Pay per message, query to the DB
* Usually v cheap per operation
* Keep in mind for estimation of events

^ Just 3 of the metrics, not going to get esoteric after a while 
