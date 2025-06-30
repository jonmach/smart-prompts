---
name: function_generator_by_language
title: Generate a function in a specified programming language
description: Given a programming language and a function description, this prompt instructs an LLM to generate the function in the specified language. Useful for quickly generating code snippets in any language.
category: development
tags: ["code-generation","function","language","llm"]
difficulty: beginner
author: Cline
version: 1.0
created: 2025-06-30T22:47:53.674Z
updated: 2025-06-30T22:47:53.679Z
arguments:
  - name: language
    description: The programming language in which to generate the function.
    required: true
  - name: function_description
    description: A description of the function to generate.
    required: true
---

Write a function in {{language}} that does the following:

{{function_description}}

- Only output the code for the function, with no extra explanation or comments unless they are idiomatic for the language.
- Ensure the function is complete and syntactically correct for {{language}}.
- If the function requires imports or dependencies, include them as part of the code output.