---
name: error_root_cause_explainer
title: Error Root Cause Explainer with Dual Coding (Text + Mermaid Diagram)
description: Analyze and explain the root cause of a given error or syntax error. Provide a detailed explanation in text and a visual representation using a mermaid diagram. Do not modify any code or propose direct fixes—focus on understanding and communicating the problem.
category: development
tags: ["error","explanation","mermaid","root-cause","diagnosis"]
difficulty: intermediate
author: jonmach
version: 1.0
created: 2025-07-09T13:40:54.079Z
updated: 2025-07-09T13:40:54.079Z
arguments:
  - name: error
    description: The error message or syntax errors to analyze and explain.
    required: true
---

Understand and explain the root cause of this error and propose possible solutions using dual coding: text and visually using mermaid diagrams. Don’t modify any code or execute any fix.

Error:
{{error}}
