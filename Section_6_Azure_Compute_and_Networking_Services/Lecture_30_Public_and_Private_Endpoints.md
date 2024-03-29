# Lecture 30 Public and Private Endpoints

Pub and Priv endpoints

Resources in Azure have different levels of access in terms of "HOW"

Create a Storage Account network settings
* Network access
  * Enable public access does not mean anyone can access, still need a access
    * Public means it has a door with some kind of lock
  * Enable on Vnet
    * Specifiy which of your vnets can access the resource
  * Disable Pub and Priv entirely
    * Only have 1 to 1 connections
    * Higher security way to go about this

