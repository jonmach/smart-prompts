---
name: test_driven_development
title: Test Driven Development
description: A comprehensive TDD workflow prompt that guides through the Red-Green-Refactor cycle. Analyzes PRD features and implements them using strict test-first development, ensuring tests are written before implementation code.
category: development
tags: ["tdd","testing","red-green-refactor","test-first","quality-assurance","agile"]
difficulty: intermediate
author: User
version: 1.0
created: 2025-10-10T14:44:56.357Z
updated: 2025-10-10T14:44:56.357Z
arguments:
  - name: prd_content
    description: The Product Requirements Document content containing features and user stories to implement
    required: true
---

I have provided you with a Product Requirements document(PRD). Please analyze the features and User Stories and implement Feature:

PRD Content: {{prd_content}} 

I want to use strict test-driven development. Please write the failing test first, then we'll write code to make it pass. Do not write any implementation code until I've reviewed the test.

Follow the Red-Green-Refactor cycle strictly:
1. RED: Write a failing test
2. GREEN: Minimal code to pass
3. REFACTOR: Improve while keeping tests green

### Start with step 1 only

Write failing tests for Feature 1. Show me:
1. The test code
2. Why it will fail
3. What error message we'd expect

Test-First Reasoning:
Before writing any implementation, walk me through:
- What behavior should this test verify?
- What would make this test pass?
- What assumptions am I making?

### Now lets do step 2. 

GREEN: Minimal code to pass

Writing Minimal Code:
Now write the absolute minimum code needed to make this test pass. Nothing more, nothing less.
Make this test pass with the simplest possible implementation. Don't worry about edge cases or future features yet.

Catching Over-Engineering:
Is this the minimum code needed, or are you implementing extra features not covered by the current test?
Review your implementation: What parts aren't required by the failing test? Remove everything unnecessary.

After writing the code, please execute the tests

### Now lets do step 3. 

REFACTOR: Improve while keeping tests green

Refactor this code to improve the readability and structure while keeping all tests green. Show me the refactored version and confirm tests still pass