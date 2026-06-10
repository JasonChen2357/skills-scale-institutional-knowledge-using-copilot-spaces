# OctoAcme Project Management Docs

This README provides an overview of how OctoAcme approaches project management, and quick links to all process documents.

## Summary of Project Management Processes

OctoAcme follows a structured five-stage project lifecycle that emphasizes customer value, iterative delivery, and clear accountability. Projects move through **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments), **Execution** (building, testing, and iterating), **Release** (deploying to production with risk mitigation), and **Close & Retrospective** (capturing learnings). Throughout each stage, the organization maintains a **single source of truth** through key artifacts—including Project Charters, risk registers, and backlogs—ensuring transparency and enabling quick decision-making.

OctoAcme operates with clearly defined, cross-functional roles that distribute accountability and expertise. **Product Managers** own the vision and prioritize the roadmap based on customer value and measurable success metrics. **Project Managers** coordinate schedules, manage risks, and facilitate stakeholder communication. **Developers** implement features while contributing to estimation, design reviews, and risk identification. **QA/Testing** validates quality and acceptance criteria. The organization sustains alignment through a structured communication cadence: weekly syncs between PM and Product Lead, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations.

Quality is embedded throughout the delivery process, not relegated to the end. OctoAcme requires unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. All pull requests follow a lightweight standard with automated CI/CD testing and linting, and require at least one approval before merging. The team uses structured backlogs with clear acceptance criteria and Definition of Done. Risk and dependency management are proactive and systematic—maintained in a Risk Register reviewed at weekly syncs—with a formal escalation ladder for issues requiring higher-level decisions. After each sprint or milestone, the team conducts retrospectives to capture learnings and drive continuous improvement.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Docs

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders
- [Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution and track progress toward milestones
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Release & Deployment](./octoacme-release-and-deployment.md) — Standardize releases to production and reduce risk
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — Define typical roles and responsibilities in OctoAcme projects

## How to Use These Docs

- **For new team members**: Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand OctoAcme's approach, then review [Roles & Personas](./octoacme-roles-and-personas.md) to understand your role.
- **Starting a new project**: Follow the sequence: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution](./octoacme-execution-and-tracking.md) → [Release](./octoacme-release-and-deployment.md) → [Retrospective](./octoacme-retrospective-and-continuous-improvement.md).
- **Managing risks**: See [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths and templates.
- **Project repos**: Keep the Project Charter updated in your project repo and add process-specific docs to `.copilot/` if using Copilot Spaces as context.
