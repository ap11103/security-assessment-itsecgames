# Security Assessment – itsecgames.com

## Objective

Conduct a security assessment on the public endpoint http://www.itsecgames.com

## Tools Used

* OWASP ZAP
* SSL Labs Server Test
* SecurityHeaders.com

## Summary of Findings

* Invalid and untrusted SSL certificate
* Weak TLS configuration (TLS 1.0 / 1.1 supported)
* Missing security headers (CSP, X-Frame-Options, etc.)
* No HSTS implementation
* Information disclosure via server headers

## Full Report

See /report/security-assessment.pdf

## Screenshots

See /screenshots/

## Video Demonstration

See /video/
