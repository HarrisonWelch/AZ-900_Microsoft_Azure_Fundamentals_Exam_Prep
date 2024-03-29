# Lecture 64 Azure Policy

One of the main ways and commonly enforce rules in a company

Create rules across all of your Azure resources

Evaluate compliance to those rules
* Daily backup for example
* Every VM must have a daily backup

Assign policy to a resource group

Create a "consequence" to not following this policy.
* Report is generated that your VM does not have a backup
* Prevent the VM from being created.

Example of built-in policies
* Require SQL Server 12.0
* Allowed Storage Account SKUs
* Allowed Locations
* Allowed Virtual Machine SKUs
* Apply tag and its default value
* Not allowed resource types

Can create custom policies using JSON definition

