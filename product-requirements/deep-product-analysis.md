---
name: deep_product_analysis
title: Deep Product Analysis
description: Performs comprehensive meta-analysis of product requirements including effectiveness evaluation, pros/cons analysis, recommendations, and alternatives consideration. Generates a detailed report covering overview, lifetime effectiveness, gaps, future considerations, organizational benefits, and adoption costs.
category: product-requirements
tags: ["product-analysis","requirements","analysis","product-management","documentation"]
difficulty: advanced
author: jon
version: 1.0
created: 2025-10-07T07:45:03.384Z
updated: 2025-10-07T07:45:03.384Z
arguments:
  - name: adr
    description: Architectural Decision Record content to analyze
    required: true
  - name: prd
    description: Product Requirements Document content to analyze
    required: true
---

Do some meta analysis to analyse the following product requirements, including what it does, and how effective it could be. Come up with a pros and cons list, thinking about how it will be used over the lifetime of the product. Come up with a list of recommendations to improve it, or alternatives to consider for a tool we could build.

ANALYSIS PHASE:

Read, analyse and understand the following product and technical requirements:

Architectural Decision Record: {{adr}}

Product Requirements Document: {{prd}}

IMPLEMENTATION PHASE:

Do deep analysis of the proposed solution and write a report detailing the following:
# Overview and Purpose
# What the App Does and Its Effectiveness
# Potential Effectiveness Over the App's Lifetime
# Pros and Cons
# Recommendations for Improvement
[Including any gaps in the requirements]
# Alternatives to Consider
# Futurespective
[What are some potential issues users might face using this product a few years from now?]
# Benefits
[What could be the overall benefits to an organisation who adopts this product?]
# Costs
[What are some of the possible costs of adoption]

The report should be in a single, downloadable file using markdown formatting.

VERIFICATION AND COMPLETION PHASE:

- Make sure the analysis is thorough and covers all the sections listed above.
- Highlight any areas where you have made assumptions.
- Suggest improvements where possible.