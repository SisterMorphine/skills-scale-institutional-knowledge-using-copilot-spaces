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

### Key Interactions
- Works with QA Lead on testing requirements and quality gates
- Collaborates with UX/UI Designer on design handoff and implementation details
- Depends on DevOps Engineer for deployment and monitoring support
- Receives requirements from Business Analyst and Product Manager

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

### Key Interactions
- Partners with Business Analyst to translate stakeholder needs into requirements
- Works with UX/UI Designer to define user experience strategy
- Aligns with Project Sponsor on strategic direction and priorities
- Guides Developers and QA Lead on acceptance criteria and success metrics

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

### Key Interactions
- Works closely with QA Lead to ensure quality gates and testing timelines are met
- Coordinates with DevOps Engineer on deployment scheduling and release planning
- Escalates risks and blockers to Project Sponsor
- Facilitates communication between Developers, UX/UI Designer, and Business Analyst

---

## QA Lead

### Role Summary
QA Leads establish and oversee testing strategy, ensure quality standards are met, and coordinate defect tracking and resolution. They bridge quality assurance between product definition and production readiness.

### Responsibilities
- Define and maintain testing strategy (unit, integration, end-to-end, performance)
- Create and prioritize test cases aligned with acceptance criteria
- Coordinate test execution and defect tracking
- Establish quality gates and sign-off criteria for releases
- Work with Developers to resolve issues and improve test coverage
- Report on quality metrics and test results to Project Manager

### Goals
- Deliver high-quality, reliable products that meet user expectations
- Identify and mitigate quality risks early in the development cycle
- Establish clear, repeatable quality standards
- Reduce defects in production

### Typical Communication
- Sprint planning and test case reviews
- Daily standup updates on test progress and blockers
- Defect reports and quality metrics summaries
- Release readiness sign-off and post-release verification

### Key Interactions
- Partners with Developers on test case design and unit testing approaches
- Collaborates with UX/UI Designer to validate user experience against specifications
- Depends on DevOps Engineer for test environment setup and production monitoring
- Reports to Project Manager on quality status and release readiness
- Works with Project Manager on quality gates and timeline impacts

---

## UX/UI Designer

### Role Summary
UX/UI Designers own the user experience and visual design strategy. They translate user needs and product vision into intuitive, accessible interfaces and guide implementation through design handoff.

### Responsibilities
- Conduct user research and validate design assumptions
- Create wireframes, mockups, and high-fidelity UI designs
- Define interaction patterns, navigation, and information architecture
- Ensure designs meet accessibility and usability standards
- Provide detailed design specs and assets to Developers
- Iterate on designs based on feedback and user testing
- Participate in code reviews to ensure implementation matches design intent

### Goals
- Create user-centered, accessible, and visually coherent interfaces
- Minimize rework by establishing clear design expectations upfront
- Validate that product outcomes align with user needs
- Build consistency across the product

### Typical Communication
- Design reviews and critique sessions with stakeholders
- Detailed handoff documents and design specifications for Developers
- User research findings and design validation reports
- Collaboration on definition of done for UI/UX work

### Key Interactions
- Works with Product Manager to understand user needs and product strategy
- Collaborates closely with Developers on implementation feasibility and design handoff
- Participates in QA Lead's acceptance criteria to ensure visual and interaction quality
- Shares insights with Business Analyst on user workflows and requirements
- Reports to Project Manager on design milestones and timeline impacts

---

## DevOps Engineer

### Role Summary
DevOps Engineers build, maintain, and operate the infrastructure, CI/CD pipelines, and deployment automation. They enable fast, safe, and reliable releases while ensuring system observability and incident response.

### Responsibilities
- Design and implement CI/CD pipelines and deployment automation
- Manage infrastructure, environments (dev, staging, production), and configuration management
- Establish monitoring, logging, and alerting systems
- Coordinate deployments and manage rollback procedures
- Support incident response and triage
- Collaborate with Developers on testing infrastructure and local development environments
- Document deployment procedures and runbooks

### Goals
- Enable rapid, reliable, and safe deployments
- Minimize deployment and operational risk
- Provide clear visibility into system health and performance
- Support fast incident recovery and learning

### Typical Communication
- CI/CD pipeline updates and deployment coordination
- Infrastructure readiness and monitoring dashboards
- Incident alerts and post-incident reviews
- Collaboration on performance and scalability concerns

### Key Interactions
- Works with Developers on build pipeline optimization and local development tools
- Partners with QA Lead to provide test environment infrastructure and production monitoring
- Coordinates with Project Manager on deployment windows and release scheduling
- Provides insights to Project Manager on operational risks and capacity constraints
- Supports incident response under Project Manager coordination

---

## Business Analyst

### Role Summary
Business Analysts gather, clarify, and translate business and stakeholder requirements into actionable specifications for the delivery team. They bridge the gap between business needs and technical implementation.

### Responsibilities
- Conduct stakeholder interviews and requirements gathering sessions
- Document business processes, rules, and workflows
- Translate business needs into clear, testable acceptance criteria
- Identify and flag requirement gaps, conflicts, or dependencies
- Validate that solutions meet business objectives
- Maintain requirements traceability and documentation
- Facilitate communication between business stakeholders and delivery team

### Goals
- Ensure shared understanding of business needs and objectives
- Minimize rework caused by unclear or missing requirements
- Enable informed trade-off decisions
- Improve product alignment with business and customer needs

### Typical Communication
- Requirements workshops and clarification sessions
- Requirements documentation and specification artifacts
- Stakeholder interviews and needs assessments
- Acceptance criteria refinement with Product Manager and QA Lead

### Key Interactions
- Partners with Product Manager to translate business needs into product requirements
- Works with Developers and UX/UI Designer to ensure requirements clarity and feasibility
- Collaborates with QA Lead to define acceptance criteria and test scenarios
- Supports Project Manager in stakeholder communication and expectation management
- Reports business impact and requirement status to Project Manager

---

## Project Sponsor

### Role Summary
Project Sponsors provide executive leadership, strategic direction, and organizational support. They ensure projects align with business goals, secure resources, and unblock teams to deliver outcomes.

### Responsibilities
- Define strategic objectives and success criteria for the project
- Secure and allocate resources (budget, personnel, infrastructure)
- Provide executive visibility and stakeholder alignment
- Remove organizational blockers and escalated issues
- Make key trade-off decisions (scope, timeline, resources)
- Ensure project outcomes align with business strategy
- Participate in project gates and sign-off milestones

### Goals
- Deliver business value and strategic alignment
- Remove barriers to team success
- Ensure informed decision-making on priorities and trade-offs
- Maintain accountability for project outcomes

### Typical Communication
- Project status briefings and milestone reviews
- Executive steering committee meetings
- Strategic priority alignment with business leadership
- Decision-making on scope, timeline, and resource changes

### Key Interactions
- Provides strategic direction to Product Manager and Project Manager
- Escalation point for Project Manager on organizational blockers and trade-off decisions
- Aligns project with other organizational initiatives and priorities
- Reviews and approves project charter and major milestones
- Ensures resource availability and organizational support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference key interactions to understand cross-functional collaboration and dependency points.
