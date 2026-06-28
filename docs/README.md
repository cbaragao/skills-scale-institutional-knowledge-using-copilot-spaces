# OctoAcme Project Management Documentation

## Welcome to OctoAcme Project Management

OctoAcme runs projects using a customer-first, iterative delivery model with clear ownership and data-informed decisions. This documentation provides comprehensive guidance on how we plan, execute, and continuously improve our projects.

## OctoAcme Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation** — Define problem, stakeholders, and high-level timeline
2. **Planning** — Break work into increments, estimate, align on resources
3. **Execution** — Build, test, review, and iterate
4. **Release** — Deploy, verify, and communicate
5. **Close & Retrospective** — Capture learnings and document next steps

## Documentation Index

### Core Resources

- [**Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, artifacts, and communication cadence
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Detailed descriptions of Project Managers, Product Managers, and Developers

### Project Lifecycle

- [**Project Initiation Guide**](octoacme-project-initiation.md) — Steps to validate ideas, align stakeholders, and authorize work
- [**Project Planning**](octoacme-project-planning.md) — How to create actionable plans, prioritized backlogs, and release timelines
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Managing day-to-day execution, quality, and progress
- [**Release & Deployment Guide**](octoacme-release-and-deployment.md) — Standardized release processes and rollback procedures

### Risk & Continuous Improvement

- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — How to identify, assess, and communicate risks and dependencies
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements

---

## OctoAcme Process Overview

OctoAcme operates a structured, lifecycle-driven project management approach that emphasizes customer value, iterative delivery, and clear ownership. The framework consists of five key phases: **Initiation** (validating business need and aligning stakeholders), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (building, testing, and reviewing with daily standups and weekly syncs), **Release** (deploying to production with pre-flight checks and rollback plans), and **Close & Retrospective** (capturing learnings and driving continuous improvement). This phased approach ensures projects move through a decision gate at each stage, with success metrics and stakeholder alignment confirmed before proceeding to the next phase.

The organization defines clear roles and responsibilities to minimize ambiguity and enable efficient execution. **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features, collaborate on design, and maintain quality standards; and **QA/Testing** validates acceptance criteria and quality. This role clarity, combined with a principle of psychological safety, enables cross-functional teams to work cohesively while maintaining accountability. Each project has a named PM and Product Lead, creating clear escalation paths and decision-making authority.

Communication and risk management are woven throughout OctoAcme's execution rhythm. Teams follow a consistent cadence of daily standups (15 minutes), weekly delivery syncs with the PM and Product Lead, and monthly stakeholder updates. Risk is managed through a simple but rigorous register—tracking ID, description, impact, likelihood, owner, and mitigation—with risks reviewed and updated during weekly syncs. A three-level escalation path (team-level triage → PM escalation → sponsor-level escalation) ensures blockers are surfaced and resolved quickly. Status is communicated via standardized weekly templates covering progress, next steps, risks, blockers, and decisions needed.

Quality and delivery excellence are embedded in OctoAcme's execution practices through lightweight, standards-based workflows. Teams maintain a project board with defined columns (Backlog, Ready, In Progress, In Review, QA, Done), enforce small PRs (≤400 lines when possible) with automated CI checks before review, require at least one approval before merging, and implement unit tests, integration tests, and end-to-end smoke tests for critical flows. Pre-release requirements include passing security scans, drafted release notes, and a documented rollback plan. After each sprint, release, or incident, retrospectives (45–75 minutes) are held to capture what went well, identify improvements, and create action items with clear owners and timelines—ensuring the team continuously learns and refines its processes.

---

## Getting Started

**New to OctoAcme projects?** Start with the [Project Management Overview](octoacme-project-management-overview.md).

**Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md).

**Currently executing?** Refer to the [Execution & Tracking](octoacme-execution-and-tracking.md) guide.

**Need to release?** Check the [Release & Deployment Guide](octoacme-release-and-deployment.md).

**Looking for role clarity?** Review the [Roles & Personas](octoacme-roles-and-personas.md) guide.

---

## Key Artifacts Used in OctoAcme Projects

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders, timeline, and initial risks
- **Roadmap and Release Plan** — Milestone-based delivery schedule and dependencies
- **Sprint/Iteration Backlog** — Prioritized work items with acceptance criteria and estimates
- **Risk Register** — Tracking ID, description, impact, likelihood, owner, mitigation, and status
- **Project Board** — Kanban-style tracking with columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Retrospective Notes & Action Items** — Learnings and improvements with owners and due dates

---

## Communication Cadence

- **Daily**: Team standups (15 minutes) — progress, blockers, dependencies
- **Weekly**: PM + PdM sync — alignment on priorities and risks
- **Bi-weekly**: Delivery team standup (or as agreed)
- **Monthly**: Stakeholder updates
- **As-needed**: Escalations and incident communication

---

## Questions or Feedback?

If you have questions about OctoAcme processes or suggestions for improving this documentation, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
