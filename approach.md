---
title: 'Approach'
description: 'Documentation-Driven Development Approach'
---

# Documentation-Driven Development Approach

This document outlines our systematic approach to building software through documentation-first development.

## 0. Platform Vision Alignment

The foundation of our development process is the `overview.md` document, which serves as the source of truth for ZenBot's vision and purpose. As we gain deeper understanding of the platform's capabilities and requirements, we continuously refine this document to maintain clarity about what we're building.

## 1. Requirements Evolution

1. Start with draft requirements in `docs/draft/`

2. Create versioned documentation in `docs/v1/`

3. Maintain living documentation that evolves with the codebase

4. Cross out completed tasks in TODO.md as development progresses

5. Regularly review and update OVERVIEW.md to reflect enhanced understanding

## 2. Documentation Structure

Establish a clear documentation hierarchy:

* `OVERVIEW.md`: Platform vision and core purpose

* `TODO.md`: Tracks implementation progress

* `ARCHITECTURE.md`: Records key technical decisions

* `SCHEMA.md`: Details database structure and business logic

* Additional documentation as needed

## 3. Development Rules Integration

1. Create `.windsurf-rules.json` to enforce documentation compliance

2. Add rules that require:

   * Alignment with platform vision

   * Checking requirements before changes

   * Following architectural decisions

   * Adhering to documented patterns

   * Updating documentation with code changes

## 4. Documentation Update Flow

1. Vision Alignment

   * Review changes against OVERVIEW.md

   * Update vision document as understanding deepens

   * Ensure features align with core purpose

2. Make architectural decisions

   * Document in ARCHITECTURE.md

   * Update TODO.md with new tasks

   * Add enforcement rules to windsurf-rules

3. Design technical components

   * Create specific documentation

   * Update architectural documentation

   * Add relevant tasks to TODO.md

4. Implementation

   * Reference documentation during development

   * Cross out completed tasks

   * Update documentation with any deviations

## 5. Living Documentation Principles

1. **Single Source of Truth**

   * Platform vision in OVERVIEW.md

   * All documentation in `docs/v1/`

   * Clear versioning of requirements

   * Automated enforcement through rules

2. **Documentation Types**

   * Vision (OVERVIEW.md)

   * Planning (TODO.md)

   * Decisions (ARCHITECTURE.md)

   * Implementation Details (SCHEMA.md)

   * Process Documentation (APPROACH.md)

3. **Continuous Updates**

   * Documentation evolves with code

   * Tasks marked as complete

   * New requirements added as discovered

   * Vision refined as understanding grows

## 6. Enforcement Mechanism

1. Use windsurf-rules to:

   * Enforce vision alignment

   * Enforce documentation checks

   * Maintain consistency

   * Ensure documentation stays current

2. Rules should verify:

   * Changes align with platform vision

   * Documentation is consulted

   * Changes align with architecture

   * Tasks are tracked and updated

## Benefits of This Approach

1. **Clear Vision Alignment**

   * Every feature serves the core purpose

   * Consistent platform direction

   * Shared understanding of goals

2. **Clear Progress Tracking**

   * Visible task completion

   * Documentation always current

   * Requirements clearly defined

3. **Consistent Development**

   * Architectural consistency

   * Enforced best practices

   * Reduced technical debt

4. **Better Collaboration**

   * Shared understanding

   * Clear decision records

   * Easy onboarding

## Maintaining the Process

1. Regular vision review and refinement

2. Regular documentation reviews

3. Update rules as patterns emerge

4. Refine documentation structure

5. Keep TODO list current

6. Document new architectural decisions