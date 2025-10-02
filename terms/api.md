# API (Application Programming Interface)

## Definition
An Application Programming Interface (API) is a set of rules, protocols, and tools that allows different software applications to communicate with each other.

## Use Cases
- Enabling third-party integrations with existing software
- Building microservices architectures
- Connecting front-end applications with back-end services
- Automating tasks between different systems

## Examples

### REST API
```
GET /api/users/123
```
Returns user data in JSON format for user ID 123.

### GraphQL API
```
query {
  user(id: 123) {
    name
    email
  }
}
```
Allows clients to request specific fields from the server.

## Related Terms
- REST (Representational State Transfer)
- GraphQL
- Webhook
- SDK (Software Development Kit)
