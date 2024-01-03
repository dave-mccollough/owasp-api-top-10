# API10:2023 Unsafe Consumption of APIs

[Link](https://owasp.org/API-Security/editions/2023/en/0xaa-unsafe-consumption-of-apis/)

## Description

- Exposures can occur via use of 3rd party APIs that are generally trusted

## Exposure

- Data theft, breach, and/or account takeover

## Examples

- Attacker inserts malicious address data to validation site used by client. Client fails to validate data
- Attacker compromises 3rd party API causing it to redirect to malicious site. Client follows redirect

## Prevention

- Validate data returned by 3rd party APIs
- Evaluate security controls of 3rd party APIs
- Encrypt all API communication
- Maintain approved list of known API integrations
