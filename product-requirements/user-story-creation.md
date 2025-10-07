---
name: user_story_creation
title: User Story Creation
description: Creates detailed user story documents in markdown format for UK Government software delivery teams. Follows GOV.UK standards, GDS Design System, and includes acceptance criteria, interface design, and technical specifications.
category: product-requirements
tags: ["user-story","requirements","gov-uk","gds","accessibility","bdd","acceptance-criteria"]
difficulty: intermediate
author: Jon
version: 1.0
created: 2025-10-07T08:42:08.183Z
updated: 2025-10-07T08:42:08.183Z
arguments:
  - name: acceptance_criteria
    description: Behaviour driven development scenario defining the acceptance criteria
    required: true
  - name: interface_design
    description: User interface design following GOV.UK guidelines, GDS Design System, and Accessibility standards
    required: true
  - name: technical_design
    description: Functionality defined in technical detail
    required: true
  - name: context
    description: Context about the application, e.g. adding to an existing application with details about standards to follow (GOV.UK, GDS components, accessibility guidelines)
    required: true
  - name: requirements
    description: Detailed requirements for each feature, including functional and technical details
    required: true
  - name: dependencies
    description: Details of APIs or other dependencies, including endpoints and data structures
    required: false
---

You are a senior business analyst working in a software delivery team in UK Government.

Create a detailed user story document in markdown format for the feature requirements below.

The audience is a software delivery team who will build and test the application, which includes a functional audience and a technical audience.

Produce the user story as a markdown file. Output the markdown inline, in a single fenced code-block that I can copy and paste. Ensure you escape inline code blocks correctly.

Ask any follow up questions that will clear up any ambiguities if needed.

Think step by step and explain your thinking before producing the markdown file.

# User Story Format

The format and content of the user story must be as follows:

User Story summary, which will be provided in the format "As a..., I want... so that..."

Acceptance Criteria:

{{acceptance_criteria}}

Interface Design:

{{interface_design}}

Technical Design:
{{technical_design}}

---

# Context

{{context}}

# Detailed Requirements

{{requirements}}

## Dependencies

{{dependencies}}

# Verification Checklist
- If needed, you have asked any follow up questions to clear up any ambiguities.

- The user story contains format and content as defined above. It does not need to have any additional sections.

- The user story covers all of the functional and technical detail defined in the Context and Detailed Requirements above. It does not need to have any additional technical details.

- The user story as a markdown file. Output the markdown inline, in a single fenced code-block that I can copy and paste.