---
name: file_debug_review
title: Debug File Review for Syntax Errors
description: A prompt template to review code files for syntax errors based on file name and error output. Analyzes provided error messages to identify common syntax issues like missing semicolons, brackets, or keyword mismatches.
category: development
tags: ["debug","syntax","code-review"]
difficulty: beginner
author: AI Assistant
version: 1.0
created: 2025-07-15T09:26:38.127Z
updated: 2025-07-15T09:26:38.127Z
arguments:
  - name: file_name
    description: Name of the code file being reviewed
    required: true
  - name: error_output
    description: Syntax error messages from the code execution
    required: true
---

### Debug File Review Prompt

Review the following code file ({{file_name}}) for syntax errors based on the provided error output:

**Error Output:**
{{error_output}}

Please:
1. Identify the type of syntax error(s) in the output
2. Suggest potential fixes
3. Provide example corrections if applicable
4. Indicate if additional context is needed from the file content