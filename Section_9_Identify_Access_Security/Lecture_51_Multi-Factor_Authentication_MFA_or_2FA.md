# Lecture 51 Multi-Factor Authentication MFA or 2FA

Concept of Multi-factor Authentication

Require 2 or more pieces of evidence (factors) in order to login

Three factors
* Something you know - i.e. password
  * Change password every so often
* Something you have - i.e. mobile phone, access to email acct
  * send code to email
  * text you a code
  * login to application that generates a number every few minutes
  * hacker halfway around the world won't have access to your phone
* Something you are - i.e. fingerprint
  * Face ID with apple
  * Problem is you can't change it

Your unique password could be considered 1 piece of evidence

2nd evidence is required - unique time limited code sent to you
* 5 mins
* 60 seconds

MS Azure, there are 4 ways
* SMS
* email
* Authenticator app
* phone call
  * Robot tells you a number
