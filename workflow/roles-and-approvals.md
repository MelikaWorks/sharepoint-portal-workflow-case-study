# Roles and Approval Structure

The workflow was implemented using a role-based approval model to ensure
clear responsibility boundaries, controlled access, and auditability
throughout the process.

## Defined Roles

- **Secretariat Operator**  
  Responsible for initial registration, metadata entry, and document routing.

- **Department Reviewer**  
  Reviews assigned correspondence and provides initial feedback or decisions.

- **Department Manager**  
  Performs managerial review and approval based on organizational rules.

- **Final Approver**  
  Provides final confirmation and closes the workflow process.

## Approval Logic

- Sequential approval paths based on correspondence type and routing rules
- Conditional branching for rejection, rework, or reassignment scenarios
- Escalation handling for delayed or unresponsive approval steps

## Access Control

- Role-based visibility of workflow tasks and items
- Edit permissions restricted to responsible roles at each stage
- Read-only access enabled for audit and tracking purposes
