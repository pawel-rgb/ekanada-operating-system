# Document Classification Policy

## Metadata

**Document:** Document Classification Policy

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

---

# 1. Purpose

This policy defines the official classes of documentation used within the eKanada Operating System.

Its purpose is to ensure that every permanent document has a clearly defined role, level of authority, ownership and location within the repository. Each document class exists to support a distinct function and should not duplicate the responsibilities of another class.

---

# 2. Scope

This policy applies to all permanent documentation stored in the repository.

Temporary notes, brainstorming materials, chat conversations and unpublished working files are outside the scope of this policy until they are incorporated into repository documentation.

---

# 3. Classification Principles

Every permanent document shall belong to a single primary document class.

Document classes determine:

- the document's purpose;
- its expected level of authority;
- its typical owner;
- its location within the repository;
- its relationship to other documentation.

Classification defines the role of a document, not its lifecycle or approval requirements.

The repository locations defined in this policy represent the default documentation structure of the project. Changes to these locations should be introduced only through an approved architectural decision, such as an ADR.

---

# 4. Governance Documents

**Purpose**

Define policies, standards, rules and governance of the eKanada Operating System.

**Characteristics**

- normative;
- organization-wide;
- long-term;
- authoritative.

**Authority**

Highest.

Governance documents define how the project operates.

**Typical Owner**

00 – Architecture

**Repository Location**

`docs/governance/`

---

# 5. Architecture Decision Records (ADR)

**Purpose**

Record significant architectural decisions together with their context, rationale and consequences.

**Characteristics**

- historical;
- decision-oriented;
- immutable except for corrections or status updates.

**Authority**

Authoritative record of architectural decisions.

**Typical Owner**

00 – Architecture

**Repository Location**

`docs/architecture/adr/`

---

# 6. Knowledge Base

**Purpose**

Capture reusable knowledge supporting the project.

Examples include:

- brand information;
- educational knowledge;
- organizational knowledge;
- technical references.

**Characteristics**

- descriptive;
- reusable;
- continuously maintained.

**Authority**

Authoritative only within its defined subject area, provided that its content is not superseded or governed by Governance documentation.

**Typical Owner**

Relevant Module Owner.

**Repository Location**

`knowledge-base/`

---

# 7. Workflow Documents

**Purpose**

Describe repeatable operational processes.

Examples:

- publishing procedures;
- review workflows;
- production processes;
- automation workflows.

**Characteristics**

- process-oriented;
- instructional;
- operational.

**Authority**

Authoritative for the defined workflow.

**Typical Owner**

Responsible Module Owner.

**Repository Location**

`workflows/`

---

# 8. Templates

**Purpose**

Provide standardized structures for creating consistent project artifacts.

Examples:

- document templates;
- lesson templates;
- presentation templates;
- review templates.

**Characteristics**

- reusable;
- standardized;
- implementation-oriented.

**Authority**

Authoritative only as structural guidance.

Templates do not define policy.

**Typical Owner**

Relevant Module Owner.

**Repository Location**

`templates/`

---

# 9. Reference Documents

**Purpose**

Preserve external or internal reference material used for consultation.

Examples:

- legislation;
- specifications;
- research;
- standards;
- vendor documentation.

**Characteristics**

- informational;
- non-governing;
- evidence-based.

**Authority**

Reference only.

They do not establish project governance.

**Typical Owner**

Relevant Module Owner.

**Repository Location**

`references/`

---

# 10. Repository Documentation (README)

**Purpose**

Provide navigation and structural guidance for the repository, its modules and directory hierarchy.

**Characteristics**

- descriptive;
- navigational;
- repository-oriented;
- maintained alongside repository structure.

**Authority**

Authoritative for repository navigation and documentation structure within its scope, but does not establish governance.

**Typical Owner**

Responsible Module Owner or 00 – Architecture, depending on scope.

**Repository Location**

README files throughout the repository, including the repository root and module directories.

---

# 11. Operational Documentation

**Purpose**

Support day-to-day execution of project activities.

Examples include:

- campaign documentation;
- production checklists;
- planning documents;
- operational guides.

**Characteristics**

- practical;
- execution-focused;
- regularly updated.

**Authority**

Limited to the operational context in which they are used.

Operational documentation does not establish governance or modify approved project policies.

**Typical Owner**

Responsible Module Owner.

**Repository Location**

Examples include:

- `campaigns/`
- `automation/`
- other operational directories as appropriate.

---

# 12. Cross-References

Documents may reference documents belonging to other classes.

However:

- governance documents shall not be replaced by Knowledge Base documents;
- Knowledge Base documents shall not redefine governance;
- workflows shall not redefine governance;
- templates shall not establish policy;
- reference documents shall not become Sources of Truth without explicit adoption.

Each document should remain within the responsibility of its own class.

---

# 13. Responsibilities

## 00 – Architecture

Responsible for defining and maintaining document classifications.

---

## Document Owners

Responsible for ensuring that documents are classified correctly and remain in the appropriate repository location.

---

## Module Owners

Responsible for maintaining documentation belonging to their respective functional areas.

---

# 14. Relationship to Other Policies

This policy defines **what kinds of documents exist** within the repository.

It does not define:

- ownership responsibilities (Document Ownership);
- document lifecycle (Document Lifecycle Policy);
- approval procedures (Approval Policy);
- human decision authority (Human-in-the-Loop Policy);
- Source of Truth hierarchy (Source of Truth Policy).

These policies should be interpreted together.

---

# Related Documents

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1
- Source of Truth Policy
- Document Ownership
- Approval Policy
- Human-in-the-Loop Policy
- Document Lifecycle Policy
