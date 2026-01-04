# Secretariat & Mailroom Workflow (Nintex Case Study)

This section documents the design and implementation of a Secretariat
(Mailroom) workflow developed using SharePoint Server and Nintex Workflow.

The workflow was implemented across multiple factories to standardize
document intake, registration, review, approval, and archiving processes.

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
  Mailroom workflow specification document

- **FV-010428-rev00.xlsx**  
  Data collection and form field mapping sheet

- **process-inputs.docx**  
  Initial process requirements gathered from business stakeholders

> Note: Original artifacts are maintained in Persian, as they were created and
> used in a production environment within a Persian-speaking organization.
> Core workflow logic, roles, and approval flows are fully documented in
> English within this repository.
