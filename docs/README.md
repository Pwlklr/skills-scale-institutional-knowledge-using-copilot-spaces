# OctoAcme Project Management Documentation

## Welcome to OctoAcme Project Management

OctoAcme follows an iterative, customer-first approach to project delivery with clear roles, ownership, and structured processes. This documentation suite provides guidance for managing projects from initiation through retrospective and continuous improvement.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a structured five-stage lifecycle:

1. **Initiation** — Validate business need, align stakeholders, create lightweight plan
2. **Planning** — Break work into shippable increments, identify dependencies and risks
3. **Execution** — Build, test, review, and iterate
4. **Release** — Deploy, verify, and announce to stakeholders
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

## OctoAcme Project Management Processes Overview

OctoAcme follows a structured five-stage project lifecycle with clear ownership across defined personas. **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure impact; **Developers** implement features and contribute to estimation; and **QA/Testing** validates quality against acceptance criteria. 

Communication happens through a structured cadence: twice-weekly standups for delivery teams, weekly syncs between PM and Product Lead, and monthly stakeholder updates. Risks escalate through three levels: team-level triage in standups, PM escalation to Product Lead for cross-team issues, and sponsor-level escalation for business-impacting problems.

Quality is embedded throughout execution with unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Before release, all acceptance criteria must be met and CI/security scans must pass. The team conducts regular retrospectives (45–75 minutes per sprint or milestone) to capture learnings, track action items, and measure improvement impact, embedding quality and continuous learning into the project culture.

## Documentation Guide

### Essential Reading

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** — Start here to understand core roles, artifacts, and communication cadence

### Process Documentation by Lifecycle Phase

#### Initiation
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define initial steps to validate and authorize work, align stakeholders, and create a lightweight plan

#### Planning
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into actionable plans and backlogs for delivery

#### Execution
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones

#### Release
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized approach to releasing features to production with reduced risk

#### Close & Retrospective
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Guidance

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies throughout the project lifecycle
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of key roles (Product Manager, Project Manager, Developer, QA) and their responsibilities

## Using These Docs in Copilot Spaces

These process documents are designed to be used as context in Copilot Spaces. When working on project management tasks, reference the relevant documentation to:

- Ensure consistent terminology and processes
- Access templates and checklists
- Find guidance on roles and responsibilities
- Review best practices for your current project phase

## Key Artifacts Across the Lifecycle

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Risk Register
- Status Updates and Communications
- Retrospective Notes

## Communication Cadence

- **Weekly**: Sync between PM + Product Manager
- **Twice-weekly**: Standups for delivery team (or as agreed)
- **Monthly**: Stakeholder updates
- **As needed**: Ad-hoc escalations and incident communications

## Quick Links

- [All Process Docs](./)
- [Issue Templates](../.github/ISSUE_TEMPLATE/)
