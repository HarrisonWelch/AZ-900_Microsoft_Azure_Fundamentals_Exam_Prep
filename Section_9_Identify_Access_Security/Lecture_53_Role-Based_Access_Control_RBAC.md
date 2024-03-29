# Lecture 53 Role-Based Access Control RBAC

Role Based Access Control

Authorization

This is Microsoft's preferred solution for access control

To contrast - Claims based
* If you have token they let you in. DIgital applications

Create roles that represent the common tasks of the job

Assign permissions to the role where then the user gets the role

Accessing data, applications, storage accts, subscriptions.
* You don't want HR able to stop a VM

Assign granular permissions to that role
* Instead of saying, devs can do anything, you can set permissions at a very low level

Benefit is security. Getting specific permissions lower the risk of something unexpected thing happening.

Assign users to that role
* Devs get Dev role
* Manager gets the manager and dev role
  * Can assign multiple roles

This way you don't have to assign permissions to 20,000 employees. Could lead to accidents where you have more or less than expected

Built-In permissions within Azure
* Reader
* Contributor
* Owner

Individual would never make edits - Reader perm
Contributor - Would make edits - read and write full access
Owner - can give permissions to other people

100s of granualar permissions
