# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management Documentation Hub. This folder contains comprehensive guides for running projects at OctoAcme using our standardized, customer-first approach to delivery.

## Quick Overview

OctoAcme follows a structured, customer-centric lifecycle that moves projects through five key phases:

1. **Initiation** – Validate business need, align stakeholders, and authorize work
2. **Planning** – Break work into shippable increments with clear acceptance criteria
3. **Execution** – Build, test, iterate, and track progress daily
4. **Release** – Deploy to production with safety checks and observability
5. **Retrospective** – Capture learnings and drive continuous improvement

## Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has named PM and Product Lead roles
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Project Management Overview

OctoAcme emphasizes a structured, customer-centric lifecycle where projects move through five distinct phases. During **Initiation**, teams validate the business need by creating a lightweight One-pager that defines the problem statement, success metrics, stakeholders, and initial timeline—this serves as the decision gate to move forward. Once approved, the **Planning phase** transforms the initiative into an actionable roadmap by breaking work into prioritized backlog items with clear acceptance criteria, estimating scope, and identifying dependencies and risks.

**Execution** forms the operational heartbeat of OctoAcme projects. Teams adopt a structured rhythm of daily standups (15 min), weekly delivery syncs, and sprint-based iterations using GitHub Projects. Pull requests follow a lightweight discipline with clear issue links and acceptance criteria, automated CI testing and linting, and at least one peer approval before merge. Quality is embedded throughout via unit and integration tests, end-to-end smoke tests, security scanning, and manual QA when needed.

Communication and risk management are woven throughout the framework to maintain stakeholder alignment and catch issues early. A **Risk Register** tracks potential blockers by ID, description, impact, likelihood, owner, and mitigation plan, with escalation paths running from team-level triage in standups → PM escalation → Product Lead → Sponsor. Weekly status updates, milestone-based reports, and role-specific communication cadences keep all parties informed.

Finally, OctoAcme closes the loop through structured **Release & Deployment** and **Retrospective & Continuous Improvement** practices. Releases follow a formal checklist with pre-release validation, passing CI/security scans, staging smoke tests, production deployment, and post-deploy verification. After each sprint or milestone, teams conduct structured retrospectives to capture learnings and assign prioritized action items, embedding continuous improvement into the organizational culture.

## Documentation Index

### Getting Started
- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** – High-level introduction to roles, artifacts, and lifecycle. Start here if you're new to OctoAcme PM.
- **[Roles & Personas](octoacme-roles-and-personas.md)** – Definitions of core roles (PM, Product Manager, Developers, QA) and responsibilities.

### Phase-by-Phase Guides
- **[Project Initiation](octoacme-project-initiation.md)** – Steps for validating and authorizing new projects, creating a One-pager, and decision gates.
- **[Project Planning](octoacme-project-planning.md)** – How to build a prioritized backlog, estimate scope, identify dependencies, and create a release plan.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** – Daily workflows, standups, PR practices, quality standards, and blocker escalation.
- **[Release & Deployment](octoacme-release-and-deployment.md)** – Pre-release requirements, deployment checklists, and rollback procedures.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** – How to run retrospectives and track action items.

### Cross-Cutting Topics
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** – Maintaining a risk register, stakeholder communication templates, and escalation paths.

## How to Use These Docs

- **Project Managers** – Start with Initiation and Planning, refer to Execution and Risk Management throughout delivery.
- **Product Managers** – Focus on Project Initiation and Planning, collaborate on success metrics and backlog prioritization.
- **Developers & QA** – Review Execution & Tracking, Definition of Done, and quality expectations.
- **Stakeholders** – See Project Management Overview and Risk Management & Communication for status templates and escalation info.

## Templates & Artifacts

Each process document includes templates and checklists for:
- Project One-pager
- Backlog items and acceptance criteria
- Risk register
- Weekly status updates
- Incident communication
- Retrospective action items

See `.github/ISSUE_TEMPLATE/` for GitHub issue templates that support these processes.

## Contributing & Feedback

These docs are living artifacts. If you have feedback, identify gaps, or want to propose improvements, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
