# Lecture 27 Azure Functions

Small pieces of code that you can run in the cloud

Utility Function - does something for some specific finite period
* Used to be called Jobs

Can trigger on:
* HTTP call
* Timer
* Blob creation
* Message queue
* Dozens of other options

Cheap

100$/month min to start a VM

60$ month to run a web app

Million exe of function for free
* 1000s of executions for a week
* every 5 mins 24/day would not get to a million

Examples of Functions
* On a regular basis (i.e. every hour) moves all of the files from one container to another
* every 6 hrs, it calls an external API that clears the external web cache
* Every time a new message arrives in a queue, it creates three new messages in 3 other queues
* Every time a blob is uploaded into a storage acct, an email is ent to notify someone.

Serverless option
