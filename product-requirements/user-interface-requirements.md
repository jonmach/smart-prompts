---
name: user_interface_requirements
title: User Interface Requirements
description: Generate comprehensive frontend requirements based on UI mock-ups, following GDS standards and design patterns. Analyzes interface designs, data models, and API endpoints to create detailed frontend specifications with routing, component design, and accessibility considerations.
category: product-requirements
tags: ["frontend","ui","user-interface","gds","requirements","mock-ups","routing","components"]
difficulty: intermediate
author: Cline
version: 1.0
created: 2025-10-07T08:48:30.654Z
updated: 2025-10-07T08:48:30.654Z
arguments:
  - name: data_model
    description: Database schema and data model definitions
    required: true
  - name: api_endpoints
    description: Backend API endpoint specifications
    required: true
---

I have provided you with mock-ups of the interfaces as attachments. I have also defined the data model and backend API endpoints below.

Write the frontend requirements based on the mock-ups I've uploaded.

Follow GDS standards and give detail about where the pages should sit (route) and any GDS component design elements.

Ask clarifying questions about ambiguities before proceeding.

DATA MODEL:
{{data_model}}

API ENDPOINTS:
{{api_endpoints}}