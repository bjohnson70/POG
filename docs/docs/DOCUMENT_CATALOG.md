# POG Document Catalog

**Document ID:** CAT-001
**Version:** 3.0
**Status:** Active
**Published:** 2026-08-02
**Last Updated:** 2026-08-05
**Last Repository Verification:** 2026-08-05

---

# Purpose

The Document Catalog is the authoritative inventory of every controlled document within the Property Operations Guide (POG).

It functions as the Configuration Management Database (CMDB) for the POG framework by recording document identity, lifecycle, verification status, dependencies, and repository location.

The Document Catalog serves as the single source of truth for repository governance.

---

# Objectives

The Document Catalog shall:

- Inventory every controlled document
- Track document lifecycle
- Verify repository integrity
- Support repository audits
- Support automation
- Identify missing documentation
- Record planned documentation
- Prevent duplicate documents
- Support future application development

---

# Repository Verification Summary

Repository:

```
bjohnson70/POG
```

Latest Verification:

```
2026-08-05
```

Verification confirmed:

- Repository structure verified
- Foundation documents verified
- Governance documents verified
- ADR documents verified
- Standards verified
- Template library verified
- Duplicate file identified and removed
- Missing Tenant Tour template added
- README synchronized
- Documentation Index synchronized
- Document Catalog synchronized

---

# Repository Statistics

| Metric | Count |
|---------|------:|
| Controlled Documents | 30 |
| Foundation Documents | 5 |
| ADR Documents | 2 |
| Backlog Documents | 2 |
| Standards | 10 |
| Templates | 10 |
| Planned Documents | 6 |
| Repository Support Files | 2 |
| Duplicate Documents | 0 |
| Missing Controlled Documents | 0 |

---

# Document Lifecycle

| Lifecycle | Meaning |
|------------|---------|
| Draft | Under development |
| Review | Awaiting approval |
| Active | Approved for general use |
| Accepted | Approved ADR |
| Adopted | Approved Standard |
| Template | Reusable template |
| Planned | Approved but not yet created |
| Deprecated | Scheduled for retirement |
| Archived | Historical reference |
| Retired | No longer maintained |

---

# Repository Health

| Indicator | Meaning |
|-----------|---------|
| 🟢 | Verified |
| 🟡 | Needs Review |
| 🔵 | Planned |
| 🔴 | Missing |
| ⚫ | Retired |

---

# Controlled Document Register

## Repository

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| README | Repository Overview | 2.0 | Active | 🟢 | 2026-08-05 |
| LICENSE | Apache License 2.0 | Current | Active | 🟢 | 2026-08-05 |

---

## Foundation

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| GOV-FOUND-001 | FOUNDATION.md | 1.0 | Active | 🟢 | 2026-08-05 |
| ARC-001 | ARCHITECTURE.md | 1.0 | Active | 🟢 | 2026-08-05 |
| GOV-001 | GOVERNANCE.md | 1.0 | Active | 🟢 | 2026-08-05 |
| POL-DATA-001 | DATA_CLASSIFICATION.md | 1.0 | Active | 🟢 | 2026-08-05 |
| CAT-INDEX-001 | INDEX.md | 2.0 | Active | 🟢 | 2026-08-05 |

---

## Governance

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| CAT-001 | DOCUMENT_CATALOG.md | 3.0 | Active | 🟢 | 2026-08-05 |

---

## Architecture Decision Records

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| ADR-README | ADR Framework | 1.0 | Active | 🟢 | 2026-08-05 |
| ADR-0001 | Public / Private Repository Architecture | 1.0 | Accepted | 🟢 | 2026-08-05 |

---

## Backlog

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| LOG-IDEA-001 | IDEA_LOG.md | 1.0 | Active | 🟢 | 2026-08-05 |
| LOG-DEC-001 | DECISION_LOG.md | 1.0 | Active | 🟢 | 2026-08-05 |