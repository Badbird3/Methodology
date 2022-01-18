# WebSec_Study

# Goal: develop web hacking expertise. 

## Focus 

### S 
- injection
 - SQL Injection	// install mysql and learn syntax
    - Generic SQL injection
    - Blind SQL injection
    - SQL injection through common WAFs
 - Command-line injecton
    - Generic CLI
    - Argument-based CLI (gtfobins)
 - Code injection
    - Server-side template injection
        - Jinja[2] (Python)
        - Twig (PHP)
        - Velocity (Java)
        - Hibernate injection
 - LDAP injection
 - NoSQL injection
- XXE
    - Generic XXE	// find an instance where you can complete this 
    - Error-based output XXE	
    - Blind XXE
- deserialization
    - PHP Deserialization
        - PHAR file loading
    - Java Deserialization (POJO)
    - Java Deserialiation (xstream)
    - JavaScript deserialization
    - Python Deserialization (cPickle)
    - Sandbox escapes 
        - Handlebars template injection example
        - Old Ghostscript exploit examples
- path traversal, file inclusion etc
    - Insecure file upload
    - Generic path traversal
        - Relative
        - Absolute
    - Zip file path traversal
        - Extract / Read
- SSRF / Parameter manipulation
    - The confused deputy (microservice issue)
### A 
- Authentication
    - Generic session entropy issues
    - JWT implementations and issues
        - None algo
        - Using RS256 certificate for HS256 signing
        - Key file traversal / changing
    - Signature algorithms
        - RS256/512 (RSA_SHA)
        - HMAC (SHA-256/512)
        - ECC (NISTp256/ed25519)
    - Insecure password reset
        - Use of insecure PRNGs
        - Empty reset token
### B 
- Authorization
    - Insecure Direct Object Reference
    - Missing Function-level access controls
    - Mass Assignment vulnerabilities
### C 
- XXS /SOP bypass
    - Cross-site scripting (general)
        - Vanilla
        - Dom-based XSS
    - Cross-site scripting (within frameworks)
        - ReactJS cross-site scripting
        - Angular cross-site scripting
        - Template-based cross-site scripting
        - VueJS cross-site scripting
    - postMessage SOP issues
    - CORS SOP issues
    - JSONP issues
    - Cross-site request forgery
        - No CSRF token
        - Guessable CSRF token
        - Using XSS to submit the form that contains an otherwise secure CSRF token