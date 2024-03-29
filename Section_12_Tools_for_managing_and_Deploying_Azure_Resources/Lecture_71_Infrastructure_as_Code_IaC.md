# Lecture 71 Infrastructure as Code IaC

Infrastructure (n): all the servers, storage, database settings, network settings, firewalls, load balancers, etc.

How do you "backup" your infrastructure setup?

This is where IaC comes in

Define your desired Infrastructure in a configuration file

And then you can re-deploy it again and again and again... 
* IaC can help you get your Infra back to an original state for example.

Recreate it in another region (duplication)

Desired state configuration (DSC)

Using automation to ensure your configuration doesn't drift from the original setup.
* Sometimes intentional
* Trying to solve little problems can create a slow move of settings
* Make changes to config file, tracks changes, can be reverted.

IaC Options:
* ARM Templates (JSON)
* Bicep
  * Looks a little more like code, compiles to ARM template behind the scene
* Terraform
* Chef, Puppet - Open source options
* Powershell scripts
  * Lot of work and not as flexible but can work
* Other types of code
  * PHP, etc.

Exam will be ARM or Bicep

