# API7:2023 Server Side Request Forgery (SSRF)

[Link](https://owasp.org/API-Security/editions/2023/en/0xa7-server-side-request-forgery/)

## Description

- Exploit URL inputs to make requests to a 3rd party server

## Exposure

- Potential for data leaks
- SSRF creates an opportunity for malicious requests, data access or other fraudulent activity

## Examples

- Local file injection
- Malware downloaded from malicious sites

## Prevention

- Validate and sanitize all user supplied information including URL parameters
- Ensure communication only with entrusted resources
- Test URL validation