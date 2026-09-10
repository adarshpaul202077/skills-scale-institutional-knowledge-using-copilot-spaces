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

## QA / Testing Lead

### Role Summary
QA and Testing Leads design and execute quality assurance strategies to ensure features meet acceptance criteria and quality standards before release. They collaborate with Developers and Product Managers to define testability and validate customer experience.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Design and execute unit, integration, and end-to-end test scenarios
- Triage and report bugs with clear reproduction steps
- Advise on testability during design and code reviews
- Coordinate manual and automated testing efforts
- Lead smoke test execution before releases
- Maintain test coverage metrics and quality dashboards

### Goals
- Catch defects early and reduce production issues
- Provide confidence in feature quality before release
- Improve test coverage and automation efficiency
- Enable fast feedback loops to developers

### Interactions with other roles
- **Developers:** Reviews test plans, provides feedback on test coverage, assists with test automation
- **Product Managers:** Aligns test scenarios with acceptance criteria and user workflows
- **Project Managers:** Reports quality metrics and risk status in weekly syncs

### Typical Communication
- Sprint planning and backlog refinement (defining testability)
- Test status updates in daily standups
- Bug reports and test execution logs
- Release readiness sign-off

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors are executive or business-level decision-makers who champion projects, provide approvals, and ensure alignment with organizational strategy. They represent business value and customer needs at the strategic level.

### Responsibilities
- Champion the project and communicate business rationale
- Provide approvals and prioritization decisions
- Ensure alignment with organizational strategy and customer needs
- Review progress and manage escalations
- Approve scope changes, resource allocation, and release decisions
- Communicate project outcomes to broader organization

### Goals
- Maximize business value and ROI
- Ensure strategic alignment of projects
- Mitigate business-level risks and dependencies
- Drive organizational support and adoption

### Interactions with other roles
- **Project Managers:** Receives status updates, approves major decisions and scope changes
- **Product Managers:** Aligns on business objectives, success metrics, and strategic priorities
- **Developers:** Communicates vision and business context during kickoffs and demos

### Typical Communication
- Monthly or milestone-based status briefings
- Decision gates and approval meetings
- Executive dashboards and progress reports
- Release announcements and stakeholder updates

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects and Tech Leads lead technical design decisions, manage architectural risks, and ensure scalability, maintainability, and integration across systems. They provide technical guidance to the development team and balance innovation with system stability.

### Responsibilities
- Design system architecture and technical solutions
- Make decisions on technology choices and frameworks
- Identify and mitigate technical risks and bottlenecks
- Ensure code quality, scalability, and performance standards
- Lead technical design reviews and code reviews
- Manage integration points with other systems
- Mentor developers and promote best practices

### Goals
- Build scalable, maintainable systems
- Reduce technical debt and system complexity
- Ensure reliable and performant solutions
- Enable fast development velocity and reduced rework

### Interactions with other roles
- **Developers:** Provides technical direction, reviews designs, mentors team members
- **Project Managers:** Communicates technical risks, timeline impacts, and resource needs
- **QA/Testing Leads:** Partners on testability strategy and performance requirements
- **Product Managers:** Collaborates on feasibility and technical trade-offs

### Typical Communication
- Technical design reviews and architecture discussions
- Sprint planning and backlog refinement (technical feasibility)
- Code review sessions and pair programming
- Risk registers and escalation updates

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile processes, remove blockers, and coach teams on agile practices. They focus on continuous improvement, team dynamics, and adherence to agile principles to optimize delivery velocity and team health.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove impediments and blockers for the team
- Coach team members on agile practices and mindset
- Monitor team velocity and burndown metrics
- Facilitate conflict resolution and team communication
- Drive continuous process improvement initiatives
- Ensure Definition of Done and acceptance criteria clarity

### Goals
- Optimize team velocity and delivery cadence
- Improve team collaboration and psychological safety
- Reduce waste and cycle time
- Foster a culture of continuous improvement

### Interactions with other roles
- **Project Managers:** Partners on process execution, timeline management, and risk escalation
- **Developers:** Coaches on agile practices, removes blockers, facilitates ceremonies
- **Product Managers:** Supports backlog refinement and acceptance criteria clarity
- **All Team Members:** Provides process guidance and fosters team health

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching and team retrospectives
- Process metrics and improvement tracking
- Escalation of persistent blockers and team concerns

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security and regulatory requirements, minimize risk exposure, and maintain organizational compliance standards. They conduct reviews, manage incident response, and provide security guidance throughout the project lifecycle.

### Responsibilities
- Review security requirements and acceptance criteria
- Conduct security assessments and code reviews
- Advise on compliance with regulatory and organizational standards
- Manage security scanning and vulnerability assessment
- Lead incident response and post-incident analysis
- Maintain security documentation and audit trails
- Provide security training and awareness to team members

### Goals
- Reduce security vulnerabilities and risk exposure
- Ensure compliance with regulatory and organizational policies
- Enable fast, secure delivery without compromising quality
- Build security awareness across the organization

### Interactions with other roles
- **Developers:** Reviews code for security vulnerabilities, advises on secure coding practices
- **Project Managers:** Reports security risks, manages incident escalation and communication
- **QA/Testing Leads:** Partners on security testing strategy and penetration testing
- **Technical Architects:** Collaborates on secure architecture and technology choices

### Typical Communication
- Security design reviews and threat assessments
- Vulnerability reports and remediation tracking
- Incident notifications and escalations
- Security scanning results in CI/CD pipeline
- Compliance audit updates and risk registers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
