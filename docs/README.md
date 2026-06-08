# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This README provides a concise overview of our project management processes, key roles and communication patterns, quality assurance practices, and direct links to the detailed process documents in this folder.

## Summary of Project Management Processes

OctoAcme follows a structured, iterative lifecycle designed to deliver customer value with clear governance. Work progresses through five main phases: Initiation, Planning, Execution & Tracking, Release & Deployment, and Retrospective & Continuous Improvement. Initiation establishes the problem, success metrics, stakeholders, and a lightweight Project One-pager. Planning decomposes work into prioritized, shippable backlog items with estimates and dependency mapping. Execution uses GitHub Projects and small, frequent increments with daily standups and ongoing demos. Releases are controlled with pre-release checklists and rollback plans, and retrospectives capture learnings for continuous improvement.

## Key Workflows & Roles

Clear ownership and role definitions are central to OctoAcme. Product Managers (PdM) define desired outcomes, prioritize the backlog, and measure success. Project Managers (PM) coordinate delivery, manage timelines, risks, and communications. Developers build and test features, and QA validates the work against acceptance criteria. Communication is rhythmic and intentional: daily standups to surface progress and blockers, weekly PM/PdM syncs, sprint demos/reviews, and monthly stakeholder updates. A Risk Register is maintained and reviewed regularly; escalation follows team → PM → Product Lead → Sponsor as needed.

## Quality Assurance & Release Practices

Quality is embedded across the lifecycle. Teams are expected to add unit and integration tests, use automated CI pipelines for tests and linting, and run end-to-end smoke tests for critical flows before production. Pull requests should be small, include acceptance criteria and issue links, and pass CI/security scans before merging. Releases require documented notes, verification steps, and rollback plans. Incidents trigger on-call response and a blameless retrospective to capture corrective actions.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)  
- [Project Initiation Guide](octoacme-project-initiation.md)  
- [Project Planning](octoacme-project-planning.md)  
- [Execution & Tracking](octoacme-execution-and-tracking.md)  
- [Risk Management & Communication](octoacme-risks-and-communication.md)  
- [Release & Deployment Guide](octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)  
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use this hub

- Use this README as the entry point for onboarding and quick reference.
- Link to individual docs for detailed processes, templates, and checklists.
- Suggested next step: create a project README that references the Project One-pager and links back to this docs index.
