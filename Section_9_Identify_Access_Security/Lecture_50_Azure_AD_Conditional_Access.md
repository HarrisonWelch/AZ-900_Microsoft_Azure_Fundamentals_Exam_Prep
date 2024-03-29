# Lecture 50 Azure AD Conditional Access

Conditional Access

common ways for accts to get hacked - individual outside company gets access to account that is able to find or infer user with admin rights

User A attempts to log in to the app from within the company office, as she does every day.
* In the office - certain level of high trust
* Out of the office or out of the country (hacker) - low trust, give code to type in.

User B attempting to log in to the app for the first time in 4 months
* Login after a loooooooong time

Admin C attempts to login from their phone
* Extra careful

Admin D logs in to the app from a location 1200 miles away

You can treat some access attempts as "routine" and some as "not normal"

Conditional Access
* Signal
  * Device
  * Location
  * IP address
  * Last login time
* Descition
  * Increased assurance
    * Text message
    * Limited privledges
    * Block account
    * Deny login
* Enforcement
  * Dont allow access after logged or such


