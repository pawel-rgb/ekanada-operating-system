# Document Lifecycle Policy

## Metadata

**Document:** Document Lifecycle Policy

**Version:** 1.0

**Status:** ACTIVE

**Owner:** 00 – Architecture

**Related:**
- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1
- Source of Truth Policy
- Document Ownership
- Approval Policy
- Human-in-the-Loop Policy

---

# 1. Purpose

This policy defines the lifecycle of permanent documentation within the eKanada Operating System.

Its purpose is to establish a consistent process for creating, reviewing, approving, activating, maintaining and retiring documentation while preserving repository integrity and historical traceability.

This document complements the Approval Policy by defining the operational lifecycle of documents rather than the approval process itself.

---

# 2. Scope

This policy applies to all permanent documentation stored within the eKanada Operating System repository, including governance documents, Architecture Decision Records (ADRs), standards, workflows, Knowledge Base documentation, templates and reference materials.

Temporary working notes, drafts outside the repository and conversational content are outside the scope of this policy unless incorporated into permanent documentation.

---

# 3. Relationship to Approval Policy

The Approval Policy defines:

- review requirements;
- approval authority;
- document activation.

This policy defines:

- document lifecycle states;
- permitted transitions;
- version evolution;
- retirement;
- archival;
- long-term maintenance.

The two policies are complementary and should be interpreted together.

---

# 4. Lifecycle Principles

The document lifecycle shall:

- preserve a single authoritative version of every ACTIVE document;
- maintain complete traceability of significant revisions;
- ensure that no document becomes authoritative without approval;
- preserve historical versions where appropriate;
- minimize ambiguity regarding document status.

---

# 5. Document Statuses

Every permanent document shall have exactly one lifecycle status.

A document shall never have more than one lifecycle status at the same time.

## DRAFT

The document is under development.

**Characteristics:**

- content may change significantly;
- review has not yet been completed;
- the document is not authoritative.

---

## REVIEW

The document is undergoing formal review.

**Characteristics:**

- comments and recommendations are collected;
- revisions may still occur;
- no approval has yet been granted.

---

## APPROVED

The document has successfully completed review and has received formal approval.

**Characteristics:**

- content is considered final;
- awaiting repository commit and activation;
- not yet the active authoritative version.

---

## ACTIVE

The document is the current authoritative version.

**Characteristics:**

- may be referenced by other documentation;
- governs the applicable scope;
- remains active until superseded, deprecated or archived.

---

## DEPRECATED

The document remains available for historical or compatibility purposes but should no longer be used for new work.

**Characteristics:**

- retained for reference;
- replacement should normally exist;
- no further development is expected except exceptional corrections.

---

## ARCHIVED

The document is retained solely for historical record.

**Characteristics:**

- no longer participates in project governance;
- not maintained;
- preserved for traceability.

---

# 6. Lifecycle Transitions

The normal lifecycle is:

```text
DRAFT
   ↓
REVIEW
   ↓
APPROVED
   ↓
ACTIVE
   ↓
DEPRECATED
   ↓
ARCHIVED
```

Additional permitted transitions include:

- REVIEW → DRAFT
- ACTIVE → REVIEW
- DEPRECATED → REVIEW (exceptional cases)
- REVIEW → ARCHIVED (document abandoned before completion)

Transitions should occur only when justified by project needs.

---

# 7. Versioning

Every permanent document shall include a version identifier.

Recommended versioning:

- Major versions for structural, governance or architectural changes.
- Minor versions for substantive improvements.
- Patch versions for editorial corrections where version granularity is required.

Examples:

- 1.0
- 1.1
- 2.0

The repository may adopt additional versioning conventions provided they remain consistent across the repository.

---

# 8. Revising ACTIVE Documents

ACTIVE documents remain living documents.

When revision is required:

- the existing document should be updated rather than duplicated, unless a new document is justified;
- the scope of the change should determine the review process;
- related documentation should be evaluated for consistency;
- revisions should preserve repository history and traceability.

Approval requirements are governed by the Approval Policy.

---

# 9. Superseding Documents

A document may supersede another document when it fully replaces its purpose.

When this occurs:

- the replacement should reference the superseded document where appropriate;
- the previous document should normally become DEPRECATED;
- historical references should remain valid whenever practical.

Superseding documentation should preserve continuity rather than fragment repository history.

---

# 10. Archival

Documents may be archived when they:

- no longer serve an operational purpose;
- have been superseded;
- are retained only for historical reference.

Archived documents should remain accessible within the repository unless legal or security requirements dictate otherwise.

Archiving does not invalidate historical decisions that were made while the document was ACTIVE.

---

# 11. Repository Consistency

Whenever a document changes lifecycle status, related documentation should be reviewed for consistency.

This may include:

- references between governance documents;
- ADR references;
- Knowledge Base links;
- templates;
- workflow documentation;
- cross-document references.

The objective is to preserve a coherent Source of Truth across the repository.

---

# 12. Responsibilities

## 00 – Architecture

Responsible for lifecycle governance of architecture and governance documentation.

---

## Document Owner

Responsible for:

- maintaining document accuracy;
- initiating revisions;
- coordinating lifecycle transitions;
- ensuring consistency with related documentation.

---

## Reviewers

Responsible for evaluating proposed revisions and recommending whether a document is ready to progress through the lifecycle.

---

# 13. Relationship to Other Policies

This policy defines the operational lifecycle of permanent documentation.

It does not define:

- ownership (Document Ownership);
- approval authority (Approval Policy);
- Source of Truth hierarchy (Source of Truth Policy);
- human decision authority (Human-in-the-Loop Policy).

These policies should be interpreted together.

---

# Related Documents

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1
- Source of Truth Policy
- Document Ownership
- Approval Policy
- Human-in-the-Loop Policy
