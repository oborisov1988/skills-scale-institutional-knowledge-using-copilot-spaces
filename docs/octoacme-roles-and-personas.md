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

## UX / Product Designers

### Role Summary
UX / Product Designers turn user and business needs into clear user journeys, wireframes, and interaction models that make features usable and valuable. They help teams design solutions that are understandable, consistent, and aligned with customer expectations.

### Responsibilities
- Research user needs, behaviors, and pain points
- Design workflows, prototypes, and interface patterns
- Translate product goals into accessible, testable experiences
- Partner with Product Managers on scope and prioritization
- Review implementation with Developers and QA/Testing for usability and acceptance

### Goals
- Improve usability, clarity, and customer satisfaction
- Reduce rework caused by unclear requirements or weak UX decisions
- Align product experience with business outcomes and service quality goals

### Typical Communication
- Discovery interviews and usability reviews
- Wireframes and design critiques with Product and Engineering
- Acceptance feedback and edge-case validation with QA/Testing

### Interaction with Existing Roles
- Works closely with Product Managers to validate problem framing and prioritize user value
- Coordinates with Developers to ensure feasible design choices and implementation trade-offs
- Partners with QA/Testing to define usability and interface acceptance criteria
- Keeps Project Managers informed of design dependencies or schedule risks

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads define how teams measure value, monitor outcomes, and ensure the right instrumentation and reporting are in place. They connect project delivery to evidence-based decision-making and operational visibility.

### Responsibilities
- Define measurement plans and success metrics
- Specify instrumentation requirements for product events and dashboards
- Validate data quality, reporting accuracy, and analysis readiness
- Support performance reviews and decision-making with stakeholders
- Partner with engineering to ensure analytics data is reliable and actionable

### Goals
- Make business and product outcomes measurable
- Improve confidence in decision-making with data
- Reduce blind spots in quality, adoption, and operational performance

### Typical Communication
- Weekly metric reviews and stakeholder updates
- Event specification discussions with Developers and Product Managers
- Dashboard and reporting review with PMs and leadership

### Interaction with Existing Roles
- Works with Product Managers to translate business goals into measurable outcomes
- Collaborates with Developers to implement nonfunctional and event-tracking requirements
- Supports Project Managers by surfacing risks related to data dependencies, reporting gaps, or milestone readiness
- Helps Stakeholders understand progress and impact with evidence-based reporting

---

## Security / Privacy Leads

### Role Summary
Security / Privacy Leads protect the organization and customers by identifying security, privacy, and compliance requirements early and helping teams build in the right controls. They reduce risk before and during delivery.

### Responsibilities
- Assess security and privacy requirements for features, integrations, and data flows
- Identify and mitigate technical, compliance, and operational risk
- Review controls, threat models, and access patterns
- Partner with delivery teams to close security gaps before release
- Support incident readiness and escalation when risk is elevated

### Goals
- Reduce exposure to security and privacy issues
- Ensure compliance with policy and customer expectations
- Improve release confidence without slowing delivery unnecessarily

### Typical Communication
- Threat-model reviews and risk assessments
- Security design review sessions with Engineering and Product
- Release-readiness and escalation updates to PMs and leadership

### Interaction with Existing Roles
- Advises Product Managers and Project Managers on risk trade-offs, scope, and release timing
- Partners with Developers on secure design patterns and validation checks
- Collaborates with QA/Testing on security-related acceptance criteria and verification
- Keeps Stakeholders informed of material risk, remediation status, and escalations

---

## Operations / Site Reliability Engineers (SREs)

### Role Summary
Operations / SREs ensure that systems are reliable, observable, and operationally sustainable after delivery. They connect product changes to production readiness and ongoing service health.

### Responsibilities
- Define operational readiness, monitoring, and reliability requirements
- Support deployment planning, rollback readiness, and incident response
- Use telemetry to detect service degradation and guide resolution
- Partner with engineering teams on scalability, resilience, and observability
- Help establish ownership for critical service health and support handoffs

### Goals
- Maintain stable, resilient services in production
- Reduce downtime and operational surprises
- Improve the predictability of releases and recovery flows

### Typical Communication
- Release readiness reviews and deployment check-ins
- Post-incident reviews and reliability planning
- Operational dashboards and service health updates with PMs and leadership

### Interaction with Existing Roles
- Coordinates with Developers on deployment readiness, observability, and rollback planning
- Works with QA/Testing on resilience and failure-mode validation
- Supports Project Managers on release dependencies, risk escalation, and communication timing
- Helps Product Managers assess the operational impact of new features or changes

---

## Customer Support / Success Representatives

### Role Summary
Customer Support / Success Representatives bring real customer pain points and support realities into planning and delivery. They help teams design solutions that are easy to adopt, easier to support, and more valuable to customers.

### Responsibilities
- Capture recurring customer issues, requests, and service friction
- Share support readiness needs and customer impact considerations
- Help validate adoption, training, and communication requirements
- Coordinate release communications and known-issue awareness
- Contribute to backlog refinement with real-world customer feedback

### Goals
- Improve customer experience and supportability
- Reduce customer confusion, escalations, and operational friction
- Ensure changes are ready for real-world use and support

### Typical Communication
- Customer feedback loops and issue review sessions
- Release communications and support readiness updates
- Cross-functional planning with Product and Project teams

### Interaction with Existing Roles
- Provides Product Managers with customer insights and prioritization signals
- Coordinates with Project Managers on communications, known issues, and rollout readiness
- Shares product and workflow knowledge with Developers and QA/Testing for edge-case validation
- Supports Stakeholders by highlighting customer impact and adoption considerations

---

## Domain / Subject-Matter Experts

### Role Summary
Domain / Subject-Matter Experts provide specialized knowledge about the business process, regulatory constraints, operational realities, or technical domain being addressed. They help teams avoid incorrect assumptions and reduce rework.

### Responsibilities
- Validate business rules, workflows, and operational constraints
- Review requirements and acceptance criteria for domain accuracy
- Help identify edge cases, dependencies, and risk areas
- Support estimation and prioritization with practical context
- Contribute to decisions that affect regulations, compliance, or industry standards

### Goals
- Improve correctness of solution design and delivery decisions
- Reduce misalignment between business needs and implementation
- Increase confidence that outcomes meet real-world usage conditions

### Typical Communication
- Business process reviews and domain validation sessions
- Requirements sign-off with Product and stakeholder groups
- Working sessions with Developers and QA/Testing around exceptions and edge cases

### Interaction with Existing Roles
- Works with Product Managers to refine requirements and success criteria
- Supports Developers and QA/Testing in validating business rules and edge-case coverage
- Provides Project Managers with context for dependencies, risks, and stakeholder concerns
- Helps Stakeholders make informed decisions by translating domain constraints into practical guidance

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Teams can add or adapt personas based on project size, regulatory needs, and delivery model, while keeping clear accountability, responsibilities, and handoffs across the lifecycle.

