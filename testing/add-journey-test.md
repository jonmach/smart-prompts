---
name: add_journey_test
title: Add Journey Test
description: Create a comprehensive Playwright journey test based on a user story. This prompt guides the creation of BDD-style tests with proper selectors, accessibility scanning, and adherence to Playwright best practices. Includes analysis and implementation phases with specific focus on page structure, component relationships, and real application testing (no mocks).
category: testing
tags: ["playwright","testing","journey-test","bdd","accessibility","e2e"]
difficulty: intermediate
author: Cline
version: 1.0
created: 2025-10-10T14:48:22.607Z
updated: 2025-10-10T14:48:22.607Z
arguments:
  - name: user_story
    description: The user story containing BDD scenarios that need to be tested with Playwright
    required: true
---

Create a Playwright journey test that meets the requirements in this user story: {{user_story}}

Follow the Playwright testing cursor rules

ANALYSIS PHASE:
- Understand the user story
- Understand the Playwright testing cursor rules
- Identify:
  - Each of the BDD scenarios to be tested
  - Page structure; the tree of page markup, containing noteworthy elements for the tests
  - Component Structure; tree of components markup, for those components that are relevant to the test
  - The expected user interactions
  - The most appropriate selectors / locators, including using relative selectors for nested or related components

Test Setup:
- Base URL: /standards/standard-sets

Test Interaction Data:
Use these values to interact with the application:
- Standard Set: Test Standards
- Standard: Java Coding Standards
- Classification: Java
- Repository URL: https://github.com/ee-todd/test-standards-set/
- Note: Do not expect specific IDs, as these can change between environments

Important Considerations:
- Give special consideration to scoping elements - like finding classifications and standards within table rows, and using :has() selectors for parent-child relationships.
- The tests will be journey tests with the real application. No mocks
- Use JavaScript (not TypeScript)

IMPLEMENTATION PHASE:
- Implement tests for each of the BDD Scenarios in the user story
- Follow the Playwright testing cursor rules

Accessibility Testing:
Please add a simple test to use `@axe-core/playwright` to do an accessibility scan against the page. Search @Web for how to do this
