---
name: api_requirements
title: API Requirements
description: Generate comprehensive REST API requirements following strict RESTful conventions. Creates detailed endpoint specifications with request/response examples, validation rules, error handling, and data schemas.
category: product-requirements
tags: ["api","rest","requirements","documentation","endpoints"]
difficulty: intermediate
author: Cline
version: 1.0
created: 2025-10-07T08:31:06.711Z
updated: 2025-10-07T08:31:06.711Z
arguments:
  - name: operations
    description: API operations needed (e.g., CRUD, bulk operations, search, file uploads, etc.)
    required: true
  - name: data_model
    description: Data model/schema including relationships and constraints
    required: true
  - name: special_requirements
    description: Special requirements like authentication, rate limiting, versioning, performance constraints, etc.
    required: false
---

## Instructions
Generate comprehensive REST API requirements following strict RESTful conventions. Use plural resource names and include practical examples.

## Required Output
For each endpoint provide:
- HTTP method, URL pattern, and parameters
- Request/response JSON examples with realistic data
- HTTP status codes (success + common errors)
- Validation rules and constraints
- Pagination, filtering, and sorting (for lists)

## Input Details

### Operations Scope
This should include API operastions needed, CRUD, bulk operations, search, file uploads etc.<p>
{{operations}}

### Data Model
This should include data model/schema and include any relationships and consraints<p>
{{data_model}}

### Special Requirements (Optional)
This could include for example, any authentication, rate limiting, version, performance constraints.<p>
{{special_requirements}}

## Output Format
1. **API Overview** - Purpose and base URL
2. **Endpoints** - Specs with examples for each operation
3. **Error Responses** - Standard error format
4. **Data Schemas** - JSON definitions

Ask clarifying questions about ambiguities before proceeding.
