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

## QA Lead / QA Engineer

### Role Summary
QA Leads own quality strategy, test planning, and acceptance validation. They collaborate with product and engineering to define quality standards and ensure features meet acceptance criteria before release.

### Responsibilities
- Define test plan and QA approach aligned with release timeline
- Create and maintain acceptance criteria validation checklist
- Coordinate manual and automated testing efforts
- Triage and track quality issues and defects
- Conduct acceptance testing and sign-off on features
- Participate in sprint planning to estimate test effort

### Goals
- Ensure features meet defined acceptance criteria before release
- Reduce post-release defects and customer-impacting bugs
- Provide early quality feedback to shape design decisions

### Typical Communication
- Sprint planning and backlog refinement sessions
- Bug reports and quality dashboards
- Test case documentation and QA status updates
- Acceptance sign-off and release readiness reviews

### Interaction with Other Roles
- Works closely with **Developers** to understand technical implementation and design testable solutions
- Collaborates with **Product Managers** to clarify acceptance criteria and validate feature completeness
- Coordinates with **Project Managers** on test timelines and quality milestones
- Partners with **Technical Leads** on test architecture and automation strategies

---

## Technical Lead / Architect

### Role Summary
Technical Leads establish technical strategy, facilitate design decisions, and ensure architectural alignment. They guide engineering teams on technology choices, scalability, and technical risk mitigation.

### Responsibilities
- Participate in design reviews and architecture decisions
- Advise on technology choices and trade-offs
- Identify and escalate technical risks and dependencies
- Mentor developers on code quality and design patterns
- Collaborate with DevOps on infrastructure and deployment needs
- Ensure solutions align with system architecture and standards

### Goals
- Deliver scalable, maintainable technical solutions
- Minimize technical debt and rework
- Reduce integration risk and deployment friction

### Typical Communication
- Technical design documents and architecture review meetings
- Code review feedback and mentoring
- Risk identification and mitigation planning
- Technology recommendation and evaluation sessions

### Interaction with Other Roles
- Mentors and guides **Developers** on architectural decisions and code quality standards
- Collaborates with **Product Managers** on technical feasibility and trade-offs
- Advises **Project Managers** on technical risk and dependency management
- Works with **DevOps Engineers** to ensure infrastructure supports architectural decisions

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business context, strategic alignment, and executive oversight. They have decision-making authority on resource allocation, priority conflicts, and business-level trade-offs.

### Responsibilities
- Define business goals and strategic alignment for the project
- Approve resource allocation and budget
- Resolve priority conflicts between competing initiatives
- Provide executive escalation path for blockers
- Communicate project value to senior leadership
- Review milestone progress and business impact

### Goals
- Ensure project delivers measurable business value
- Align project execution with organizational strategy
- Enable timely decision-making and risk mitigation

### Typical Communication
- Monthly stakeholder updates and business reviews
- Escalation escalations and decision gates
- Budget and resource approval meetings
- Executive steering committee updates

### Interaction with Other Roles
- Reviews and approves project charters with **Product Managers** and **Project Managers**
- Provides strategic guidance to **Project Managers** on priority and scope decisions
- Serves as escalation authority for **Product Managers** and **Project Managers**
- Communicates project status externally to broader organization

---

## Scrum Master / Delivery Facilitator

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile practices and process adherence. They focus on team velocity and continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Coach team on agile principles and practices
- Monitor and communicate team velocity and burndown
- Escalate process and organizational impediments
- Facilitate retrospectives and drive continuous improvement action items

### Goals
- Maximize team velocity and predictability
- Foster psychological safety and collaboration
- Enable continuous process improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment escalations and blocker tracking
- Retrospective facilitation and action item tracking
- Velocity and burndown reporting

### Interaction with Other Roles
- Coaches **Developers**, **Product Managers**, and **Project Managers** on agile practices
- Works with **Project Managers** to resolve cross-team dependencies and blockers
- Supports **QA Leads** in integrating testing into sprint ceremonies
- Escalates organizational impediments to **Sponsors** when needed

---

## Security Engineer

### Role Summary
Security Engineers integrate security requirements throughout the project lifecycle, conduct threat modeling, and ensure compliance with security standards and regulations.

### Responsibilities
- Integrate security requirements into project planning and backlog
- Conduct threat modeling and security design reviews
- Coordinate security testing and vulnerability assessments
- Review code and infrastructure for security compliance
- Ensure adherence to security policies and regulations
- Drive security awareness and best practices within the team

### Goals
- Prevent security vulnerabilities and data breaches
- Ensure compliance with security standards and regulations
- Embed security practices into development workflows

### Typical Communication
- Security requirements and threat modeling sessions
- Code and design review participation
- Security testing and vulnerability reports
- Security training and awareness sessions

### Interaction with Other Roles
- Collaborates with **Developers** on secure coding practices and vulnerability fixes
- Works with **Product Managers** to define security requirements and acceptance criteria
- Partners with **Technical Leads** on architecture security and design patterns
- Coordinates with **DevOps Engineers** on infrastructure security and compliance

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps Engineers manage deployment pipelines, infrastructure, monitoring, and incident response. They ensure reliable, scalable, and observable production systems.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Manage cloud infrastructure, networking, and data storage
- Implement monitoring, logging, and alerting systems
- Support application deployment and rollback procedures
- Respond to production incidents and manage incident runbooks
- Ensure infrastructure security and compliance

### Goals
- Enable reliable and rapid deployment of features
- Maintain high system availability and performance
- Reduce mean time to detection (MTTD) and mean time to recovery (MTTR)

### Typical Communication
- Infrastructure design and deployment planning meetings
- CI/CD pipeline configuration and troubleshooting
- Production incident response and post-mortems
- Monitoring and performance dashboard reviews

### Interaction with Other Roles
- Supports **Developers** with deployment infrastructure, logs, and troubleshooting
- Collaborates with **Technical Leads** on infrastructure architecture and scalability
- Works with **Project Managers** on deployment schedules and release coordination
- Partners with **QA Leads** on test environment provisioning and staging deployments
- Coordinates with **Sponsors** on system performance and reliability reports

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
