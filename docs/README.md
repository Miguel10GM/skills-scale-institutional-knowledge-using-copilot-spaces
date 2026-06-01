# OctoAcme Project Management Documentation

Welcome! This README provides an overview of the project management processes used at OctoAcme, and offers easy links to all detailed documents in this repository.

## OctoAcme Project Management Overview

OctoAcme operates a structured, lifecycle-based project management approach designed around five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The organization emphasizes customer-first delivery through iterative increments, with clear ownership distributed between a Project Manager (who coordinates schedules, risks, and communications) and a Product Manager (who defines outcomes and prioritizes the backlog).

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver work in small, testable increments
- **Clear ownership**: Named Project Manager (PM) and Product Lead for each project
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement
- **Transparency**: Share decisions, rationale, and processes across all team members

### Key Workflows

**Execution & Quality**: Execution at OctoAcme is underpinned by a disciplined team rhythm featuring daily 15-minute standups, weekly delivery syncs, and transparent project boards using GitHub Projects. Small pull requests (≤400 lines when possible) flow through automated CI checks for tests, linting, and security scanning before human review. Quality assurance is embedded throughout with unit tests, integration tests, end-to-end smoke tests for critical flows, and manual QA for feature acceptance.

**Risk & Communication**: Risk management is woven throughout operations via a maintained Risk Register tracking threats by impact, likelihood, mitigation, and status. Cross-functional dependencies are surfaced early in planning and monitored continuously. Communication is standardized through weekly status templates and milestone-based stakeholder updates, with a three-tier blocker escalation path (team triage → PM to Product Lead → sponsor escalation).

**Continuous Improvement**: Each cycle closes with structured retrospectives (45–75 minutes after sprints, releases, or milestones) to capture learnings, identify improvements, and assign 2–3 prioritized action items with clear owners and due dates. These improvements feed back into the backlog, and their impact is measured and celebrated, ensuring OctoAcme evolves its processes based on real team experience.

## Key Project Management Docs

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight initial plan
- **[Project Planning Guide](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, communicate risks, and escalate blockers
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how to release features to production safely and observably
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand roles, principles, and the project lifecycle.
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate the idea and gain stakeholder alignment.
- **Executing a project?** Use [Project Planning](octoacme-project-planning.md), [Execution & Tracking](octoacme-execution-and-tracking.md), and [Risk Management & Communication](octoacme-risks-and-communication.md) as your guide.
- **Preparing a release?** Refer to the [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release requirements and deployment checklists.
- **Closing a cycle?** Use the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings and drive improvements.

## Contributing to Process Documentation

To suggest updates, additions, or clarifications to these process documents, please open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template. This helps us maintain a living, collaborative knowledge base that evolves with team feedback and organizational needs.