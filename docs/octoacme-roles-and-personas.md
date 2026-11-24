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

## Release Manager / Deployment Owner

### Role Summary
The Release Manager or Deployment Owner coordinates release readiness and deployment execution, ensuring changes are verified and rollback plans are available.

### Responsibilities
- Plan release windows and coordinate deployment activities
- Confirm acceptance criteria, CI, security checks, and smoke tests are complete
- Maintain rollback and mitigation plans
- Communicate release status, known issues, and verification outcomes
- Coordinate incident escalation during release failures

### Goals
- Deliver predictable, low-risk releases
- Keep rollback options ready and understood
- Improve release observability and stakeholder confidence

### Typical Communication
- Release readiness reviews with the PM and Product Manager
- Merge-readiness and deployment coordination with Developers
- Smoke-test evidence and release acceptance with QA
- Security release gates and findings with the Security Lead
- Operational announcements, runbooks, and known issues with Support / Operations

### Interactions with Existing Roles
- Works with the PM to schedule releases and escalate schedule or dependency risks.
- Works with the Product Manager to align release scope and stakeholder expectations.
- Works with Developers to confirm merge readiness and deployment requirements.
- Works with QA to verify acceptance and smoke-test results.
- Coordinates with Security, Support / Operations, and Stakeholders to complete release readiness and communications.

---

## Security Lead

### Role Summary
The Security Lead advises on security requirements, reviews security findings, and ensures appropriate security controls and escalation paths are applied to project work.

### Responsibilities
- Define relevant threat and control requirements
- Review security findings and recommend mitigations
- Verify security acceptance criteria before sensitive releases
- Participate in security incident triage and escalation
- Promote secure design and operational practices

### Goals
- Reduce security exposure and release risk
- Ensure security findings are understood, owned, and resolved
- Maintain consistent incident and escalation practices

### Typical Communication
- Security requirements and risk reviews with Product and Project Managers
- Threat modeling and remediation coordination with Developers
- Security test findings and validation with QA
- Release gates with the Release Manager
- Incident updates with the PM and Stakeholders

### Interactions with Existing Roles
- Advises the Product Manager on security risks that affect scope or outcomes.
- Partners with the PM to track security risks and escalation decisions.
- Works with Developers to design mitigations and implement secure changes.
- Works with QA to validate security fixes and test coverage.
- Coordinates with the Release Manager on release gates and rollback decisions.

---

## UX / Design Lead

### Role Summary
The UX / Design Lead represents users throughout discovery and delivery, turning customer needs into clear, usable designs and testable acceptance criteria.

### Responsibilities
- Lead or contribute to user research and discovery
- Create interaction and visual design guidance
- Translate usability findings into clear requirements
- Help define usability acceptance criteria
- Validate designs against customer and accessibility needs

### Goals
- Improve usability and customer value
- Catch experience risks before implementation
- Keep design decisions consistent across the product

### Typical Communication
- Outcome and prioritization discussions with the Product Manager
- Feasibility and implementation reviews with Developers
- Usability and acceptance validation with QA
- Design feedback and validation sessions with Stakeholders
- Delivery scope, timeline, and dependency updates with the PM

### Interactions with Existing Roles
- Collaborates with the Product Manager to turn customer needs and success metrics into usable solutions.
- Works with Developers to ensure designs are feasible and implemented consistently.
- Partners with QA to define and validate usability and accessibility acceptance criteria.
- Consults with the PM about design dependencies and delivery risks.
- Involves Stakeholders in reviews and validation as appropriate.

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead defines how project outcomes are measured, ensuring telemetry and reporting support evidence-based decisions.

### Responsibilities
- Define success metrics, baselines, and measurement plans
- Specify and validate product instrumentation
- Maintain dashboards and reporting approaches
- Analyze post-release behavior and outcome trends
- Communicate findings and data limitations

### Goals
- Produce reliable, actionable outcome data
- Improve the team's ability to make evidence-based decisions
- Detect and explain unexpected changes after release

### Typical Communication
- Metric definitions and prioritization with the Product Manager
- Instrumentation requirements with Developers
- Measurement validation with QA
- Outcome and trend reporting with the PM and Stakeholders
- Post-release analysis with the Release Manager

### Interactions with Existing Roles
- Works with the Product Manager to define and refine success measures.
- Partners with Developers to add reliable telemetry and reporting.
- Works with QA to validate that measurements and dashboards are accurate.
- Provides the PM and Stakeholders with delivery and outcome insights.
- Helps the Release Manager assess post-release impact and identify follow-up work.

---

## Support / Operations Liaison

### Role Summary
The Support / Operations Liaison represents operational readiness and customer support needs across planning, release, and incident response.

### Responsibilities
- Prepare operational readiness materials and support escalation contacts
- Maintain runbooks, known-issue summaries, and support communications
- Reproduce and triage customer-impacting issues
- Feed support insights into backlog prioritization
- Coordinate incident handoffs and customer updates

### Goals
- Improve operational readiness and response
- Reduce the gap between delivery and support teams
- Bring recurring customer and operational issues into project decisions

### Typical Communication
- Operational risks and readiness reviews with the PM
- Reproduction, fixes, and known issues with Developers and QA
- Customer impact and prioritization with the Product Manager
- Release announcements and incident handoffs with the Release Manager
- Incident summaries and status updates with Stakeholders

### Interactions with Existing Roles
- Works with the PM to identify operational risks and readiness gaps.
- Partners with Developers and QA on reproduction, fixes, and verification.
- Shares customer insights with the Product Manager to inform prioritization.
- Coordinates with the Release Manager on deployment communications and rollback readiness.
- Provides Stakeholders with clear operational and incident status updates.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Projects should assign personas based on their scope and team structure. Related responsibilities may be shared, while each project should document clear ownership for decisions and handoffs.
