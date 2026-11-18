---
name: api-developer
description: Design, build, secure, test, and document reliable REST APIs using established backend development practices.
---

# API Developer Skill

## Purpose

Help AI agents design and implement reliable, secure, maintainable APIs.

## Core Responsibilities

- Design clear and consistent API endpoints.
- Implement RESTful API conventions.
- Validate and sanitize incoming data.
- Handle authentication and authorization.
- Implement structured error responses.
- Integrate databases and external services.
- Write API tests and documentation.

## Development Workflow

1. Understand the API requirements and expected consumers.
2. Inspect the existing backend architecture and conventions.
3. Define endpoints, HTTP methods, request schemas, and response formats.
4. Implement business logic separately from routing where appropriate.
5. Add input validation and appropriate authorization checks.
6. Implement consistent error handling and logging.
7. Write tests for successful requests, failures, and edge cases.
8. Document endpoints, parameters, authentication, and responses.

## API Design Guidelines

- Use appropriate HTTP methods and status codes.
- Keep endpoint naming consistent.
- Return predictable JSON response structures.
- Validate all untrusted input.
- Avoid exposing internal errors or sensitive information.
- Implement pagination for large collections.
- Consider rate limiting and abuse prevention.
- Use versioning when breaking changes are necessary.
- Never hardcode credentials, API keys, or secrets.

## Security Checklist

- [ ] Authentication is implemented where required.
- [ ] Authorization is checked for protected resources.
- [ ] Input validation is enforced.
- [ ] Sensitive data is not exposed.
- [ ] SQL injection and other injection risks are addressed.
- [ ] Rate limiting is considered.
- [ ] Secrets are stored securely.

## Testing Checklist

- [ ] Successful requests tested.
- [ ] Invalid input tested.
- [ ] Unauthorized requests tested.
- [ ] Missing resources tested.
- [ ] Error responses tested.
- [ ] Edge cases considered.

## Expected Output

Provide implementation details, endpoint documentation, relevant code changes, and testing instructions.

Never claim that an API or test has been executed unless it actually has.
