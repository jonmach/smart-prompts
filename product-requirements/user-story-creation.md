---
name: user_story_creation
title: User Story Creation
description: Creates detailed user story documents in markdown format for UK Government software delivery teams. Follows GDS Design System standards and produces BDD scenarios with acceptance criteria. Designed for business analysts working with functional and technical audiences.
category: product-requirements
tags: ["user-story","bdd","requirements","gov-uk","government","gds","acceptance-criteria"]
difficulty: intermediate
author: Cline User
version: 1.0
created: 2025-10-07T08:23:18.933Z
updated: 2025-10-07T08:23:18.933Z
arguments:
  - name: context
    description: Background information about the application or feature being developed. Include details about existing systems, GOV.UK standards requirements, and any relevant constraints.
    required: true
  - name: requirements
    description: Detailed functional and technical requirements for each feature to be implemented. Include specific behaviors, constraints, and expected outcomes.
    required: true
  - name: apis
    description: API dependencies and specifications. Include endpoints, request/response formats, and any relevant technical details about external services or integrations.
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

User Story:
[User story summary in "AS A, I WANT, SO THAT" format. This must be functional and must omit technical details]

Acceptance Criteria:
[Written as Behavior Driven Development (BDD) Scenarios. The BDD scenarios should focus more on functional/user-driven actions. Omit technical details. Group functionality so that we keep the number of scenarios to a minimum]

Interface Design:
[Relevant user interface design. This is a GOV.UK Application so it should follow GOV.UK guidelines including the GDS Design System and Accessibility. Ensure you include the GDS Components needed for the interface]

Technical Design:
[The functionality defined in technical detail. Include the API Responses as examples from below]

---

# Context

{{context}}

# Detailed Requirements

{{requirements}}

## APIS

{{apis}}

# Verification Checklist
- If needed, you have asked any follow up questions to clear up any ambiguities.

- The user story contains format and content as defined above. It does not need to have any additional sections.

- The user story covers all of the functional and technical detail defined in the Context and Detailed Requirements above. It does not need to have any additional technical details.

- The user story as a markdown file. Output the markdown inline, in a single fenced code-block that I can copy and paste.