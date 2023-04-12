Authorization/Authentication
lateral and horizontal authZ controls 
endpoints can be accessed without cookies/tokens
login functionality can be bypassed
Weak PW reset
Insecure Direct Object Reference
Missing Function-level access controls
Mass Assignment vulnerabilities


Encryption issues
Scan for TLS cipher issues
Insure all endpoints are using TLS
Injection
Identify backend DB functionality
Try to inject into backend DB
Template engine in use? If so, check for SSTI
XXE or XML injection
Path traversal 
Zip slip 
Info Disclosure
Banners showing tech metadata
Customer data
Anything that exposes more data than what we should know

XSS/SOP issues
Cross-site request forgery
No CSRF token
Guessable CSRF token
Using XSS to submit the form that contains an otherwise secure CSRF token
Same-site token config settings
XSS (dom, stored, reflected)

Enumeration 

Can get a list of user names from brute forcing login page
Missing rate limiting 
