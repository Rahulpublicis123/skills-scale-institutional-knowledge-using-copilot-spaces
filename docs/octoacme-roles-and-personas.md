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

### Interaction with Other Roles
- **Product Managers**: Collaborate on acceptance criteria and feature priorities
- **Project Managers**: Provide status updates and work estimates
- **QA/Test Lead**: Partner on test strategy and acceptance criteria validation
- **Technical Lead/Architect**: Receive technical guidance and design reviews

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

### Interaction with Other Roles
- **Developers**: Define requirements and acceptance criteria
- **Project Managers**: Align on priorities and timeline
- **QA/Test Lead**: Validate solutions meet success metrics
- **Business Analyst**: Collaborate on requirements and user stories

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

### Interaction with Other Roles
- **Product Managers**: Align on priorities and milestones
- **Developers**: Track progress and manage dependencies
- **Technical Lead/Architect**: Escalate technical risks and dependencies
- **Release Manager**: Coordinate release planning and deployment windows

---

## QA/Test Lead

### Role Summary
QA and Test Leads define and execute the testing strategy, ensure quality standards are met, and validate that features meet acceptance criteria before release.

### Responsibilities
- Define test strategy and test plans for each project
- Write and maintain automated test suites
- Execute manual QA and exploratory testing
- Validate acceptance criteria before marking work as done
- Identify and document defects and quality issues
- Recommend quality gates and testing improvements
- Collaborate on smoke tests and end-to-end testing

### Goals
- Ensure features meet quality standards before release
- Reduce escape of defects to production
- Maintain comprehensive test coverage
- Improve release confidence through rigorous testing

### Typical Communication
- Daily standups and sprint planning
- Acceptance criteria refinement with PdM and developers
- Test status updates in execution syncs
- Defect triage and escalation

### Interaction with Other Roles
- **Developers**: Collaborate on test automation and acceptance criteria validation
- **Product Managers**: Validate solutions meet success metrics and user expectations
- **Project Managers**: Report on QA progress and readiness for release
- **Release Manager**: Coordinate smoke tests and pre-deployment verification

---

## Technical Lead/Architect

### Role Summary
Technical Leads shape the technical strategy, ensure design quality, identify technical risks, and guide architectural decisions for projects. They are the primary technical authority and mentor for development teams.

### Responsibilities
- Lead technical design reviews and architecture discussions
- Identify technical risks and propose mitigation strategies
- Define technical standards and best practices for the project
- Mentor developers and conduct code reviews
- Manage technical dependencies and integration points
- Collaborate on estimation and feasibility assessment
- Ensure scalability, security, and maintainability of solutions

### Goals
- Ensure scalable, maintainable technical solutions
- Reduce technical debt and rework
- Minimize integration surprises and dependencies
- Accelerate development velocity through clear technical direction

### Typical Communication
- Design review meetings and technical sync
- Code review comments and architectural guidance
- Risk register updates during planning
- Integration point coordination with dependent teams

### Interaction with Other Roles
- **Developers**: Provide technical guidance, mentorship, and design reviews
- **Project Managers**: Escalate technical risks and flag dependencies
- **Product Managers**: Advise on technical feasibility and trade-offs
- **DevOps/Infrastructure**: Collaborate on infrastructure requirements and deployment strategy

---

## Release Manager

### Role Summary
Release Managers orchestrate the release process, coordinate deployment activities, and ensure smooth handoff from development to production. They minimize deployment risk through careful planning and coordination.

### Responsibilities
- Plan and schedule release windows
- Coordinate deployment activities across teams
- Execute or oversee deployment checklists
- Verify post-deployment health and rollback procedures
- Communicate release status and timeline to stakeholders
- Coordinate incident response if deployment issues arise
- Maintain release notes and documentation

### Goals
- Execute reliable, predictable releases
- Minimize deployment risk and downtime
- Maintain transparency with stakeholders during release
- Enable rapid rollback if needed

### Typical Communication
- Release planning with PM and engineering
- Pre-release coordination meetings
- Deployment day communication and status updates
- Post-release verification and incident updates

### Interaction with Other Roles
- **Project Managers**: Coordinate release windows and timelines
- **Developers**: Validate code readiness and coordinate deployment steps
- **QA/Test Lead**: Execute smoke tests and verify post-deployment health
- **DevOps/Infrastructure**: Execute deployment and manage infrastructure changes
- **Product Managers**: Communicate release status and feature availability to business

---

## Business Analyst

### Role Summary
Business Analysts bridge product vision and technical delivery by gathering requirements, analyzing business needs, and refining acceptance criteria. They ensure clear understanding of what needs to be built and why.

### Responsibilities
- Gather and document business requirements from stakeholders
- Conduct stakeholder interviews and requirements analysis
- Refine and clarify acceptance criteria with Product Managers and Developers
- Document user stories and use cases
- Identify and highlight business and functional gaps
- Validate solutions meet business objectives

### Goals
- Ensure clear, shared understanding of requirements across the team
- Reduce rework due to unclear or misunderstood requirements
- Improve alignment between business needs and technical delivery
- Accelerate requirements clarity in planning phase

### Typical Communication
- Stakeholder interviews and requirements workshops
- User story refinement sessions with product and engineering
- Requirements documentation and clarification in issue comments
- Business impact analysis and trade-off recommendations

### Interaction with Other Roles
- **Product Managers**: Collaborate on requirements prioritization and success metrics
- **Developers**: Clarify technical feasibility and acceptance criteria
- **Project Managers**: Help identify dependencies and scope implications
- **QA/Test Lead**: Ensure acceptance criteria are testable and clear

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters (or Agile Coaches) facilitate the agile delivery process, remove impediments, and help the team continuously improve their execution. They ensure the team follows agreed practices and remains focused.

### Responsibilities
- Facilitate sprint planning, standup, review, and retrospective ceremonies
- Identify and help remove impediments and blockers
- Coach the team on agile practices and continuous improvement
- Monitor team velocity and sprint health
- Facilitate difficult conversations and conflict resolution
- Protect the team from external disruptions during sprints
- Help teams iterate on their processes

### Goals
- Maximize team productivity and predictability
- Foster continuous improvement mindset
- Remove friction from the delivery process
- Build a high-performing, self-organizing team

### Typical Communication
- Facilitation of all sprint ceremonies
- 1-on-1 coaching conversations with team members
- Process improvement suggestions and retrospective follow-ups
- Escalation of systemic blockers to Project Manager

### Interaction with Other Roles
- **Project Managers**: Escalate organizational impediments and resource constraints
- **Developers**: Coach on sprint commitments and agile practices
- **Product Managers**: Help manage scope and prioritization clarity
- **All Roles**: Facilitate ceremonies and continuous process improvement

---

## Security Lead/InfoSec Representative

### Role Summary
Security Leads ensure that security is integrated into the project delivery process from inception through release. They identify security risks, guide secure development practices, and ensure compliance.

### Responsibilities
- Conduct security reviews of design and code
- Identify and assess security risks
- Define security requirements and acceptance criteria
- Guide secure coding practices and architecture patterns
- Recommend security tooling and testing (e.g., SAST, DAST)
- Ensure compliance with security policies and standards
- Coordinate security incident response if needed

### Goals
- Embed security into the development lifecycle
- Reduce security vulnerabilities in production
- Maintain compliance with regulatory and organizational standards
- Build a security-conscious delivery culture

### Typical Communication
- Security review participation in design and code reviews
- Security requirements in acceptance criteria
- Threat modeling and risk assessment documentation
- Security incident response and post-incident reviews

### Interaction with Other Roles
- **Technical Lead/Architect**: Collaborate on secure architecture and threat modeling
- **Developers**: Review code for security vulnerabilities and guide secure practices
- **Product Managers**: Advise on security implications of features
- **Release Manager**: Verify security readiness before deployment

---

## DevOps/Infrastructure

### Role Summary
DevOps and Infrastructure Engineers design, build, and maintain the infrastructure, CI/CD pipelines, and deployment systems that enable reliable, rapid delivery of software. They enable teams to deploy confidently and frequently.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Configure and manage deployment environments (staging, production)
- Monitor system health, performance, and reliability
- Enable automated testing and security scanning in CI
- Support troubleshooting and incident response
- Document infrastructure and deployment procedures
- Optimize for deployment speed and reliability

### Goals
- Enable rapid, reliable deployment of features
- Maintain high system reliability and uptime
- Minimize manual deployment effort and error risk
- Provide visibility into system health and performance

### Typical Communication
- CI/CD pipeline setup and optimization discussions
- Infrastructure requirements and capacity planning
- Deployment coordination and runbook documentation
- Incident response and post-incident analysis

### Interaction with Other Roles
- **Developers**: Enable CI/CD pipeline access and support environment troubleshooting
- **Technical Lead/Architect**: Collaborate on infrastructure requirements and deployment strategy
- **Release Manager**: Execute deployments and verify infrastructure readiness
- **QA/Test Lead**: Provide test environment access and configuration

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understanding the interaction patterns between roles helps simulate realistic cross-functional project scenarios.
- Refer to these personas when reviewing project checklists and process steps to ensure all roles are appropriately involved.
