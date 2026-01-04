# Secretariat & Mailroom Workflow (Nintex Case Study)

This folder documents the design and implementation of a Secretariat
(Mailroom) workflow developed using SharePoint Server and Nintex Workflow.

The workflow was implemented across multiple factories to standardize
document intake, registration, review, approval, and archiving processes.

Due to platform upgrades and localization limitations, direct access to the
Nintex workflow designer is no longer available. This case study therefore
focuses on process design, approval logic, and execution evidence.

---

## Workflow Design (Nintex)

Multiple Nintex workflows were implemented as part of this solution, including:

- Mailroom / secretariat request handling
- Multi-level approval routing
- Conditional branching based on request type and confidentiality
- Automated notifications and archiving

Due to Nintex engine incompatibility following platform upgrades,
direct access to the workflow designer is no longer available.

For this reason, the workflows are documented using:
- Logical step-by-step process descriptions
- Reconstructed diagrams based on implementation knowledge
- Screenshots captured from production usage

---

## Scope of Implementation

- Deployed across **4 factories**
- Integrated with organizational portals
- Role-based approvals and notifications
- Combination of automated and manual decision steps
- Centralized handling of physical and electronic correspondence

---

## Key Objectives

- Centralize document intake and registration
- Ensure transparent and traceable approval flows
- Reduce manual follow-ups and operational delays
- Maintain full auditability of actions and decisions

---

## Technologies Used

- SharePoint Server (On-Prem)
- Nintex Workflow
- SharePoint Lists and Libraries
- Organizational Portals

---

## Supporting Artifacts

The following documents were used during analysis and implementation and are
included for contextual reference:

- **FL-MWF-010224-rev00.pdf**  
  Official workflow specification document describing the mailroom process,
  approval stages, and routing logic.

- **FV-010428-rev00.xlsx**  
  Data collection and form field mapping used during workflow and form design.

- **process-inputs.docx**  
  Initial process requirements gathered from business stakeholders during
  the analysis phase.

- **MNGReport-01.04.25-01.xlsx**  
  An anonymized and simplified management-level summary derived from
  operational data. All organizational names and sensitive identifiers
  have been abstracted for confidentiality.

---

## Screenshots

The `screenshots/` folder contains screenshots captured from the production
environment of the implemented workflow.

The images demonstrate:

- SharePoint list and form interfaces
- Nintex workflow structure and decision logic
- Approval task lists (cartable)
- Automated email notifications

Screenshots serve as execution evidence in the absence of the original
Nintex workflow definition.

> Note: Original artifacts are maintained in Persian, as they were created and
> used in a production environment within a Persian-speaking organization.
> Core workflow logic, roles, and approval flows are fully documented in
> English within this repository.

---

## Folder Structure

```text
workflow/
├── overview.md
├── process-flow-fa.md
├── process-flow-en.md
├── roles-and-approvals.md
├── artifacts/
│   ├── FL-MWF-010224-rev00.pdf
│   ├── FV-010428-rev00.xlsx
│   ├── process-inputs.docx
│   └── management-summary.xlsx
└── screenshots/
    ├── screenshot-01.png
    ├── screenshot-02.png
    └── ...
