# API3:2023 Broken Object Property Level Authorization

[Link](https://owasp.org/API-Security/editions/2023/en/0xa3-broken-object-property-level-authorization/)

## Description

- Manipulation of data and objects from an API endpoint
- Exploit endpoints by reading and/or modifying object values
- Update or modify object elements
- Data exposure - reveal sensitive data

## Exposure

- Reveal protected user data

## Example

- User search API returns all user details including email, address, id, etc
- Change user from 'free' to 'paid'

## Prevention

- Ensure users can only access permitted fields
- Return only minimum amount of data for each use case
