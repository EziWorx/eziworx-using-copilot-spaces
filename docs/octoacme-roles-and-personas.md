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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## UX / Designer

### Role Summary
UX Designers are responsible for understanding user needs and translating them into intuitive, accessible product experiences. They collaborate closely with Product Managers and Developers to ensure that features are user-centred and meet usability standards.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define and maintain design systems and accessibility standards
- Review implemented features against design intent
- Collaborate with PdM on acceptance criteria related to UX

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by validating designs early with users and engineers
- Maintain consistency across the product through shared design standards

### Typical Communication
- Design reviews with developers and PdM
- Usability testing sessions and research readouts
- Feedback via PR comments and design tool annotations

### Interaction with Existing Roles
- Works with **Product Manager** to translate requirements into designs
- Partners with **Developers** during implementation to clarify design intent
- Coordinates with **QA** to validate UI/UX acceptance criteria

---

## Technical Lead / Architect

### Role Summary
The Technical Lead provides architectural guidance, sets engineering standards, and ensures technical decisions align with long-term system goals. They bridge the gap between product requirements and technical execution.

### Responsibilities
- Define and document technical architecture and key design decisions
- Review and approve significant technical changes via ADRs (Architecture Decision Records)
- Identify and mitigate technical risks early in planning
- Mentor developers and support code quality standards
- Ensure non-functional requirements (performance, scalability, security) are addressed

### Goals
- Deliver a maintainable, scalable, and well-documented technical foundation
- Prevent technical debt from accumulating unchecked
- Ensure engineering decisions are transparent and traceable

### Typical Communication
- Architecture reviews and technical design docs
- PR reviews for high-impact changes
- Risk discussions in planning and weekly syncs

### Interaction with Existing Roles
- Works with **Developers** to guide implementation and uphold standards
- Collaborates with **Product Manager** on technical trade-offs
- Supports **Project Manager** in identifying and managing technical risks

---

## DevOps / Platform Engineer

### Role Summary
DevOps/Platform Engineers own the CI/CD pipelines, infrastructure, deployment processes, and observability tooling. They enable fast, reliable, and repeatable delivery.

### Responsibilities
- Build and maintain CI/CD pipelines (tests, linting, security scans, deployments)
- Manage infrastructure provisioning and environment configuration
- Monitor system health, alerts, and dashboards
- Support incident response and post-incident reviews
- Define and enforce deployment and rollback procedures

### Goals
- Enable frequent, low-risk deployments
- Maximize system reliability and observability
- Reduce developer friction through streamlined tooling

### Typical Communication
- Deployment and release planning discussions
- On-call and incident response coordination
- Infrastructure change reviews

### Interaction with Existing Roles
- Partners with **Developers** on pipeline design and local dev environments
- Coordinates with **Project Manager** on deployment windows and release scheduling
- Supports **Technical Lead** on infrastructure architecture decisions

---

## Security Engineer

### Role Summary
Security Engineers identify, assess, and mitigate security risks across the product and infrastructure. They ensure the team ships secure software and responds effectively to security incidents.

### Responsibilities
- Conduct threat modelling and security reviews during planning and design
- Integrate and monitor security scanning tools in CI pipelines
- Review code and infrastructure changes for security vulnerabilities
- Own the security incident runbook and coordinate security incident response
- Maintain compliance with relevant security standards and policies

### Goals
- Shift security left — catch issues early in the lifecycle
- Ensure all releases meet security acceptance criteria
- Build a security-aware engineering culture

### Typical Communication
- Security review sessions during planning and pre-release
- Vulnerability reports and remediation tracking
- Incident response communications

### Interaction with Existing Roles
- Works with **DevOps** to embed security scanning in pipelines
- Advises **Technical Lead** on secure architecture patterns
- Coordinates with **Project Manager** on risk register entries related to security

---

## Business Analyst / Scrum Master

### Role Summary
The Business Analyst (BA) / Scrum Master bridges business needs and technical delivery. They facilitate agile ceremonies, refine requirements, and ensure the team has clear, actionable work items at all times.

### Responsibilities
- Facilitate sprint planning, retrospectives, and daily standups
- Elicit, document, and refine business requirements and acceptance criteria
- Maintain backlog hygiene and support prioritisation with the Product Manager
- Remove impediments and escalate blockers
- Track and report on team velocity, capacity, and delivery metrics

### Goals
- Keep the team focused, unblocked, and delivering consistently
- Ensure requirements are clear before work begins
- Continuously improve team processes through retrospective action items

### Typical Communication
- Agile ceremony facilitation (standups, planning, retros)
- Backlog grooming sessions with PdM and developers
- Status reporting and metrics dashboards

### Interaction with Existing Roles
- Partners with **Product Manager** on backlog refinement and prioritisation
- Supports **Project Manager** with delivery tracking and reporting
- Enables **Developers** by ensuring stories are well-defined before sprint start
