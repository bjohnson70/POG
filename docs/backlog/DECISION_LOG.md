# POG Decision Log

**Version:** 1.0  
**Status:** Active  
**Published:** 2026-08-02

---

# Purpose

The Decision Log records operational and project decisions that do not warrant a formal Architecture Decision Record (ADR).

It provides a concise historical record of important choices, allowing future contributors to understand how the project evolved.

---

# When to Use

Use the Decision Log when a decision:

- Does not significantly alter the architecture.
- Affects project organization or workflow.
- Establishes a naming convention.
- Approves or retires templates.
- Clarifies documentation practices.
- Resolves an implementation question.
- Records agreements reached during project discussions.

If the decision has long-term architectural consequences, create an ADR instead.

---

# Decision Lifecycle

Proposed

↓

Accepted

↓

Implemented

↓

Superseded (optional)

---

# Standard Entry Format

## Decision ID

DEC-YYYYMMDD-###

Example:

DEC-20260802-001

---

### Date

Date the decision was accepted.

---

### Status

- Accepted
- Implemented
- Superseded

---

### Summary

One-sentence description.

---

### Rationale

Why the decision was made.

---

### Related Documents

Optional references to:

- ADRs
- Standards
- Templates
- Ideas

---

# Decision Register

## DEC-20260802-001

**Date**

2026-08-02

**Status**

Accepted

**Summary**

Adopt the `(Idea)` convention across the POG framework.

**Rationale**

Ideas often occur during active work. Capturing them immediately preserves creativity without interrupting the current workflow.

Future implementations may reference the associated Idea ID.

---

## DEC-20260802-002

**Date**

2026-08-02

**Status**

Accepted

**Summary**

Separate reusable framework documentation from private operational records.

**Rationale**

The public repository should contain reusable knowledge, while property-specific and confidential information belongs in private repositories or secure storage.

(Architectural details are documented in ADR-0001.)

---

# Guiding Principle

Record decisions while they are fresh.

A short decision documented today is more valuable than a perfect explanation reconstructed months later.