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

## Additional personas to consider
As projects grow in complexity, additional specialized roles often appear. Explicitly documenting these personas, their responsibilities, and their interactions with core roles improves clarity, reduces overlap, and speeds onboarding.

### UX Designer
Role Summary
- Designs user interfaces and interaction patterns, ensuring usability and accessibility.

Responsibilities
- Create wireframes, prototypes, and design specs
- Conduct usability testing and incorporate feedback
- Define user interaction acceptance criteria and collaborate on accessibility

Interactions with existing roles
- Product Manager: Collaborates on user needs, prioritization, and acceptance criteria
- Developers: Shares design assets and implementation guidance, participates in design reviews
- QA: Works with QA to define usability-related test cases and acceptance criteria

Typical artifacts
- Wireframes, high-fidelity mockups, design system components, usability test reports

### DevOps Engineer
Role Summary
- Manages CI/CD, infrastructure as code, deployments, and observability to enable reliable delivery.

Responsibilities
- Design and maintain deployment pipelines and automation
- Define and maintain infrastructure as code and configuration
- Implement and maintain monitoring, logging, and alerting
- Support incident response and post-incident analysis

Interactions with existing roles
- Developers: Collaborates on build/release pipelines and environment parity
- QA: Coordinates staging environments and test automation execution
- Project Manager: Communicates deployment windows, risks, and rollback strategies

Typical artifacts
- CI/CD pipeline definitions, runbooks, infrastructure templates, dashboards

### Security Champion
Role Summary
- Advocates for security best practices within the delivery team and ensures threats are considered early.

Responsibilities
- Participate in threat modeling and risk assessments
- Review designs and code for security implications
- Coordinate security scans and follow-up actions
- Escalate security issues to the Security team when required

Interactions with existing roles
- Developers: Works closely to remediate security issues and incorporate secure coding standards
- Project Manager: Escalates security risks and helps prioritize mitigations
- Product Manager: Advises on security-related acceptance criteria and data handling

Typical artifacts
- Threat models, security checklists, scan reports, remediation tickets

### Business Analyst
Role Summary
- Bridges business stakeholders and delivery teams, clarifying requirements and acceptance criteria.

Responsibilities
- Elicit and document business requirements and workflows
- Break down business needs into user stories and acceptance criteria
- Validate solutions with stakeholders and support UAT

Interactions with existing roles
- Product Manager: Helps refine requirements and ensures stakeholder alignment
- Developers: Provides clarification and acceptance criteria during implementation
- QA: Supports test case definition and UAT coordination

Typical artifacts
- Requirements documents, process flows, user story templates, UAT plans

### Customer Support Lead
Role Summary
- Represents the customer-facing support organization and ensures product changes consider supportability and known issues.

Responsibilities
- Provide insights from support tickets and customer feedback
- Prepare release notes, KB articles, and support runbooks
- Triage post-release incidents and communicate patterns to the team

Interactions with existing roles
- Product Manager: Shares customer impact, prioritizes fixes, and informs roadmap
- Developers/QA: Provides reproducible reports and assists in triage
- Project Manager: Coordinates communications for major incidents and escalations

Typical artifacts
- KB articles, incident summaries, support runbooks, release notes

---

## Guidance for adding new personas
- Define a Role Summary, Responsibilities, Interactions with core roles, and Typical Artifacts
- Keep entries concise (1–2 short sections each) and link to more detailed guidance if needed
- Add a cross-reference table to show handoffs (e.g., who owns release readiness, who notifies stakeholders)

