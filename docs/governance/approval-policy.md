# Approval Policy

## Metadata

**Document:** Approval Policy

**Version:** 1.0

**Status:** ACTIVE

**Owner:** 00 – Architecture

**Related:**

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1
- Source of Truth Policy
- Document Ownership

---

## 1. Purpose

This policy defines the governance process for reviewing, approving, activating and changing permanent documentation within the eKanada Operating System.

Its purpose is to ensure that all authoritative documentation follows a consistent lifecycle before becoming part of the project's permanent documentation.

This policy complements, but does not replace:

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1
- Source of Truth Policy
- Document Ownership

---

## 2. Scope

This policy applies to all permanent documentation maintained in the repository, including governance documents, architecture documentation, standards, workflows, templates, Knowledge Base documentation and ADRs.

---

## 3. Definitions

### Review

A structured evaluation of a proposed document to verify correctness, consistency, completeness and compliance with project governance.

### Approval

Formal acceptance of a reviewed document by the appropriate authority.

### Activation

The point at which an approved document becomes part of the active governance of the project.

### Revision

Any modification to an existing ACTIVE document.

---

## 4. Document Lifecycle

1. DRAFT
2. REVIEW
3. APPROVED
4. ACTIVE
5. DEPRECATED
6. ARCHIVED

---

## 5. Review Process

Every governance or architecture document must undergo review before approval.

Review verifies alignment with Project Instructions, accepted ADRs, governance consistency, repository consistency and scope.

---

## 6. Approval Authority

System-wide governance and architecture documentation require approval by the Owner responsible for global governance as defined in the Document Ownership policy.

Module-specific documentation may be approved by the responsible Module Owner provided it does not modify global governance.

No document becomes authoritative through discussion alone.

---

## 7. Activation

After approval:

- the document is committed to the repository;
- its status changes from **APPROVED** to **ACTIVE**;
- related documentation should be updated where necessary;
- previous versions should be superseded or archived according to project governance.

Activation represents the official adoption of the document. A document becomes **ACTIVE** only after it has been approved and recorded in the repository.

---

## 8. Document Changes

Changes to ACTIVE documents should be proportional to their impact.

Editorial changes may follow a simplified review process.

Structural, governance or architectural changes require formal review and approval before activation.

Where a change introduces a new architectural decision or materially changes an existing architectural decision, a new ADR or an update to an existing ADR should be created, as appropriate. Not all significant document revisions require a new ADR.

---

## 9. Responsibilities

### 00 – Architecture

Approves governance policies, architecture documentation, ADRs and cross-project standards.

### Document Owner

Maintains document accuracy, coordinates review and revisions.

### Reviewers

Evaluate proposed changes and recommend approval.

---

## 10. Relationship to Other Policies

This policy defines how documentation becomes authoritative. Ownership, Sources of Truth and Human-in-the-Loop are defined in separate governance documents.

---

## Related Documents

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1
- Source of Truth Policy
- Document Ownership
- Human-in-the-Loop Policy
