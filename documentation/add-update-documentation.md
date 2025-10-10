---
name: add_update_documentation
title: Add / Update Documentation
description: Comprehensive documentation creation and update prompt for maintaining README.md and ARCHITECTURE.md files. Focuses on technical accuracy, clarity, and consistency using British English with professional tone.
category: documentation
tags: ["documentation","readme","architecture","technical-writing","british-english"]
difficulty: intermediate
author: user
version: 1.0
created: 2025-10-10T15:10:15.541Z
updated: 2025-10-10T15:10:15.541Z
arguments:
  - name: directory
    description: The directory path containing the codebase to document
    required: true
---

Please review the codebase in directory {{directory}} and create or update the following documentation files while maintaining their existing structure and format.

Required Documentation:
1. README.md
2. ARCHITECTURE.md

Documentation Standards:
- Maintain existing document structure (if applicable)
- Be concise yet informative
- Use professional British English
- Use proper Markdown formatting
- Create or update Mermaid diagrams if applicable

Focus Areas:
1. Technical accuracy
2. Clarity and readability
3. Completeness of information
4. Consistency across documents
5. Current best practices
6. Data model documentation

Key constraints:
- This is an incremental update to existing documentation
- Only update or add documentation as necessary 
- Keep a consistent tone and style with existing content
- Use British English

Provide a complete, production-ready update in British English with a professional tone.