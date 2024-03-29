# Shared Responsibility Model

You and MS have shared responsibility including security

"On Premises Responsibility"
* All you!
* OS patches
* Building Security
* Authentication
* Devices
* Data
* Accounts for users
* App settings
* Network and Firewall

Cloud VM Responsibility:
* Azure - Building Security
* Azure - Physical Network Security
* Azure - Physical Computer Security

Now the rest is you!
* OS patches
* Network Firewall Settings
* Application Settings
* Auth platform
* User accounts
* Devices
* Data

Moving up to an APP Service


Cloud App Responsibility:
* Azure takes over the OS patching
* Network and Firewall settings are now split between client and Azure
* App settings are split
* Auth platform

In other words...:
* Azure - Building Security
* Azure - Physical Network Security
* Azure - Physical Computer Security
* Azure - OS patches
* Shared - Network Firewall Settings
* Shared - Application Settings
* Shared - Auth platform
* Client - User accounts
* Client - Devices
* Client - Data

Still fully responsible for 
* User accounts
* Devices
* Data

Cloud SaaS:
* Azure - Building Security
* Azure - Physical Network Security
* Azure - Physical Computer Security
* Azure - OS patches
* Azure - Network Firewall Settings
* Azure - Application Settings
* Shared - Auth platform
* Client - User accounts
* Client - Devices
* Client - Data

The farther you go up the extraction the less repsonsbility

![Diagram showing what you manage vs Microsoft/Cloud Provider](https://dachou.github.io/assets/20110326-cloudmodels.png)



