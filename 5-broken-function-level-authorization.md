# API5:2023 Broken Function Level Authorization

[Link](https://owasp.org/API-Security/editions/2023/en/0xa5-broken-function-level-authorization/)

## Description

- Abuse of API functionality to improperly modify objects (create, update and delete)
- Usually involves replacing passive methods (GET) with PUT or DELETE

## Exposure

- May be used to escalate privilege
- Can be exploited to modify account details

## Examples

- Modify parameters: "role = admin"
- Delete invoices
- Set account balances

## Prevention

- Identify high sensitivity functions and develop controls to limit access
- Continuous release testing to ensure correct behavior
