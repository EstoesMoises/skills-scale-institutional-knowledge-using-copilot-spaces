# OctoAcme Project Management Docs

This README serves as the central entry point for OctoAcme's project management documentation. Use it to quickly orient yourself to our approach, find the right process document, and understand the end-to-end lifecycle of how we deliver software.

## Project Management Processes Summary

OctoAcme follows a structured, iterative lifecycle to deliver product features and services. Projects begin with an **Initiation** phase where the problem statement, success metrics, and stakeholder alignment are validated via a Project One-pager before a go/no-go decision is made. Once approved, the **Planning** phase breaks work into shippable increments, creates a prioritized backlog with acceptance criteria and estimates, documents dependencies in a Risk Register, and maps out a release plan with clear milestones. During **Execution & Tracking**, teams operate in regular sprints with daily standups, weekly delivery syncs, and end-of-sprint demos. Progress is measured against velocity and success metrics, and blockers are escalated through a three-tier path (team → PM → Product Lead → Sponsor). When features are ready, the **Release & Deployment** process ensures every change is covered by a deployment checklist, passing CI and security scans, documented rollback plan, and post-deploy verification before announcements go out. After each release or sprint, a **Retrospective** captures what went well and what to improve, with action items tracked in the backlog to drive continuous improvement.

The team is built around five key **personas**: the **Project Manager (PM)**, who coordinates delivery, schedules, and cross-team communication; the **Product Manager (PdM/Product Lead)**, who defines outcomes and prioritizes the backlog; **Developers**, who implement, test, and review code; **QA/Testing**, who validate acceptance criteria; and **Stakeholders**, who provide inputs and approvals. Each role has defined responsibilities, communication norms, and goals documented in the Roles & Personas guide, ensuring clear ownership at every stage of the project.

**Communication** runs on a predictable cadence: weekly PM + PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates, supplemented by ad-hoc escalations when needed. A single source of truth—the project README or release doc—keeps everyone aligned. Standard templates for weekly status updates and incident communications reduce noise and ensure consistent reporting. **Quality assurance** is baked into every phase: PRs are kept small (≤ 400 lines), must include linked issues and acceptance criteria, and require at least one approval after automated tests and linting pass in CI. Security scans run in the pipeline, manual QA covers feature acceptance, and every release follows a checklist-driven deployment with a documented rollback and incident playbook.

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle, and communication cadence |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate, authorize, and kick off new projects |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, sprint planning, and release mapping |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflows, PR conventions, QA, metrics, and escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, risk lifecycle, stakeholder communication, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running retrospectives, and tracking improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for Developers, Product Managers, and Project Managers |
