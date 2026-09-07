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

### Interactions with Other Roles
- Works with **QA/Testing Engineer** on test design and acceptance criteria validation
- Collaborates with **Technical Lead/Architect** on design reviews and technical strategy
- Aligns with **Product Manager** on acceptance criteria and priorities
- Coordinates with **Project Manager** on sprint planning and delivery timeline

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

### Interactions with Other Roles
- Aligns with **Stakeholder/Business Owner** on priorities and business goals
- Works with **Project Manager** on timeline and resource allocation
- Collaborates with **Developers** on acceptance criteria and technical trade-offs
- Reviews quality gates with **QA/Testing Engineer** for feature acceptance

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

### Interactions with Other Roles
- Coordinates with **Product Manager** on priorities and release planning
- Works with **Developers** and **QA/Testing Engineer** on delivery schedules
- Escalates risks to **Stakeholder/Business Owner** and **Sponsor**
- Partners with **Technical Lead/Architect** on technical dependencies
- Supports **Scrum Master/Agile Coach** with process facilitation

---

## QA/Testing Engineer

### Role Summary
QA/Testing Engineers ensure software quality by designing test strategies, validating acceptance criteria, and identifying defects. They work throughout the project lifecycle to enable confident deployments and reduce production issues.

### Responsibilities
- Design comprehensive test plans and test strategies
- Validate that acceptance criteria are met before release
- Execute manual and automated testing across quality gates
- Identify, triage, and track defects with clear reproduction steps
- Support smoke tests and user acceptance testing (UAT) for releases
- Collaborate with developers to improve testability and test coverage
- Provide quality metrics and test execution reports

### Goals
- Ensure quality gates are met before release
- Reduce production defects and post-release issues
- Enable confident deployments with validated acceptance criteria
- Maintain high test coverage across critical flows

### Typical Communication
- Test plan reviews and test case documentation
- Daily standups and QA status updates
- Defect reports and quality metrics dashboards
- Pre-release smoke test coordination

### Interactions with Other Roles
- Works with **Developers** on test design, testability improvements, and defect reproduction
- Reports quality gates to **Product Manager** for feature acceptance
- Coordinates with **Project Manager** on testing timeline and release readiness
- Collaborates with **Technical Lead/Architect** on test strategy for complex features
- Participates in **Scrum Master/Agile Coach** ceremonies for sprint-based quality goals

---

## Technical Lead / Solution Architect

### Role Summary
Technical Leads define the technical approach, mentor developers, and ensure solutions are scalable, maintainable, and aligned with architectural standards. They bridge product vision with technical implementation.

### Responsibilities
- Define technical architecture and design approach for features and integrations
- Mentor and guide developers on best practices and code standards
- Review designs and implementations for scalability and maintainability
- Identify technical dependencies, risks, and mitigation strategies
- Conduct code reviews and architectural decision-making
- Collaborate on performance and reliability improvements
- Plan technical debt reduction and refactoring initiatives

### Goals
- Ensure technical excellence and adherence to standards
- Reduce technical debt and architecture drift
- Enable sustainable, scalable product delivery
- Minimize technical surprises and integration issues

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code review comments and feedback
- Technical risk identification in risk registers
- Architecture and design discussions with team

### Interactions with Other Roles
- Mentors and collaborates with **Developers** on technical implementation
- Advises **Product Manager** on technical trade-offs and feasibility
- Identifies technical dependencies with **Project Manager**
- Supports **QA/Testing Engineer** with test strategy for complex systems
- Partners with **Operations/Support Lead** on deployability and monitoring
- Works with **Security/Compliance Officer** on architectural security reviews

---

## Stakeholder / Business Owner

### Role Summary
Stakeholders and Business Owners provide business context, approve scope and budget decisions, and ensure projects deliver measurable business value. They are decision-makers who align projects with organizational goals.

### Responsibilities
- Provide business context and strategic constraints for projects
- Approve project scope, timeline, and budget
- Make prioritization decisions and trade-off calls
- Validate that solutions meet business needs and success criteria
- Communicate project status to executive sponsors
- Remove business-level blockers and escalations
- Define success metrics tied to business outcomes

### Goals
- Ensure projects deliver measurable business value
- Manage stakeholder expectations and communicate impact
- Support resource allocation and priority decisions
- Align project outcomes with organizational strategy

### Typical Communication
- Stakeholder briefings and status updates
- Budget and scope approval meetings
- Executive summaries and business impact reports
- Escalation and decision-making forums

### Interactions with Other Roles
- Aligns with **Product Manager** on product priorities and success metrics
- Works with **Project Manager** on budget and resource approval
- Receives status updates and escalations from delivery team
- Approves trade-offs with **Developers** and **Technical Lead/Architect**
- Partners with **Security/Compliance Officer** on compliance and risk approval

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet security standards, compliance requirements, and risk mitigation. They review designs, validate implementations, and support incident response.

### Responsibilities
- Review technical designs and architectures for security risks
- Conduct or coordinate security scanning and validation testing
- Approve security checklists before releases to production
- Support incident response and root cause analysis for security issues
- Ensure compliance with organizational and regulatory requirements
- Provide security guidance and best practices to the team
- Maintain security risk register and mitigation tracking

### Goals
- Reduce security risks and vulnerabilities in production
- Ensure compliance with organizational and regulatory standards
- Enable secure, confident deployments
- Foster a security-conscious culture across teams

### Typical Communication
- Security design reviews and threat modeling discussions
- Security scanning reports and vulnerability assessments
- Release security checklist sign-off
- Security incident and post-incident review reports

### Interactions with Other Roles
- Reviews technical designs with **Technical Lead/Architect** and **Developers**
- Escalates findings to **Project Manager** and **Stakeholder/Business Owner**
- Coordinates security testing with **QA/Testing Engineer**
- Works with **Operations/Support Lead** on secure deployment procedures
- Participates in release approval with **Project Manager**

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile practices. They optimize team flow, improve predictability, and foster psychological safety for continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, and retrospectives
- Identify and help remove impediments blocking the team
- Coach team members on agile principles and practices
- Track and report on team velocity, burndown, and process metrics
- Foster psychological safety and encourage continuous improvement feedback
- Help resolve conflicts and maintain team morale
- Optimize ceremonies and processes for team effectiveness

### Goals
- Optimize team flow and delivery predictability
- Improve sprint velocity and cycle time
- Foster psychological safety and continuous learning
- Maintain team focus and reduce process friction

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective notes and action items
- Velocity and burndown tracking
- Process improvement recommendations

### Interactions with Other Roles
- Supports **Project Manager** with meeting facilitation and process optimization
- Coaches all team members on agile practices and collaboration
- Escalates impediments to **Project Manager** when team cannot resolve
- Tracks team metrics for **Developers**, **QA/Testing Engineer**, and **Product Manager**
- Partners with **Technical Lead/Architect** on technical flow improvements

---

## Operations / Support Lead

### Role Summary
Operations and Support Leads prepare for releases, manage deployments, monitor production systems, and provide operational feedback for planning. They ensure smooth deployments and maintain system uptime.

### Responsibilities
- Prepare deployment documentation and procedures
- Plan rollback and disaster recovery procedures
- Monitor system health and performance post-release
- Coordinate with support teams on customer escalations
- Provide operational feedback and lessons learned to the team
- Support production issue triage and resolution
- Ensure operational readiness before releases

### Goals
- Ensure smooth, reliable releases to production
- Maintain system uptime and performance
- Provide operational perspective during planning
- Reduce time-to-resolution for production issues

### Typical Communication
- Deployment runbooks and procedures
- Production monitoring and alerting
- Operational readiness reviews
- Post-release incident reports and lessons learned

### Interactions with Other Roles
- Coordinates with **Technical Lead/Architect** on deployment planning and runbooks
- Works with **Project Manager** on release timing and deployment windows
- Collaborates with **Developers** on troubleshooting production issues
- Provides operational input to **QA/Testing Engineer** on smoke test scenarios
- Reports production issues back to the delivery team for continuous improvement

---

## Role Interaction Matrix

| Role | Reports to | Interacts with | Decision Authority |
|------|------------|-----------------|-------------------|
| Developer | Technical Lead | Product Manager, QA, Technical Lead, Scrum Master | Technical implementation |
| Product Manager | Product Lead | Developers, Project Manager, Stakeholders | Product priorities & acceptance |
| Project Manager | Delivery Lead | All roles | Schedule & resource coordination |
| QA/Testing Engineer | Project Manager | Developers, Product Manager, Technical Lead | Quality gates & acceptance |
| Technical Lead / Architect | CTO/Engineering Lead | Developers, PM, Security, Operations | Technical strategy & architecture |
| Stakeholder / Business Owner | Sponsor | PM, PdM, Project Manager | Budget & prioritization |
| Security/Compliance Officer | Chief Security Officer | Developers, Technical Lead, PM, Operations | Security approval & compliance |
| Operations/Support Lead | VP Operations | Technical Lead, Project Manager, Developers | Deployment & uptime |
| Scrum Master / Agile Coach | Delivery Lead | All roles | Process improvement |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction matrix to understand cross-functional dependencies and communication paths.
- Use persona responsibilities to clarify ownership and accountability in project scenarios.
