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
- **Product Managers**: Receive acceptance criteria and feature specifications; collaborate on feasibility assessments
- **Project Managers**: Coordinate on sprint planning, risk identification, and status updates
- **QA/Testing Lead**: Work with QA to refine testability and validate implementations
- **Technical Lead/Architect**: Align on architectural decisions and design patterns
- **Scrum Master/Agile Coach**: Participate in agile ceremonies and impediment resolution

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
- **Developers**: Define acceptance criteria and collaborate on scope and feasibility
- **Project Managers**: Coordinate on roadmap alignment and stakeholder updates
- **Design/UX Lead**: Work together on user research, validation, and feature prioritization
- **Stakeholders/Sponsors**: Present roadmap priorities and gather requirements
- **QA/Testing Lead**: Define acceptance criteria validation approach

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
- **Product Managers**: Align on roadmap and release schedules
- **Developers**: Track progress, identify blockers, and facilitate planning
- **Release Manager**: Coordinate on release timelines and deployment planning
- **Stakeholders/Sponsors**: Provide status and escalate risks and decisions
- **Scrum Master/Agile Coach**: Support team velocity tracking and retrospectives

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and own the quality strategy, test planning, and acceptance criteria validation across the project. They ensure products meet quality standards before release.

### Responsibilities
- Develop test plans and QA strategies aligned with project scope
- Define acceptance criteria validation approach
- Manage test execution, bug triage, and quality reporting
- Identify testability gaps and propose improvements
- Coordinate with developers on test automation and CI integration
- Establish quality metrics and track defect trends

### Goals
- Ensure quality standards are met before release
- Reduce defects escaping to production
- Enable fast, reliable testing feedback loops
- Improve team confidence in product quality

### Typical Communication
- Quality metrics reviews
- Test readiness gates and sign-offs
- Bug triage meetings
- Release verification and post-deployment testing

### Interactions with Other Roles
- **Developers**: Collaborate on testability improvements and test automation; review test coverage
- **Product Managers**: Validate acceptance criteria and prioritize testing efforts
- **Project Managers**: Report quality status and flag risks; coordinate testing timelines
- **Release Manager**: Provide quality sign-off before production deployment
- **Technical Lead/Architect**: Align on testing architecture and technical test strategy

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects provide technical vision, guide architectural decisions, and ensure technical excellence and risk mitigation. They maintain system scalability and code quality.

### Responsibilities
- Lead technical design discussions and architecture reviews
- Identify and mitigate technical risks and dependencies
- Mentor developers on best practices and design patterns
- Review complex PRs and technical decisions
- Collaborate with Product and Project Managers on feasibility
- Ensure adherence to coding standards and technical debt management

### Goals
- Maintain code quality and system scalability
- Reduce technical debt and rework
- Enable team confidence in architectural decisions
- Improve system performance and reliability

### Typical Communication
- Technical design reviews and architecture decision records (ADRs)
- Risk assessments and mitigation strategies
- Code review feedback on complex implementations
- Technical mentoring and design pattern guidance

### Interactions with Other Roles
- **Developers**: Mentor on design patterns; review complex technical decisions
- **Product Managers**: Assess feasibility and technical trade-offs
- **Project Managers**: Identify technical risks and dependencies for planning
- **QA/Testing Lead**: Align on test architecture and technical testing strategies
- **Release Manager**: Support deployment verification and technical readiness

---

## Stakeholder/Sponsor

### Role Summary
Business owners and executive sponsors provide requirements, approve prioritization, and ensure alignment with business goals. They authorize resources and make go/no-go decisions.

### Responsibilities
- Define business requirements and success criteria
- Approve project charter and resource allocation
- Make go/no-go decisions at key gates
- Provide budget and timeline constraints
- Receive and act on status escalations
- Ensure business alignment and ROI measurement

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between technical delivery and business strategy
- Reduce scope creep and unplanned changes
- Enable data-driven decision-making

### Typical Communication
- Monthly stakeholder updates and executive summaries
- Gate approvals and decision points
- Escalation responses and risk resolution
- Roadmap alignment meetings

### Interactions with Other Roles
- **Project Managers**: Receive status updates; approve resources and scope changes
- **Product Managers**: Align on roadmap priorities and success metrics
- **Developers**: Receive updates on technical feasibility and risks
- **Release Manager**: Approve release decisions and major milestones

---

## Design/UX Lead

### Role Summary
Design/UX Leads own user experience strategy, interaction design, and usability validation to ensure products are intuitive and user-centered.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Establish design standards and accessibility requirements
- Review implementation for design fidelity
- Collaborate with Product Managers on user needs and validation
- Define user journey maps and interaction flows

### Goals
- Deliver intuitive, user-centered products
- Reduce support load through better UX
- Improve adoption and user satisfaction
- Maintain design consistency across products

### Typical Communication
- Design reviews and feedback sessions
- Usability testing reports and insights
- Accessibility audits and compliance verification
- Design system updates and style guides

### Interactions with Other Roles
- **Product Managers**: Work together on user research, validation, and feature prioritization
- **Developers**: Review design implementation and collaborate on technical constraints
- **QA/Testing Lead**: Define usability acceptance criteria and test scenarios
- **Project Managers**: Coordinate design milestones and design review timelines
- **Stakeholders/Sponsors**: Present user research findings and design impact

---

## Release Manager

### Role Summary
Release Managers coordinate release planning, deployment coordination, and post-release verification to ensure smooth, low-risk production releases.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Prepare and manage release notes and communication
- Coordinate pre-release testing and sign-offs
- Execute or oversee deployments to production
- Manage rollback procedures and post-deployment verification
- Document deployment processes and lessons learned

### Goals
- Minimize release-related incidents and downtime
- Ensure timely, predictable releases
- Maintain clear communication during deployments
- Improve deployment confidence and velocity

### Typical Communication
- Release planning meetings and timelines
- Deployment checklists and runbooks
- Stakeholder release announcements
- Post-deployment reports and retrospectives

### Interactions with Other Roles
- **Project Managers**: Coordinate on release timelines and milestone planning
- **QA/Testing Lead**: Obtain quality sign-off before production deployment
- **Developers**: Coordinate on deployment readiness and technical preparation
- **Stakeholders/Sponsors**: Announce releases and communicate business impact
- **Technical Lead/Architect**: Verify technical readiness and deployment procedures

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and coach teams on continuous improvement and agile practices.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove impediments and blockers
- Mentor team on agile principles and practices
- Track and improve team velocity and sprint health
- Coach on Definition of Done and acceptance criteria
- Foster psychological safety and encourage team feedback

### Goals
- Enable high-performing, self-organizing teams
- Improve predictability and cycle time
- Foster psychological safety and continuous learning
- Reduce process friction and impediments

### Typical Communication
- Agile ceremonies (standups, planning, reviews, retrospectives)
- Retrospective action tracking and follow-up
- Impediment logs and blocker escalations
- Team coaching and process improvement guidance

### Interactions with Other Roles
- **Project Managers**: Support sprint planning and velocity tracking; facilitate retrospectives
- **Developers**: Coach on agile practices and help resolve team impediments
- **Product Managers**: Facilitate backlog refinement and sprint planning alignment
- **All Roles**: Remove impediments and foster collaboration across the team

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand role interactions to improve cross-functional communication and accountability.
