# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Role Coverage and Project-Dependent Participation

- Core delivery roles for most projects are Developers, Product Managers, and Project Managers.
- Additional personas below are project-dependent and are staffed based on scope, risk, regulatory context, and customer impact.
- On smaller projects, one person may hold multiple roles. When this happens, document who owns each decision right to keep accountability clear.
- Related lifecycle process references: `octoacme-project-initiation.md`, `octoacme-project-planning.md`, `octoacme-execution-and-tracking.md`, `octoacme-release-and-deployment.md`, `octoacme-risks-and-communication.md`, and `octoacme-retrospective-and-continuous-improvement.md`.

---

## Executive Sponsor

### Role Summary
Provides strategic direction, funding support, and escalation backing to keep delivery aligned with business priorities.

### Responsibilities
- Confirm strategic goals, constraints, and expected outcomes
- Sponsor budget and unblock high-impact organizational dependencies
- Review major risks, trade-offs, and release readiness escalations

### Goals
- Ensure initiatives deliver measurable business value
- Reduce stalled decisions and unresolved escalations

### Decision Rights & Accountability
- Accountable for strategic go/no-go decisions and funding continuity
- Approves major scope or priority shifts with Product and Project Managers

### Collaboration & Handoffs
- Aligns with Product Managers on outcomes and value
- Partners with Project Managers on risk escalation and governance
- Engages Developers, QA/Testing, and stakeholders when trade-offs affect delivery confidence

### Typical Communication & Lifecycle Touchpoints
- Initiation charter approval, milestone reviews, release checkpoints, retrospective outcome review

### Coverage
- Project-dependent

---

## Business Analyst or Requirements Lead

### Role Summary
Translates business needs into clear, testable requirements and workflow definitions.

### Responsibilities
- Elicit and document requirements, assumptions, and constraints
- Refine acceptance criteria with Product Managers and QA/Testing
- Maintain requirement traceability through delivery and release

### Goals
- Reduce ambiguity and rework
- Improve requirement quality and downstream testability

### Decision Rights & Accountability
- Accountable for requirement clarity and completeness
- Recommends requirement decisions; Product Managers retain product priority decisions

### Collaboration & Handoffs
- Hands refined requirements to Developers and QA/Testing
- Supports Project Managers with dependency and scope impact analysis
- Validates requirement intent with stakeholders

### Typical Communication & Lifecycle Touchpoints
- Discovery workshops, backlog refinement, sprint planning, UAT/release readiness reviews

### Coverage
- Project-dependent

---

## UX/Product Designer or User Researcher

### Role Summary
Represents user needs through design artifacts, usability validation, and research evidence.

### Responsibilities
- Create user flows, prototypes, and interaction guidance
- Conduct research and usability validation
- Define accessibility and experience quality requirements

### Goals
- Improve adoption, usability, and user confidence
- Reduce post-release usability defects

### Decision Rights & Accountability
- Accountable for experience quality recommendations and design consistency
- Shares approval accountability for UX acceptance criteria with Product Managers

### Collaboration & Handoffs
- Hands design specs to Developers and QA/Testing
- Aligns feasibility trade-offs with Technical Lead/Architect and Developers
- Shares findings with stakeholders and Product Managers for prioritization

### Typical Communication & Lifecycle Touchpoints
- Discovery research, planning/design reviews, execution usability checks, release communications

### Coverage
- Project-dependent

---

## Technical Lead or Architect

### Role Summary
Guides technical direction, architecture, and implementation trade-offs across delivery.

### Responsibilities
- Define architecture patterns and integration approaches
- Surface technical risks, dependencies, and non-functional requirements
- Support estimation, sequencing, and technical decision logging

### Goals
- Maintain system reliability, scalability, and maintainability
- Reduce technical debt and architecture-related rework

### Decision Rights & Accountability
- Accountable for technical direction and architecture standards
- Approves major technical design decisions with Developers

### Collaboration & Handoffs
- Guides Developers on implementation constraints
- Partners with Project Managers on dependency and risk planning
- Coordinates with QA/Testing, Security/Privacy, and DevOps/Operations on readiness criteria

### Typical Communication & Lifecycle Touchpoints
- Initiation feasibility checks, planning/design reviews, execution architecture reviews, release go/no-go inputs

### Coverage
- Project-dependent

---

## QA/Test Lead

### Role Summary
Owns test strategy, quality risk visibility, and release quality recommendations.

### Responsibilities
- Define test approach, environments, and quality gates
- Track defect trends and verify acceptance criteria coverage
- Report quality risks and release blockers

### Goals
- Improve release confidence and defect containment
- Ensure quality standards are consistently met

### Decision Rights & Accountability
- Accountable for test strategy and quality risk reporting
- Recommends release readiness from a quality perspective

### Collaboration & Handoffs
- Works with Developers on testability and defect triage
- Aligns acceptance scope with Product Managers
- Coordinates with Project Managers on quality risks and stakeholder updates

### Typical Communication & Lifecycle Touchpoints
- Planning test strategy, execution defect reviews, pre-release quality signoff, retrospective quality insights

### Coverage
- Core on most software delivery efforts; project-dependent only for very small low-risk changes

---

## Security/Privacy Partner

### Role Summary
Ensures security and privacy requirements are identified, tracked, and validated through release.

### Responsibilities
- Identify applicable security/privacy obligations and controls
- Review threat, data handling, and compliance risks
- Support incident readiness and escalation alignment

### Goals
- Prevent avoidable security/privacy defects
- Reduce compliance and incident risk at release

### Decision Rights & Accountability
- Accountable for security/privacy risk assessment inputs
- Can block release recommendations when critical unresolved risks remain

### Collaboration & Handoffs
- Works with Technical Lead/Architect and Developers on secure implementation
- Partners with QA/Testing on security validation scope
- Informs Project Managers and stakeholders on residual risk decisions

### Typical Communication & Lifecycle Touchpoints
- Initiation risk screening, planning control definition, execution risk reviews, release security signoff, retrospective incident learnings

### Coverage
- Project-dependent, but strongly recommended for customer-facing or regulated work

---

## DevOps/Site Reliability or Operations Lead

### Role Summary
Owns deployment readiness, service operability, and production stability practices.

### Responsibilities
- Define release automation, environment readiness, and rollback plans
- Ensure monitoring, alerting, and runbook coverage
- Coordinate incident response readiness and post-release stability tracking

### Goals
- Improve deployment reliability and service uptime
- Reduce mean time to detect and recover from incidents

### Decision Rights & Accountability
- Accountable for operational readiness criteria and deployment risk visibility
- Approves go-live from infrastructure/operations readiness perspective

### Collaboration & Handoffs
- Partners with Developers and Technical Lead/Architect on CI/CD and runtime concerns
- Works with QA/Testing on environment/test parity and release checks
- Aligns with Project Managers and stakeholders on operational risk communication

### Typical Communication & Lifecycle Touchpoints
- Planning release strategy, execution deployment rehearsals, release command center, retrospective reliability review

### Coverage
- Project-dependent; core for production-impacting changes

---

## Customer Support or Service Owner

### Role Summary
Represents customer support readiness, service continuity, and incident communication needs.

### Responsibilities
- Prepare support playbooks, known-issue guidance, and escalation paths
- Bring customer pain points and service feedback into prioritization
- Coordinate launch readiness for support teams

### Goals
- Improve customer experience during and after release
- Reduce time to resolve customer-facing issues

### Decision Rights & Accountability
- Accountable for support readiness and communication quality
- Recommends rollout pacing based on customer impact risk

### Collaboration & Handoffs
- Receives launch and risk details from Product and Project Managers
- Works with Developers, QA/Testing, and DevOps/Operations on support diagnostics
- Communicates customer-impact updates to stakeholders

### Typical Communication & Lifecycle Touchpoints
- Planning support readiness, release-day updates, post-release issue triage, retrospective service insights

### Coverage
- Project-dependent

---

## Data/Analytics Partner

### Role Summary
Defines measurement strategy and provides evidence on product and delivery outcomes.

### Responsibilities
- Define instrumentation, event tracking, and reporting needs
- Validate data quality for decision-making
- Analyze performance against success metrics

### Goals
- Enable evidence-based product and project decisions
- Improve outcome predictability and learning loops

### Decision Rights & Accountability
- Accountable for analytics integrity and interpretation quality
- Advises Product Managers and stakeholders on outcome performance

### Collaboration & Handoffs
- Partners with Developers and Technical Lead/Architect on instrumentation implementation
- Aligns with Product Managers on success metrics and experiments
- Supports Project Managers and stakeholders with outcome reporting

### Typical Communication & Lifecycle Touchpoints
- Initiation metric definition, planning instrumentation scope, execution quality checks, release impact readouts, retrospective trend analysis

### Coverage
- Project-dependent

---

## Change/Communications Lead

### Role Summary
Coordinates internal and external communications, enablement, and adoption planning.

### Responsibilities
- Build communication plans for rollout milestones and risks
- Coordinate training, enablement artifacts, and stakeholder messaging
- Track adoption signals and communication effectiveness

### Goals
- Improve rollout clarity and organizational adoption
- Reduce change friction and communication gaps

### Decision Rights & Accountability
- Accountable for communication plan quality and execution
- Recommends readiness for broad announcements and enablement rollout

### Collaboration & Handoffs
- Works with Product and Project Managers on timeline and message alignment
- Coordinates with Customer Support/Service Owner and stakeholders on launch messaging
- Incorporates Developer and QA/Testing inputs into technical change communications

### Typical Communication & Lifecycle Touchpoints
- Initiation alignment, planning communication drafts, execution stakeholder updates, release announcements, retrospective adoption review

### Coverage
- Project-dependent

---

## Responsibility and Interaction Overview

| Lifecycle Area | Core Roles (always expected) | Project-Dependent Roles (as needed) | Typical Accountable Outcome |
| --- | --- | --- | --- |
| Initiation | Product Managers, Project Managers, Developers | Executive Sponsor, Business Analyst, UX/Product Designer, Technical Lead, Security/Privacy, Data/Analytics, Change/Communications | Clear charter, outcomes, scope boundaries, and initial risk profile |
| Planning | Product Managers, Project Managers, Developers, QA/Test Lead | Business Analyst, UX/Product Designer, Technical Lead, Security/Privacy, DevOps/Operations, Data/Analytics, Change/Communications | Prioritized plan, acceptance criteria, test/ops readiness plan, and dependency map |
| Execution | Developers, Product Managers, Project Managers, QA/Test Lead | Technical Lead, UX/Product Designer, Security/Privacy, DevOps/Operations, Data/Analytics | Working increments with validated quality, managed risks, and tracked outcomes |
| Release | Developers, Product Managers, Project Managers, QA/Test Lead | Executive Sponsor, Security/Privacy, DevOps/Operations, Customer Support/Service Owner, Change/Communications | Coordinated go-live decision, readiness confirmation, and stakeholder/customer communication |
| Risk Management | Product Managers, Project Managers, Developers | Executive Sponsor, Technical Lead, Security/Privacy, DevOps/Operations, QA/Test Lead | Timely escalation, mitigation ownership, and documented decision log |
| Retrospectives | Product Managers, Project Managers, Developers, QA/Test Lead | Executive Sponsor, Customer Support/Service Owner, Data/Analytics, Change/Communications | Actionable improvements across product, process, quality, and adoption |

In this matrix, "core" means typically staffed on most efforts, while "project-dependent" means engaged based on project context. On smaller efforts, the same person may represent multiple roles, but each accountable outcome should still have a clearly named owner.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
