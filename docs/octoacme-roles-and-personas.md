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

## QA / Testing Engineer

### Role Summary
QA/Testing Engineers validate that software meets functional and non-functional requirements before release. They partner closely with Developers and Product Managers to define acceptance criteria and ensure quality gates are met at every stage of delivery.

### Responsibilities
- Design, write, and maintain automated and manual test suites
- Define and enforce the Definition of Done and acceptance criteria with the team
- Identify, document, and track defects through resolution
- Perform regression, integration, and exploratory testing
- Collaborate with Developers on testability and shift-left quality practices

### Goals
- Prevent defects from reaching production
- Improve test coverage and reduce manual testing overhead
- Enable fast, confident releases through reliable automation

### Typical Communication
- Sprint planning and backlog refinement to clarify acceptance criteria
- Bug reports and defect triage with Developers
- Release readiness sign-off with Project Manager and Product Manager

### Interaction with Existing Roles
- Works with **Developers** on test coverage, bug fixes, and testability design
- Works with **Product Managers** to clarify acceptance criteria and edge cases
- Reports release readiness status to **Project Managers**

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the outcome of a project. They provide strategic input, approve key decisions, and consume project outputs. They may include executives, business unit owners, customers, or partner teams.

### Responsibilities
- Provide business context, constraints, and success criteria at project initiation
- Review and approve major milestones, scope changes, and risk escalations
- Offer feedback on deliverables during demos and reviews
- Champion the project within their respective organizations

### Goals
- Ensure the project delivers expected business value
- Stay informed of progress and risks without being bottlenecks
- Align the project with broader organizational priorities

### Typical Communication
- Monthly stakeholder updates and project status reports
- Ad-hoc escalations for high-impact risks or scope changes
- Demo attendance at key milestones

### Interaction with Existing Roles
- Engage with **Project Managers** for status, risk, and decision escalations
- Align with **Product Managers** on outcome metrics and roadmap priorities
- Receive output from **Developers** in the form of demos and shipped features

---

## Technical Lead

### Role Summary
The Technical Lead is an experienced engineer who provides technical direction for the team. They guide architectural decisions, mentor developers, and ensure the technical approach aligns with quality, scalability, and maintainability standards.

### Responsibilities
- Define and communicate technical architecture and design patterns
- Review and approve significant technical decisions and pull requests
- Identify and mitigate technical risks and debt
- Mentor Developers and support their growth
- Serve as the technical point of contact for cross-team dependencies

### Goals
- Ensure the codebase is maintainable, scalable, and well-tested
- Reduce technical risk before it impacts delivery
- Align technical solutions with product and business goals

### Typical Communication
- Design and architecture review sessions
- Code reviews and pair programming
- Technical risk updates to the Project Manager

### Interaction with Existing Roles
- Partners with **Developers** on design, code quality, and mentorship
- Advises **Product Managers** on technical feasibility and trade-offs
- Provides technical risk input to **Project Managers** for planning

---

## UX / Design Lead

### Role Summary
The UX/Design Lead is responsible for the user experience and visual design of the product. They translate user research and product requirements into intuitive interfaces and interaction patterns, ensuring the product is accessible and delightful to use.

### Responsibilities
- Conduct user research, usability testing, and competitive analysis
- Create wireframes, prototypes, and high-fidelity design artifacts
- Maintain and evolve the design system and component library
- Collaborate with Product Managers on feature discovery and problem framing
- Partner with Developers to ensure faithful implementation of designs

### Goals
- Deliver consistent, accessible, and high-quality user experiences
- Reduce friction and increase user satisfaction
- Establish shared design language across the product

### Typical Communication
- Design reviews and prototype walkthroughs
- Usability testing readouts with Product Managers and Developers
- Design handoff sessions with engineering

### Interaction with Existing Roles
- Collaborates with **Product Managers** on user needs and problem definitions
- Works with **Developers** on implementation details and design system usage
- Presents design decisions and user research findings to **Stakeholders**

---

## DevOps / Release Engineer

### Role Summary
DevOps/Release Engineers build and maintain the infrastructure, CI/CD pipelines, and release processes that enable the team to ship software reliably and efficiently. They bridge the gap between development and operations.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and deployment automation
- Manage infrastructure provisioning, configuration, and monitoring
- Define and enforce release procedures and rollback plans
- Monitor system health and respond to production incidents
- Collaborate with Developers and Technical Leads on infrastructure requirements

### Goals
- Enable fast, safe, and repeatable deployments
- Maintain high availability and system reliability
- Reduce toil through automation and tooling improvements

### Typical Communication
- Release readiness reviews with Project Managers and QA
- Incident postmortems and runbook updates
- Infrastructure change proposals with Technical Leads

### Interaction with Existing Roles
- Partners with **Developers** and **Technical Leads** on deployment architecture and environment parity
- Coordinates release windows and deployment steps with **Project Managers**
- Supports **QA/Testing Engineers** with test environment provisioning and pipeline stability

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

