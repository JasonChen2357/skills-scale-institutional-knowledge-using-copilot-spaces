# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Extended Roles

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and foster a culture of continuous improvement. They act as servant leaders, ensuring the team follows agile practices while removing impediments to productivity.

#### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help resolve team blockers and dependencies
- Coach team members on agile practices and mindset
- Protect team focus and manage scope creep
- Track and communicate sprint metrics and team health
- Foster psychological safety and open communication

#### Goals
- Enable team velocity and sustainable pace
- Build self-organizing, high-performing teams
- Reduce friction in delivery process
- Continuous process improvement

#### Typical Interactions
- Works closely with **Project Manager** on scheduling and risk escalation
- Supports **Developers** in removing blockers and managing workload
- Collaborates with **Product Manager** on backlog clarity and prioritization
- Assists **QA/Testing** in defining Definition of Done

#### Typical Communication
- Sprint ceremonies and team huddles
- Impediment logs and sprint retrospectives
- Coaching conversations with team members
- Metrics dashboards (velocity, burndown)

---

### Business Analyst

#### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit, document, and validate requirements to ensure solutions meet actual business needs and user expectations.

#### Responsibilities
- Gather and document business requirements from stakeholders
- Translate requirements into clear acceptance criteria for developers
- Model business processes and data flows
- Identify gaps or inconsistencies in requirements
- Validate solutions against original business objectives
- Support UAT and change management

#### Goals
- Ensure solutions solve real business problems
- Minimize rework due to unclear requirements
- Improve collaboration between business and technical teams
- Enhance user adoption and satisfaction

#### Typical Interactions
- Partners with **Product Manager** to refine backlog and acceptance criteria
- Works with **Developers** to clarify requirements and edge cases
- Engages **Stakeholders** to validate solutions and gather feedback
- Supports **QA/Testing** in defining test scenarios based on business rules

#### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and decision tables
- UAT coordination and stakeholder reviews
- Requirements traceability and change logs

---

### UX/UI Designer

#### Role Summary
UX/UI Designers advocate for the user and ensure solutions are intuitive, accessible, and delightful. They design user journeys, wireframes, and visual assets that guide the development of user-facing features.

#### Responsibilities
- Conduct user research and define user personas
- Design user journeys, wireframes, and mockups
- Create visual designs and design systems
- Advocate for accessibility and usability standards
- Collaborate on interaction patterns and design reviews
- Validate designs with user testing and feedback

#### Goals
- Create intuitive, user-friendly interfaces
- Ensure accessibility and inclusive design
- Reduce user friction and support adoption
- Build consistent, maintainable design systems

#### Typical Interactions
- Collaborates with **Product Manager** on feature requirements and success metrics
- Partners with **Developers** on design handoff, technical feasibility, and implementation
- Works with **QA/Testing** to validate UI against design specs
- Engages **Stakeholders** for feedback and validation

#### Typical Communication
- Wireframes, mockups, and design specifications
- Design system documentation
- Usability testing reports and user feedback
- Design review meetings and feedback sessions

---

### Release Manager

#### Role Summary
Release Managers plan, coordinate, and oversee the release of features and fixes to production. They ensure releases are smooth, well-communicated, and reversible if needed.

#### Responsibilities
- Plan and schedule releases with stakeholder input
- Create and maintain release checklists and runbooks
- Coordinate deployment activities across teams
- Manage release communications to customers and support teams
- Document release notes and migration steps
- Plan and test rollback procedures
- Monitor post-deployment health and coordinate incident response

#### Goals
- Reduce deployment risk and downtime
- Improve release predictability and communication
- Enable rapid iteration with confidence
- Maintain system stability and customer satisfaction

#### Typical Interactions
- Works with **Project Manager** on release timelines and stakeholder coordination
- Collaborates with **Developers** on deployment readiness and hotfixes
- Partners with **QA/Testing** on smoke tests and acceptance validation
- Coordinates with **Product Manager** on release messaging and feature enablement

#### Typical Communication
- Release plans and deployment schedules
- Release notes and customer announcements
- Deployment checklists and runbooks
- Post-deployment monitoring reports and incident logs

---

### Stakeholders (External/Customer)

#### Role Summary
Stakeholders represent business interests, customer needs, or organizational priorities. They provide direction, feedback, and approval throughout the project lifecycle.

#### Responsibilities
- Define business requirements and success criteria
- Provide regular feedback on solutions and prototypes
- Participate in UAT and acceptance validation
- Champion product adoption and communicate value to users
- Make decisions on scope, timeline, and resource trade-offs
- Escalate risks and organizational blockers

#### Goals
- Ensure delivered solutions meet business objectives
- Maximize return on investment
- Achieve stakeholder buy-in and smooth adoption
- Balance competing priorities

#### Typical Interactions
- Engages with **Product Manager** on vision, roadmap, and prioritization
- Works with **Business Analyst** to validate requirements and business rules
- Provides feedback to **UX/UI Designer** and **Developers** on solutions
- Partners with **Project Manager** on planning and risk escalation

#### Typical Communication
- Requirements and business case documents
- Status updates and progress reports
- UAT participation and acceptance sign-off
- Feedback sessions and stakeholder reviews
- Executive summaries and business impact reports

---

## Role Interaction Matrix

Refer to `docs/octoacme-role-interaction-matrix.md` for a detailed matrix showing how roles collaborate across project phases (Initiation, Planning, Execution, Release, Close).

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When a team member takes on multiple roles, refer to this document to understand potential overlaps and communication needs.
