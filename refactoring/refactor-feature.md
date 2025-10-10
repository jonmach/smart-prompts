---
name: refactor_feature
title: Refactor Feature
description: A comprehensive code refactoring prompt focused on readability, maintainability, and consistency. Performs detailed analysis and provides prioritized refactoring recommendations with implementation guidance.
category: refactoring
tags: ["refactoring","code-review","readability","maintainability","code-quality"]
difficulty: intermediate
author: user
version: 1.0
created: 2025-10-10T15:05:38.123Z
updated: 2025-10-10T15:05:38.123Z
arguments:
  - name: filename
    description: The file or component to be refactored
    required: true
---

I want to refactor {{filename}}. The goal is to make it easy to read and reason about.

Do the following:

1. First, outline your analysis approach and methodology.

2. Then, perform a detailed code review focusing on:
   - Readability and maintainability
   - Consistency of design patterns and naming conventions
   - Code duplication and opportunities for reuse
   - Focus on incremental improvements rather than major redesigns  

3. Deliver your findings as:
   a) A prioritized list of refactoring opportunities, with each item including:
      - Description of the issue
      - Location(s) in the codebase
      - Impact assessment (high/medium/low)
      - Potential risks or dependencies
   
   b) Implementation recommendations including:
      - Suggested order of changes
      - Any prerequisite refactoring needed
      - Testing considerations

Key constraints:
- Maintain existing design patterns - do not introduce new ones
- Prioritize consistency and readability over performance optimizations
- Ensure all changes align with cursor rules guidelines
- Focus on incremental improvements rather than major redesigns
  
Prompt me for feedback before implementing.