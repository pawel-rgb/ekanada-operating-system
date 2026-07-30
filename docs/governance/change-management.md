# Change Management Policy

## Metadata

**Document:** Change Management Policy

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
- Document Lifecycle Policy
- Document Classification Policy

---

# 1. Purpose

This policy defines how permanent documentation within the eKanada Operating System is changed after becoming part of the repository.

Its purpose is to ensure that documentation evolves in a controlled, transparent and consistent manner while preserving the integrity of the project's Sources of Truth.

This policy governs how changes are managed, not who owns documents or how they are approved.

---

# 2. Scope

This policy applies to all permanent documentation maintained within the repository, including governance documentation, Architecture Decision Records (ADRs), Knowledge Base documentation, workflows, templates, reference documentation and other permanent repository documents.

Temporary notes and unpublished working materials are outside the scope of this policy.

---

# 3. Change Management Principles

All permanent documentation shall evolve according to the following principles:

- changes shall be proportional to their impact;
- authoritative information shall remain internally consistent;
- related documentation shall be updated when necessary;
- historical decisions shall remain traceable;
- governance shall evolve deliberately rather than incrementally through unrelated edits.

---

# 4. Categories of Changes

Changes are classified according to their impact rather than their size.

## Editorial Changes

Editorial changes improve clarity without changing meaning.

Examples include spelling, grammar, formatting, broken links, typography and layout improvements.

Editorial changes normally do not require formal review unless defined otherwise by the Document Owner.

## Minor Changes

Minor changes improve documentation without changing governance or architectural intent.

Examples include clarifications, additional examples, improved explanations and non-substantive restructuring.

Minor changes should undergo review when they affect authoritative documentation or when required by the Approval Policy.

## Major Changes

Major changes modify authoritative content.

Examples include governance rules, architectural principles, responsibilities, approval requirements, Sources of Truth, repository structure and organizational standards.

Major changes require formal review and approval before becoming ACTIVE.

---

# 5. Review Requirements

Review is required whenever a proposed change:

- modifies authoritative content;
- affects multiple related documents;
- changes governance interpretation;
- changes architectural intent;
- introduces new responsibilities;
- affects approved Sources of Truth.

Review shall verify both the correctness of the change and its impact on the repository as a whole.

---

# 6. Approval Requirements

Approval is required whenever required by the Approval Policy.

No change becomes authoritative solely through editing.

---

# 7. Architecture Decision Records (ADR)

A new ADR should be created whenever a proposed change:

- introduces a new architectural decision;
- materially changes an existing architectural decision;
- supersedes an earlier architectural decision;
- records a significant architectural direction not previously documented.

Editorial revisions and routine document maintenance do not require a new ADR.

Where appropriate, an existing ADR may be updated rather than creating a new one.

---

# 8. Maintaining Repository Consistency

When a document changes, related documentation should be reviewed for consistency.

This may include governance documents, ADRs, Knowledge Base documentation, workflows, templates, references, repository indexes and cross-references.

Consistency should be considered part of the change rather than a separate activity.

---

# 9. Managing Cross-Document Changes

Some changes affect multiple documents simultaneously.

When this occurs:

- related documents should be identified before approval;
- dependent documentation should be updated as part of the same change whenever practical;
- temporary inconsistencies between related documents shall be avoided wherever reasonably practicable;
- superseded references should be removed or updated.

The objective is to preserve a coherent repository at all times.

---

# 10. Traceability

Significant changes should remain traceable.

Traceability may be maintained through:

- version identifiers;
- repository history;
- commit history;
- documented review;
- ADRs where applicable;
- documented approvals.

Historical traceability supports future maintenance and governance decisions.

---

# 11. Responsibilities

## 00 – Architecture

Responsible for changes affecting governance, architecture and repository-wide standards.

## Document Owner

Responsible for initiating revisions, maintaining document accuracy, coordinating review where required and ensuring related documentation remains consistent.

## Reviewers

Responsible for evaluating proposed changes, identifying inconsistencies and recommending whether changes are ready for approval.

---

# 12. Relationship to Other Policies

This policy defines how permanent documentation evolves over time.

It does not define:

- document ownership (Document Ownership);
- lifecycle states (Document Lifecycle Policy);
- approval authority (Approval Policy);
- document classification (Document Classification Policy);
- Source of Truth hierarchy (Source of Truth Policy);
- human decision authority (Human-in-the-Loop Policy).

These governance policies should be interpreted together.

---

# Related Documents

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1
- Source of Truth Policy
- Document Ownership
- Approval Policy
- Human-in-the-Loop Policy
- Document Lifecycle Policy
- Document Classification Policy
