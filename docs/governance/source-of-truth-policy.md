# Source of Truth Policy

## 1. Purpose

This policy defines how eKanada Operating System identifies, prioritizes and maintains authoritative information.

Its purpose is to ensure that:

- every important decision has a single authoritative source;
- conflicting information can be resolved consistently;
- documentation remains maintainable as the system grows;
- ChatGPT, Codex and future tools rely on the same governance model.

This policy implements the principles defined in:

- Project Instructions v1.1
- ADR-001

---

## 2. Scope

This policy applies to the entire eKanada Operating System, including:

- repository documentation;
- ChatGPT project conversations;
- Knowledge Base;
- architecture documentation;
- operational standards;
- future automation;
- future AI agents.

---

## 3. Definitions

### Source of Truth

The single authoritative location where a specific type of information is maintained.

A Source of Truth is responsible for accuracy, maintenance and long-term consistency.

### Authoritative Information

Information that has been formally accepted and maintained according to project governance.

Authoritative information takes precedence over drafts, proposals and unpublished work.

### Working Artifact

Any temporary or unpublished material, including drafts, notes, briefs, prototypes, work in progress and AI-generated proposals.

Working Artifacts are not authoritative.

### Published Output

A completed and approved deliverable intended for official use.

Published Outputs are official products but do not automatically become Sources of Truth.

---

## 4. Source of Truth Model

The project uses a layered governance model.

### Layer 1 — Global Governance

Includes Project Instructions, approved global policies and accepted ADRs.

### Layer 2 — Architecture and Operations

Includes architecture documentation, operational standards, workflow documentation, AGENTS.md and operational procedures.

### Layer 3 — Domain Knowledge

Includes Knowledge Base, brand profiles, language standards, official terminology and verified organizational information.

### Layer 4 — Working Artifacts

Working Artifacts never override Layers 1–3.

### Layer 5 — Published Outputs

Published Outputs represent approved work but do not replace governance or reference documentation.

**If a Published Output conflicts with an approved Source of Truth, the Published Output should be corrected rather than redefining the Source of Truth.**

---

## 5. Conflict Resolution

Higher governance layers always take precedence over lower layers.

If two documents within the same layer conflict, the newer approved version prevails unless explicitly stated otherwise.

If no authoritative source exists, the issue must be escalated to 00 – Architecture.

---

## 6. Repository Principle

The repository is the permanent home of project documentation.

Conversations are used to analyse, discuss, recommend and review.

A discussion alone does not permanently change the system.

Architectural decisions become effective only after they are recorded and approved in the repository.

---

## 7. General Rules

- every important rule should have one authoritative location;
- information should not be duplicated unnecessarily;
- documents should reference other documents instead of repeating them;
- temporary notes should not become permanent standards;
- facts must originate from approved sources;
- architecture must evolve through documented decisions;
- operational standards belong in repository documentation rather than Project Instructions.

---

## 8. Responsibilities

### 00 – Architecture

Responsible for governance, interpretation of this policy, resolving governance conflicts and approving architectural changes.

### Repository Documentation

Responsible for maintaining permanent project knowledge.

### Knowledge Base

Responsible for maintaining approved factual information and reusable domain knowledge.

### ChatGPT

Must use the appropriate Source of Truth, distinguish facts, assumptions, proposals and decisions, and never invent authoritative information.

---

## 9. Review

Review this policy whenever governance, repository structure, Project Instructions or the Source of Truth model changes.

Minor editorial updates do not require architectural review.

---

## Related Documents

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1

---

## Metadata

**Document:** Source of Truth Policy

**Version:** 1.0

**Status:** ACTIVE

**Owner:** 00 – Architecture

**Related:**

- Project Instructions v1.1
- ADR-001 — Adoption of Project Instructions v1.1