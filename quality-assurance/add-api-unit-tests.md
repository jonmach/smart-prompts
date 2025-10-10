---
name: add_api_unit_tests
title: Add API Unit Tests
description: Analyze a Product Requirements Document (PRD) and create comprehensive unit tests for the described features. This prompt guides the creation of journey-focused tests using Given-When-Then patterns, with proper mocking of external dependencies and coverage of both happy and unhappy paths. Includes execution and debugging of tests.
category: quality-assurance
tags: ["api","unit-testing","testing","mocking","tdd","prd"]
difficulty: intermediate
author: Cline
version: 1.0
created: 2025-10-10T14:55:17.776Z
updated: 2025-10-10T14:55:17.776Z
arguments:
  - name: prd_content
    description: The Product Requirements Document containing features and user stories to test
    required: true
---

I have provided you with a Product Requirements document (PRD). Please analyze the features and User Stories and create new tests for the features.

PRD Content: {{prd_content}}

## Analysis Requirements
1. Review testing standards from the testing cursor rules
2. Analyze:
   - Source code
   - Unit interactions
   - External dependencies requiring mocks
   - Data models and flows
   - Existing test coverage

## Implementation Guidelines
1. Test Structure:
   - Use Given-When-Then pattern with descriptive comments
   - Focus on journey workflows over isolated units
   - Mock external dependencies appropriately

2. Test Coverage:
   - Core user scenarios and workflows
   - Edge cases and error conditions
   - Both happy and unhappy paths

3. Quality Standards:
   - Clear test descriptions
   - Meaningful assertions
   - Efficient test setup and teardown

## Constraints
- Scope: Modify only the test file and test utilities / helpers
- Format: Deliver complete, production-ready test code
- Standards: Follow the testing cursor rules

## Output
After creating the tests please execute them and fix any issues