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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define quality standards, create test strategies, and validate that features meet acceptance criteria and quality gates before release. They collaborate with developers and product managers to ensure testability and comprehensive coverage.

### Responsibilities
- Develop test plans and test cases aligned with acceptance criteria
- Create and maintain automated test suites for regression prevention
- Coordinate manual testing and user acceptance testing (UAT)
- Identify quality risks and recommend mitigation strategies
- Validate features against Definition of Done before marking complete
- Report defect trends and quality metrics

### Goals
- Ensure features ship with high quality and minimal production defects
- Reduce time spent on rework and post-release issue triage
- Enable faster releases through efficient testing and automation

### Typical Communication
- Test plan reviews with developers and product managers
- Defect reports and blockers escalated in daily standups
- Quality metrics shared in weekly status reports

### How QA/Testing Lead interacts with other roles
- **With Developers**: Collaborates on test case design and provides feedback on testability during development
- **With Product Managers**: Reviews acceptance criteria to ensure comprehensive test coverage
- **With Project Managers**: Reports quality risks and blockers that impact timeline

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, conduct technical design reviews, and help developers navigate complex technical decisions. They identify technical risks early and propose mitigation strategies.

### Responsibilities
- Participate in technical design reviews for significant features
- Provide guidance on technical trade-offs and best practices
- Identify technical risks, scalability concerns, and debt implications
- Support developers in estimating technical complexity
- Review pull requests for architectural alignment
- Mentor junior developers and share technical knowledge

### Goals
- Maintain system health, scalability, and maintainability
- Reduce technical debt and technical risk in new features
- Enable faster delivery by providing clear technical direction

### Typical Communication
- Technical design discussions and architecture reviews
- Code review feedback and technical guidance
- Technical risk identification in project planning phase

### How Technical Lead/Architect interacts with other roles
- **With Developers**: Provides design guidance and mentorship; reviews complex PRs for architectural alignment
- **With Project Managers**: Flags technical risks during planning; helps estimate complexity of work
- **With QA/Testing Leads**: Advises on testability and integration testing strategies

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps Engineers manage deployment pipelines, production infrastructure, and release processes. They work with developers and QA to ensure safe, reliable deployments and maintain production observability.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Configure environments (staging, production) and infrastructure
- Implement monitoring, alerting, and logging for production systems
- Support release execution and coordinate rollback if needed
- Document deployment procedures and runbooks
- Ensure security scanning and compliance checks in CI

### Goals
- Enable fast, safe, reliable releases to production
- Minimize deployment risk and rollback time
- Maintain high system availability and observability

### Typical Communication
- Pre-release readiness reviews and deployment planning
- Production incident response and escalation
- Monitoring dashboards and operational metrics

### How DevOps/Infrastructure Engineer interacts with other roles
- **With Developers**: Advises on containerization, deployment requirements, and CI/CD best practices
- **With QA/Testing Leads**: Coordinates staging environment setup and smoke test automation
- **With Project Managers**: Participates in release planning and communicates deployment risks

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests, fund the project, and provide strategic context. They approve project charters, make trade-off decisions, and receive regular status updates.

### Responsibilities
- Review and approve project charter and success metrics
- Make prioritization and trade-off decisions
- Remove blockers and resolve escalations
- Receive and review regular status updates
- Validate product outcomes align with business goals

### Goals
- Ensure project delivers business value and meets strategic objectives
- Maintain executive visibility and manage organizational risk
- Enable team autonomy through clear decision authority

### Typical Communication
- Project charter reviews and approval gates
- Monthly stakeholder status updates
- Ad-hoc escalations and decision requests

### How Stakeholder/Sponsor interacts with other roles
- **With Product Managers**: Aligns on business priorities and success metrics
- **With Project Managers**: Receives status updates and approves major decisions
- **With Developers**: Provides business context for features and validates outcomes

---

## Security/Compliance Officer

### Role Summary
Security Officers ensure that projects comply with organizational security policies and regulatory requirements. They conduct security reviews, coordinate security testing, and guide risk mitigation.

### Responsibilities
- Review security requirements for new features and integrations
- Conduct security design reviews and threat modeling
- Coordinate security scanning and penetration testing
- Ensure compliance with regulatory and organizational standards
- Provide security guidance during incident response
- Track security-related risks and mitigation status

### Goals
- Minimize security and compliance risk in new features
- Ensure regulatory alignment and customer trust
- Enable secure, compliant feature delivery without excessive delay

### Typical Communication
- Security requirements gathering during planning
- Security review feedback on design and implementation
- Incident response and post-incident review participation

### How Security/Compliance Officer interacts with other roles
- **With Developers**: Reviews design and code for security vulnerabilities; provides secure coding guidance
- **With DevOps/Infrastructure Engineers**: Ensures security scanning is integrated into CI/CD pipelines
- **With Project Managers**: Escalates security risks and provides compliance guidance during planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions between personas highlight communication and dependency patterns throughout the project lifecycle.
