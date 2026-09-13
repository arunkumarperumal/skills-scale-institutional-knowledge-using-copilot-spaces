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
QA/Testing Leads ensure quality standards are met throughout development. They design test strategies, validate acceptance criteria, and own quality gates before release.

### Responsibilities
- Design and execute test plans aligned with acceptance criteria
- Conduct unit, integration, and end-to-end testing
- Perform manual QA for feature acceptance when needed
- Report quality metrics and defects to the team
- Define "Definition of Done" testing requirements
- Collaborate on smoke tests and release verification

### Goals
- Prevent defects from reaching production
- Build confidence in release quality
- Enable fast feedback loops during development

### Typical Communication
- Sprint planning and backlog refinement
- Daily standups (blocker and test status updates)
- Test result summaries in PR reviews
- Quality reports to PM and delivery lead

### Interaction with Existing Roles
- **Developers**: Review test plans, provide feedback on testability, collaborate on test automation
- **Product Managers**: Validate acceptance criteria, align on quality standards
- **Project Managers**: Report quality status, escalate blockers affecting release readiness

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide the technical strategy and design for projects. They mentor developers, conduct design reviews, and ensure architectural consistency.

### Responsibilities
- Guide technical design and architecture decisions
- Conduct architecture and design reviews
- Identify technical risks and propose mitigations
- Mentor developers and support knowledge transfer
- Break down complex features into implementable tasks
- Ensure solutions align with system standards

### Goals
- Deliver maintainable, scalable solutions
- Reduce technical debt and cycle time
- Build team technical capabilities

### Typical Communication
- Technical design reviews and planning sessions
- Code review participation and mentoring
- Architecture decision records (ADRs)
- Risk identification in planning and standups

### Interaction with Existing Roles
- **Developers**: Mentor on technical decisions, provide design guidance, review complex implementations
- **Project Managers**: Assess feasibility, estimate effort for complex features, identify technical risks
- **Product Managers**: Advise on technical trade-offs, validate solution feasibility

---

## Security/Compliance Officer

### Role Summary
Security Officers ensure projects meet security and compliance requirements. They conduct security reviews, manage threat assessments, and coordinate incident response.

### Responsibilities
- Review designs and code for security vulnerabilities
- Configure and monitor security scanning in CI/CD
- Advise on compliance requirements and data handling
- Triage and prioritize security incidents
- Coordinate incident response and post-mortems
- Maintain risk register entries for security threats

### Goals
- Prevent security breaches and data loss
- Ensure compliance with regulatory requirements
- Build a culture of security awareness

### Typical Communication
- Pre-release security reviews
- Security incident notifications and escalations
- Compliance checkpoints during project planning
- Ad-hoc consultation on sensitive features

### Interaction with Existing Roles
- **Developers**: Review code and designs, advise on secure coding practices
- **Project Managers**: Identify security risks in project planning, coordinate incident response
- **Product Managers**: Define security requirements for features, communicate compliance constraints

---

## DevOps/Release Engineer

### Role Summary
DevOps Engineers own deployment pipelines, infrastructure, and release processes. They ensure reliable and safe deployments to production.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage infrastructure and configuration management
- Prepare and execute release deployments
- Monitor post-deployment health and logs
- Support rollback procedures and incident response
- Document deployment runbooks and procedures

### Goals
- Enable fast, safe, and reliable deployments
- Minimize deployment risk and downtime
- Maintain observability and system health

### Typical Communication
- Release planning and pre-deployment reviews
- Deployment day coordination
- Post-deployment verification and monitoring
- Incident response and escalations

### Interaction with Existing Roles
- **Developers**: Support deployment processes, configure infrastructure for new features
- **Project Managers**: Coordinate deployment schedules, report deployment status and incidents
- **QA/Testing Lead**: Execute post-deployment smoke tests, verify release readiness

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies and help teams remove impediments. They coach teams in agile practices and ensure process adherence.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove blockers and impediments
- Track sprint metrics (velocity, burndown)
- Coach teams on agile best practices
- Escalate process issues to PM and leadership
- Maintain sprint backlog and documentation

### Goals
- Maximize team velocity and predictability
- Build continuous improvement culture
- Enable self-organizing, high-performing teams

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones for blocker resolution
- Retrospective action item tracking
- Metrics and process improvement recommendations

### Interaction with Existing Roles
- **Project Managers**: Report sprint metrics, escalate process blockers
- **Developers**: Remove impediments, facilitate team ceremonies, coach on agile practices
- **Product Managers**: Support backlog refinement, ensure team clarity on priorities

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors and key stakeholders provide business context, approvals, and resources. They represent customer and business interests in project decisions.

### Responsibilities
- Define business objectives and success criteria
- Approve project scope and resource allocation
- Escalation point for business-impacting decisions
- Provide feedback and validate solutions
- Support team with organizational alignment
- Communicate project status to broader organization

### Goals
- Ensure projects deliver business value
- Minimize scope creep and misaligned priorities
- Enable cross-organizational collaboration

### Typical Communication
- Project initiation and planning reviews
- Weekly or monthly status updates
- Go/no-go decision gates
- Escalation for business and priority conflicts

### Interaction with Existing Roles
- **Project Managers**: Provide escalation authority, approve major changes, receive status updates
- **Product Managers**: Align on strategy, approve roadmap, validate business outcomes
- **Developers**: Validate delivered solutions, provide feedback on functionality

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
