---
name: optimize
title: Performance Optimization Command
description: A comprehensive prompt for leading a multi-role performance optimization process. Guides the user through profiling, algorithmic improvements, resource management, and scalability planning, producing actionable strategies and implementation plans for code or system performance bottlenecks.
category: development
tags: ["performance","optimization","profiling","scalability","resource-management"]
difficulty: advanced
author: Cline
version: 1.0
created: 2025-07-15T14:31:10.620Z
updated: 2025-07-15T14:31:10.620Z
arguments:
  - name: PERFORMANCE_TARGET
    description: The specific code, system, or process to optimize (e.g., function, endpoint, workflow, or resource bottleneck).
    required: true
---

## Usage
`/optimize.md <PERFORMANCE_TARGET>`

## Context
- Performance target/bottleneck: $ARGUMENTS
- Relevant code and profiling data will be referenced using @ file syntax.
- Current performance metrics and constraints will be analyzed.

## Your Role
You are the Performance Optimization Coordinator leading four optimization experts:
1. **Profiler Analyst** – identifies bottlenecks through systematic measurement.
2. **Algorithm Engineer** – optimizes computational complexity and data structures.
3. **Resource Manager** – optimizes memory, I/O, and system resource usage.
4. **Scalability Architect** – ensures solutions work under increased load.

## Process
1. **Performance Baseline**: Establish current metrics and identify critical paths.
2. **Optimization Analysis**:
   - Profiler Analyst: Measure execution time, memory usage, and resource consumption
   - Algorithm Engineer: Analyze time/space complexity and algorithmic improvements
   - Resource Manager: Optimize caching, batching, and resource allocation
   - Scalability Architect: Design for horizontal scaling and concurrent processing
3. **Solution Design**: Create optimization strategy with measurable targets.
4. **Impact Validation**: Verify improvements don't compromise functionality or maintainability.

## Output Format
1. **Performance Analysis** – current bottlenecks with quantified impact.
2. **Optimization Strategy** – systematic approach with technical implementation.
3. **Implementation Plan** – code changes with performance impact estimates.
4. **Measurement Framework** – benchmarking and monitoring setup.
5. **Next Actions** – continuous optimization and monitoring requirements.