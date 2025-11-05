# Spec-Driven Development Methodology

## Overview

This document defines my preferred approach to spec-driven development using Amazon Q Developer. When I request "spec-driven development" for a project, follow this structured methodology with mandatory interactive checkpoints.

## Phase 1: Requirements Gathering

When starting spec-driven development:

1. **Requirements Document**
  - Create a comprehensive requirements.md file
  - Include functional and non-functional requirements
  - Define success criteria and constraints
  - Identify target users and use cases
  - Define acceptance criteria for each requirement
  - **MANDATORY CHECKPOINT**: Present requirements.md and ask: "Please review the requirements document. Should I proceed to create the system design, or would you like changes?"

## Phase 2: Technical Specifications

2. **Architecture Design**
  - Create design.md with system design
  - Define component interactions and data flow
  - Specify technology stack and infrastructure requirements
  - Include security and scalability considerations
  - **MANDATORY CHECKPOINT**: Present design.md and ask: "Please review the system design. Should I proceed to create the implementation tasks, or would you like modifications?"

3. **Implementation Tasks**
  - Generate tasks.md with specific development tasks
  - Break down user stories into actionable development work
  - Include estimates and dependencies
  - Define completion criteria for each task
  - **MANDATORY CHECKPOINT**: Present tasks.md and ask: "Please review the implementation plan. Are you satisfied with the complete specification set?"

## File Structure Standards

When creating spec-driven projects, organize files as:
```
<parent folder>/
├── specs/
│   ├── requirements.md
│   ├── design.md
│   └── tasks.md
├── src/
└── tests/
```

## Documentation Standards

- Use clear, concise language in all specifications
- Include examples and use cases where helpful
- Maintain consistency in formatting and structure
- Update specifications as requirements evolve
- Link related documents and reference dependencies

## Interactive Development Workflow

1. Always start with requirements gathering before coding
2. **MANDATORY**: After creating requirements.md, STOP and ask for user review/approval
3. **MANDATORY**: After creating design.md, STOP and ask for user review/approval
4. **MANDATORY**: After creating tasks.md, STOP and ask for user review/approval
5. Never proceed to the next phase without explicit user approval
6. Use specifications to guide all development decisions
7. Update documentation as the project evolves
8. Reference specifications when debugging or adding features

## Checkpoint Protocol

- **Phase 1 Checkpoint**: "Please review the requirements document. Should I proceed to create the system design, or would you like changes?"
- **Phase 2 Checkpoint**: "Please review the system design. Should I proceed to create the implementation tasks, or would you like modifications?"
- **Phase 3 Checkpoint**: "Please review the implementation plan. Are you satisfied with the complete specification set?"
- **Critical Rule**: Never create multiple specification documents in a single response

## Quality Criteria

Specifications should be:
- **Complete**: Cover all functional and non-functional requirements
- **Consistent**: Use consistent terminology and patterns
- **Testable**: Include criteria that can be validated
- **Maintainable**: Easy to update as requirements change
- **Accessible**: Clear to both technical and non-technical stakeholders

