---
name: code_review_for_specific_file
title: Code Review for Specific File in GitHub Repository
description: A comprehensive code review template that analyzes a specific file from a GitHub URL, checking code quality, security, performance, and adherence to development standards.
category: development
tags: ["code-review","github","quality-checks"]
difficulty: intermediate
author: user
version: 1.0
created: 2025-07-01T17:31:33.153Z
updated: 2025-07-01T17:31:33.154Z
---

### Code Review for File: {{URL}}

Language: {{language}}
Development Standard: {{standard}}
Security Standard: {{security_standard}}

## General Checklist

### Code Quality

- Code follows {{language}} style guidelines and conventions
- Functions and variables have descriptive, meaningful names
- No code duplication (DRY principle followed)
- Complex logic is well-commented
- Code is modular and follows single responsibility principle

### Error Handling

- All error cases are properly handled
- Error messages are informative and actionable
- No silent failures or swallowed exceptions
- Proper logging for debugging

### Performance

- No obvious performance bottlenecks
- Efficient algorithms and data structures used
- Database queries are optimized
- No memory leaks or resource management issues

### Security

- Input validation and sanitization
- No hardcoded secrets or credentials
- Proper authentication and authorization checks
- Protection against common vulnerabilities (SQL injection, XSS, etc.)

### Scalability

- Architecture allows for future expansion
- Code can handle increased load without major rewrites
- Efficient use of system resources

### Cost Optimisation

- Avoid unnecessary resource consumption
- Use cost-effective solutions where possible
- Minimize server-side computations

### Operational Readiness

- Code is ready for deployment
- Infrastructure requirements are clear
- Documentation covers deployment steps

### Testing

- Adequate test coverage for new code
- Tests are meaningful and test actual behavior
- Edge cases are covered
- Tests are maintainable and readable

{{#if (eq language "JavaScript")}}
### JavaScript-Specific Checks

- Proper use of async/await and Promise handling
- No memory leaks from event listeners or timers
- Appropriate use of const/let (no var)
- Proper TypeScript types (if applicable) {{/if}}

{{#if (eq language "Python")}}
### Python-Specific Checks

- PEP 8 compliance
- Proper use of type hints
- Virtual environment dependencies documented
- No mutable default arguments {{/if}}

{{#if (eq language "Java")}}
### Java-Specific Checks

- Proper use of access modifiers
- Thread safety considerations
- Resource management with try-with-resources
- Appropriate use of design patterns {{/if}}

## Additional Notes

Add any specific observations or suggestions here