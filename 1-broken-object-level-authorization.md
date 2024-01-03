# API1:2023 Broken Object Level Authorization (BOLA)

[Link](https://owasp.org/API-Security/editions/2023/en/0xa1-broken-object-level-authorization/)

## Description

- Most common and damaging API vulnerability
- Manipulation of APIs to access data/objects belonging to other users
- Authorization not authentication issue

## Exposure

- Can lead to data loss, disclosure, and data manipulation

## Example

- Attacker authenticates as user A then retrieves data on user B

## Prevention

- Define data access policies and controls
- Enforce data access controls at application logic layer
- Implement automated testing to find BOLA flaws
- Implement logic to control what users can and can't see