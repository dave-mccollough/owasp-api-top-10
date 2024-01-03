# API9:2023 Improper Inventory Management

[Link](https://owasp.org/API-Security/editions/2023/en/0xa9-improper-inventory-management/)

## Description

- Unauthorized API access via old or unused API versions or trusted 3rd parties

## Exposure

- Data and/or account theft via unretired APIs
- Exposure of sensitive data via improperly secured 3rd party APIs
  
## Examples

- Old API versions
- Unpatched endpoints
- Endpoints with weaker security
- Outdated documentation
- Unnecessarily exposed endpoints
- API access via a 3rd party

## Prevention

- Deploy/manage all APIs in gateway
- Define rules for versioning and retirement
- Periodically audit 3rd party access