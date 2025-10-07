---
name: implement_new_feature_story
title: Implement New Feature / Story from PRD
description: Analyze and implement features from Product Requirements Documents (PRDs) following a structured approach. Ensures thorough understanding, codebase analysis, and systematic implementation while maintaining consistency with existing patterns.
category: development
tags: ["prd","feature-implementation","user-stories","requirements","planning"]
difficulty: intermediate
author: Cline User
version: 1.0
created: 2025-10-07T11:49:33.410Z
updated: 2025-10-07T11:49:33.410Z
arguments:
  - name: prd_content
    description: The Product Requirements Document content or user story to implement
    required: true
---

I have provided you with a Product Requirements document (PRD). Please analyze the features and User Stories and implement as follows:

1. First, outline your understanding of:
   - The specific requirements from this story
   - How this feature integrates with existing functionality
   - Any dependencies or prerequisites

2. Perform a codebase analysis focusing on:
   - Existing patterns and conventions to follow
   - Integration points for the new feature
   - Reusable components or utilities

3. Provide an implementation plan including:
   - Component/file structure
   - Required changes to existing code
   - New components/modules to be created

4. For the implementation:
   - Follow existing code conventions and patterns
   - Maintain consistent naming and structure
   - Add appropriate error handling

5. Verification checklist:
   - List each requirement from the user story
   - Confirm implementation status of each requirement
   - Note any assumptions or decisions made

Constraints:
- Maintain consistency with existing codebase
- Follow the cursor rules
- Do not add any unit tests at this time

PRD Content:
{{prd_content}}