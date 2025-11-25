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
- **Product Owner**: Collaborates on user story clarification, acceptance criteria, and technical feasibility during implementation
- **Product Manager**: Partners on technical trade-offs, feasibility assessments, and long-term architecture decisions
- **Project Manager**: Provides implementation status updates, flags technical risks, and collaborates on timeline estimates
- **Quality Assurance Lead**: Works together on testability design, defect resolution, and test coverage improvements
- **Business Analyst**: Clarifies technical constraints, business logic requirements, and provides implementation guidance

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
- **Product Owner**: Aligns on product vision and roadmap priorities; delegates day-to-day backlog management and story refinement
- **Developers**: Sets strategic direction, validates technical approaches, and makes final decisions on product trade-offs
- **Project Manager**: Coordinates on timeline commitments, resource allocation, and stakeholder communication strategies
- **Business Analyst**: Collaborates on market research, customer feedback analysis, and high-level business requirements
- **Release Manager**: Ensures release content aligns with product strategy and customer commitments

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
- **Product Manager**: Aligns on roadmap timelines, resource needs, and manages stakeholder expectations for delivery commitments
- **Product Owner**: Coordinates on sprint planning, scope changes, and dependencies that impact iteration goals
- **Developers**: Tracks progress, removes blockers, and facilitates team communication and ceremony execution
- **Quality Assurance Lead**: Monitors quality metrics and testing progress to identify timeline risks
- **Release Manager**: Coordinates release schedules with project milestones and manages deployment communications
- **Business Analyst**: Tracks requirements status and helps identify scope risks affecting project timelines

---

## Product Owners

### Role Summary
Product Owners act as the bridge between business stakeholders and the development team. They represent the customer voice, refine the product backlog, and ensure that delivered features align with user needs and business goals.

### Responsibilities
- Maintain and prioritize the product backlog
- Define and clarify user stories and acceptance criteria
- Collaborate with Product Managers on product vision and strategy
- Make day-to-day scope and trade-off decisions during sprints
- Accept or reject completed work based on acceptance criteria
- Engage with users and stakeholders to gather feedback

### Goals
- Maximize the value of work delivered in each iteration
- Ensure the team works on the highest-priority items
- Maintain a healthy, well-groomed backlog
- Keep the team unblocked and focused on delivery

### Typical Communication
- Daily collaboration with Developers and QA on story clarifications
- Sprint planning and backlog refinement sessions
- Sprint reviews and acceptance demonstrations
- Regular sync with Product Manager on priorities and feedback

### Interactions with Other Roles
- **Product Manager**: Aligns on product vision, roadmap priorities, and success metrics; translates strategic goals into actionable backlog items
- **Developers**: Clarifies requirements, answers questions during implementation, and reviews completed work
- **Project Manager**: Coordinates on scope changes, dependencies, and timeline impacts
- **Quality Assurance Lead**: Collaborates on acceptance criteria and validates that delivered features meet quality standards

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads ensure product quality through comprehensive testing strategies, test automation, and quality advocacy. They work proactively to identify risks and establish standards that prevent defects from reaching production.

### Responsibilities
- Define and maintain testing strategies and quality standards
- Design test plans, test cases, and automation frameworks
- Lead test execution across functional, integration, and regression testing
- Identify, document, and track defects through resolution
- Advocate for quality throughout the development lifecycle
- Mentor team members on testing best practices
- Coordinate with Release Manager on release readiness

### Goals
- Ensure high product quality and reliability
- Minimize production defects and customer-impacting issues
- Increase test automation coverage and efficiency
- Foster a culture of quality ownership across the team

### Typical Communication
- Daily standup participation and defect triage
- Test plan reviews and test case walkthroughs
- Quality metrics reporting in sprint reviews
- Release readiness sign-off discussions

### Interactions with Other Roles
- **Developers**: Partners on testability design, reviews test coverage, and collaborates on defect resolution
- **Product Owner**: Validates acceptance criteria completeness and participates in story refinement for testability
- **Project Manager**: Reports on quality metrics, testing progress, and quality risks that may impact timelines
- **Release Manager**: Provides quality sign-off for releases and coordinates regression testing
- **Business Analyst**: Ensures requirements are testable and validates test scenarios against business needs

---

## Release Manager

### Role Summary
Release Managers coordinate and orchestrate software releases from planning through deployment. They ensure releases are well-planned, properly tested, communicated effectively, and can be safely rolled back if issues arise.

### Responsibilities
- Plan and schedule releases across environments
- Coordinate release activities across teams and stakeholders
- Maintain release documentation and runbooks
- Execute deployment procedures and checklists
- Monitor deployments and coordinate rollback if needed
- Communicate release status to stakeholders
- Maintain release notes and change logs
- Ensure compliance with release policies and governance requirements

### Goals
- Deliver predictable, low-risk releases
- Minimize deployment-related incidents and downtime
- Maintain clear communication throughout release cycles
- Continuously improve release processes and automation

### Typical Communication
- Pre-release readiness meetings with QA, Development, and Operations
- Deployment notifications and status updates
- Post-release retrospectives and incident reviews
- Release calendar updates for stakeholders

### Interactions with Other Roles
- **Quality Assurance Lead**: Reviews test results and obtains quality sign-off before releases
- **Developers**: Coordinates code freeze timelines, deployment procedures, and hotfix processes
- **Project Manager**: Aligns release schedules with project timelines and manages stakeholder expectations
- **Product Manager**: Ensures release content aligns with product roadmap and customer commitments
- **Product Owner**: Confirms feature completeness and priority for release inclusion

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They elicit, analyze, and document requirements, ensuring that the team understands the business context and delivers solutions that solve real problems.

### Responsibilities
- Gather and analyze business requirements from stakeholders
- Document functional specifications and business process flows
- Create and maintain requirements traceability
- Facilitate requirements workshops and stakeholder interviews
- Perform gap analysis between current and desired states
- Validate solutions against business requirements
- Support user acceptance testing (UAT) coordination

### Goals
- Ensure clear, complete, and testable requirements
- Bridge communication gaps between business and technical teams
- Reduce rework through accurate requirement definition
- Maximize business value delivery through well-understood needs

### Typical Communication
- Requirements gathering sessions with stakeholders
- Requirements review workshops with Product Owner and team
- Documentation reviews and traceability updates
- UAT coordination and results communication

### Interactions with Other Roles
- **Product Manager**: Collaborates on business case development, market research, and strategic requirements
- **Product Owner**: Works together to refine requirements into user stories with clear acceptance criteria
- **Developers**: Clarifies business logic, process flows, and technical constraints
- **Quality Assurance Lead**: Partners to ensure requirements are testable and test scenarios cover business needs
- **Project Manager**: Provides requirements status, helps identify scope risks, and supports stakeholder communication

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

