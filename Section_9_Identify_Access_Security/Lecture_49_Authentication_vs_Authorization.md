# Lecture 49 Authentication vs Authorization

Azure active directory can do a lot.

Authentication vs Authorization

Authentication is a user proving who they are - user id and password

Knowing who they are does not give you info on what they CAN do.

Authorization is ensuring that a user is permitted to perform an action

Applications can teir where some are:
* read-only
* IT
* Support
* Managment
* Admin
* Power-user
* Publisher
* etc

Move away from all authenticated users having admin access

Avoid unexpected and bad circumstances

If every user can create other users
* Users can get 2nd accounts for only the reason of forgot password
* Give the 2nd user to a friend
