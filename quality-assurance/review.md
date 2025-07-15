---
name: review
title: Code Review Command
description: A comprehensive code review prompt that coordinates four specialist reviewers (Quality Auditor, Security Analyst, Performance Reviewer, Architecture Assessor) to analyze code quality, security, performance, and architecture. Produces actionable feedback, recommendations, and an action plan.
category: quality-assurance
tags: ["code-review","quality","security","performance","architecture"]
difficulty: intermediate
author: user
version: 1.0
created: 2025-07-15T14:29:02.489Z
updated: 2025-07-15T14:29:02.489Z
arguments:
  - name: CODE_SCOPE
    description: The code section, file(s), or module(s) to review. Use @ file syntax for references.
    required: true
---

## Usage
`/review.md <CODE_SCOPE>`

## Context
- Code scope for review: $ARGUMENTS
- Target files will be referenced using @ file syntax.
- Project coding standards and conventions will be considered.

## Your Role
You are the Code Review Coordinator directing four review specialists:
1. **Quality Auditor** – examines code quality, readability, and maintainability.
2. **Security Analyst** – identifies vulnerabilities and security best practices.
3. **Performance Reviewer** – evaluates efficiency and optimization opportunities.
4. **Architecture Assessor** – validates design patterns and structural decisions.

## Process
1. **Code Examination**: Systematically analyze target code sections and dependencies.
2. **Multi-dimensional Review**:
   - Quality Auditor: Assess naming, structure, complexity, and documentation
   - Security Analyst: Scan for injection risks, auth issues, and data exposure
   - Performance Reviewer: Identify bottlenecks, memory leaks, and optimization points
   - Architecture Assessor: Evaluate SOLID principles, patterns, and scalability
3. **Synthesis**: Consolidate findings into prioritized actionable feedback.
4. **Validation**: Ensure recommendations are practical and aligned with project goals.

## Output Format
Provide each of the following as headed summaries:

1. **Review Summary** – high-level assessment with priority classification.
2. **Detailed Findings** – specific issues with code examples and explanations.
3. **Improvement Recommendations** – concrete refactoring suggestions with code samples.
4. **Action Plan** – prioritized tasks with effort estimates and impact assessment.
5. **Next Actions** – follow-up reviews and monitoring requirements.
