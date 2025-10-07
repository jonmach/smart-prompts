---
name: data_model_generation
title: Data Model Generation
description: Generate comprehensive data models based on product and technical requirements. Analyzes business requirements and system architecture to create detailed database schemas with Mermaid diagrams for visualization.
category: product-requirements
tags: ["data-model","database","schema","requirements","mermaid","architecture"]
difficulty: intermediate
author: Cline
version: 1.0
created: 2025-10-07T08:45:32.926Z
updated: 2025-10-07T08:45:32.926Z
arguments:
  - name: product_requirements
    description: Detailed feature description and product requirements
    required: true
  - name: high_level_architecture
    description: System architecture overview and technical specifications
    required: true
  - name: database_of_choice
    description: Target database system (e.g., PostgreSQL, MySQL, MongoDB)
    required: true
---

I'd like to create a data model based on the following project business and technical requirements.

ANALYSIS PHASE:

Read, analyse and understand the following product and technical requirements:

Detailed Feature Description - {{product_requirements}}

System Architecture - {{high_level_architecture}}

Ask any follow up questions that will clear up any ambiguities if needed.

IMPLEMENTATION PHASE:

Think about the above requirements and work out a simplified data model suitable for use with {{database_of_choice}}. Also produce a Mermaid diagram so it is understandable in a relational format. Feel free to change labels or column names to be more clear if needed if they are more logical. The data model should be in a single, downloadable file using markdown formatting.

VERIFICATION AND COMPLETION PHASE:

- Make sure the final model covers all the requirements before returning a solution.
- Highlight any areas where you have made assumptions.