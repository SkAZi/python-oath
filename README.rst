Python OATH
===========

python-oath is a package implementing the three main OATH specifications:
 - HOTP, an event based one-time password standard -- OTP -- using HMAC signatures,
 - TOTP, a time based OTP,
 - OCRA, a mixed OTP / signature system based on HOTP for complex use cases.


Getting started
===============

The main APIs are:

 - hotp, to generate a password.
 - accept_hotp, to check a received password,
 - totp and accept_totp, the same for the TOTP standard.
