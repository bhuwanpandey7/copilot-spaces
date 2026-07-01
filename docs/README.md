# OctoAcme Project Management Documentation

## Overview

This directory contains comprehensive documentation of OctoAcme's project management processes, methodologies, and best practices. Whether you're onboarding to a new project, planning a release, or looking to understand our approach to execution and continuous improvement, you'll find guidance here.

## OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer-first principles and iterative delivery. The organization standardizes work across five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. 

During initiation, teams validate business needs and create a lightweight Project One-pager that defines the problem, goals, success metrics, and stakeholders. Once approved, the planning phase breaks work into a prioritized, estimated backlog with clear acceptance criteria and a release timeline. This foundation ensures alignment before development begins and reduces downstream rework.

The execution phase emphasizes daily team rhythm and transparency through standups (15 min), weekly delivery syncs, and regular demos. Work flows through a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests follow a lightweight standard—kept to ≤400 lines when possible—with acceptance criteria and issue links in descriptions. Quality is enforced through unit tests, integration tests, and end-to-end smoke tests before release, along with security scanning in CI. This disciplined approach to code review and testing reduces defects and maintains velocity.

OctoAcme defines clear roles to avoid ambiguity: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what should be built and measure outcomes; and **Developers** implement features while collaborating on design and testability. Communication is structured through weekly PM-PdM syncs, twice-weekly standups, and monthly stakeholder updates, with escalation paths for blockers (team → PM → Product Lead → Sponsor). Risk management is proactive—teams maintain a Risk Register during planning and review it weekly, capturing ID, description, impact, likelihood, owner, and mitigation plans.

Finally, OctoAcme closes projects with blameless retrospectives that capture what went well, what could improve, and actionable next steps. These improvements feed back into the backlog and process docs, creating a continuous improvement culture. Release practices include pre-release checklists, smoke tests in staging, automated deployments when possible, and a documented rollback playbook for incidents. This comprehensive lifecycle—from initiation through retrospective—enables consistent, repeatable project execution while maintaining psychological safety and evidence-based decision-making.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Documentation Index

Navigate to the process document most relevant to your current project phase:

| Phase | Document | Purpose |
|-------|----------|---------|
| **Overview** | [Project Management Overview](./octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, key artifacts, and lifecycle |
| **Initiation** | [Project Initiation](./octoacme-project-initiation.md) | Validate business need, align stakeholders, and authorize work |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments and create actionable plans |
| **Execution** | [Execution and Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day execution, quality standards, and progress tracking |
| **Risk & Communication** | [Risks and Communication](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| **Release** | [Release and Deployment](./octoacme-release-and-deployment.md) | Standardize release processes and reduce deployment risk |
| **Retrospective** | [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive continuous improvements |
| **Reference** | [Roles and Personas](./octoacme-roles-and-personas.md) | Detailed definitions of Project Managers, Product Managers, and Developers |

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach.
2. **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) guide.
3. **In active delivery?** Reference [Execution and Tracking](./octoacme-execution-and-tracking.md) and [Risks and Communication](./octoacme-risks-and-communication.md).
4. **Preparing a release?** See [Release and Deployment](./octoacme-release-and-deployment.md).
5. **Project complete?** Run a retrospective using [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

## Key Artifacts & Templates

Across these docs, you'll find templates and checklists for:

- **Project One-pager** (initiation)
- **Backlog Item Template** (planning)
- **Definition of Done** (planning)
- **Risk Register** (planning & execution)
- **Weekly Status Template** (communication)
- **Release Notes Template** (release)
- **Action Item Template** (retrospective)

## Communication Cadence

- **Daily**: Standups (15 min focus on progress, blockers, dependencies)
- **Twice-weekly**: Delivery team standups (or as agreed)
- **Weekly**: PM + PdM sync; weekly stakeholder risk review
- **Monthly**: Stakeholder updates
- **As needed**: Blocker escalations and incident communications

## Questions or Feedback?

If you have questions about these processes or want to suggest improvements, please:

- Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- Reach out to your Project Manager or Product Lead
- Contribute improvements via pull request

---

**Last updated:** 2026-07-01
