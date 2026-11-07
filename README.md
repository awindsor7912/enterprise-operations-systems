# Billing Operations Management System (BOMS)

**Enterprise billing workflows · Business systems analysis · AI-assisted application development · Operational analytics**

![BOMS BANNER](BOMS.jpg)

> **Portfolio case study — employer-specific work.** Both initiatives documented here were undertaken in connection with employment at Infratech Corporation. This repository does **not** contain the employer's application, source code, database schemas, internal workflows, or customer information. This material is prepared for disclosure review and should be published only if authorized under applicable policies and agreements.

## Overview

BOMS is a professional case-study series covering two related stages of billing operations improvement. **Phase I** focused on structured workflow automation with Microsoft Power Platform. **Phase II** broadens the work toward an integrated billing operations experience that combines role-relevant workspaces, automation, reconciliation, validation, and management reporting.

The phases describe separate employer-specific initiatives, not two independently owned or publicly distributed software products.

| | Phase I: Workflow automation | Phase II: Billing operations consolidation |
|---|---|---|
| Focus | Intake coordination, routing, status visibility and reporting | Role-oriented work management, billing controls, reconciliation and operational intelligence |
| Technologies used | SharePoint, Power Automate, Power BI | Claude Artifact pilot; AI-assisted development; secure Azure-connected data access through MCP tools |
| Current presentation | Prior initiative, documented at a conceptual level | **Limited employee pilot**; broader deployment being considered |
| Public materials | Generalized architecture principles | Generalized functional summary, without implementation details |

## Business context

Billing operations often depend on multiple applications, manually assembled reports, repeated data entry, and human follow-up across roles. These fragmented processes complicate prioritization, reconciliation, and consistent validation. The initiatives explore ways to improve operational visibility and reduce repetitive manual work.

## Phase I — Workflow automation

Phase I focused on structuring billing-related work and automating administrative coordination. Its public-safe description covers workflow intake, assignment, processing visibility, exception awareness, and reporting.

See [Phase I overview](architecture/overview-and-logic-model.md) and [generalized automation pattern](architecture/automation-architecture.md).

## Phase II — Billing operations consolidation and intelligence

Phase II extends the scope into an application experience oriented around the needs of different users. In the current limited-user pilot, the reported and validated capabilities include:

- Personalized work views, processing queues, and follow-up activities.
- Automated preparation of billing documentation.
- High-level reconciliation between operational billing records and customer records.
- Identification of approval-dependent items and potential invoicing exceptions.
- Dynamic operational reporting and management-oriented visibility.

**My contribution:** Define and refine requirements, direct AI-assisted implementation through Claude, make functional design decisions, test and troubleshoot generated features, and validate behavior against business needs.

**Deployment status:** The pilot is hosted as a Claude Artifact, with secure access to relevant enterprise data through Azure-connected MCP tooling. Integration with an existing company system or a separately hosted Azure application is **under consideration**, not a completed deployment.

See [Phase II case study](phase-ii/overview.md), [generalized validation approach](phase-ii/validation-and-evaluation.md), and [reporting overview](analytics/reporting-dashboard.md).

## Outcomes and evidence

The pilot has demonstrated working automation and validation capabilities with a limited group of employees. Reduced manual processing has been observed, but comparative timing, error-rate, and financial-impact figures have **not** been independently documented in this public portfolio. No numeric productivity or compliance claims are asserted here.

## Documentation map

- [Phase I architecture overview](architecture/overview-and-logic-model.md)
- [Phase I automation pattern](architecture/automation-architecture.md)
- [Phase I conceptual data flow](architecture/data-flow.md)
- [Phase I generalized workflow](workflows/billing-workflow.md)
- [Phase II functional case study](phase-ii/overview.md)
- [Phase II quality and evaluation approach](phase-ii/validation-and-evaluation.md)
- [Operational reporting](analytics/reporting-dashboard.md)
- [Security and governance principles](governance/governance-and-hardening.md)
- [Public disclosure notice](DISCLOSURE.md)
- [Project website](https://awindsor7912.github.io/billing-operations-management-system/)

### Project Attribution & Confidentiality

Both phases of the Billing Operations Management System represent employer-specific initiatives undertaken during my employment with Infratech Corporation. The projects and their underlying intellectual property remain the property of Infratech Corporation.

This repository is independently maintained as a professional case study documenting my contributions, generalized technical concepts, and relevant professional competencies.

No proprietary source code, internal application architecture, confidential business information, customer records, or employer-specific implementation details are intentionally disclosed.

See [Project Attribution, Intellectual Property & Confidentiality](DISCLOSURE.md) for additional information.
