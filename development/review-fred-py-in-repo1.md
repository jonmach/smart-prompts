---
name: review_fred_py_in_repo1
title: Review fred.py in repo1
description: A code review template for analyzing the Python file fred.py in the repository https://github.com/repo1. Checks for code quality, security, and compliance with best practices.
category: development
tags: ["code-review","github","python"]
difficulty: intermediate
author: assistant
version: 1.0
created: 2025-07-02T22:27:33.971Z
updated: 2025-07-02T22:27:33.973Z
arguments:
  - name: github_url
    description: The GitHub URL of the repository containing the file to review
    required: true
  - name: file_path
    description: The full path to the Python file within the repository
    required: true
---

## Code Review for {{file_path}}

**GitHub URL:** {{github_url}}

This template analyzes the file {{file_path}} from the GitHub repository {{github_url}}.

### Review Steps:
1. Check for code smells and PEP8 compliance
2. Verify variable naming conventions
3. Look for potential security vulnerabilities
4. Evaluate function efficiency and readability
5. Ensure adherence to project coding standards

### Expected Output:
- Code quality score
- Security risk summary
- Performance optimization suggestions
- Compliance status with coding standards