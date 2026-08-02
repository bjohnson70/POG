# POG Document Catalog

**Document ID:** CAT-001  
**Version:** 2.0  
**Status:** Active  
**Published:** 2026-08-02

---

# Purpose

The Document Catalog is the authoritative inventory of all controlled documents within the Property Operations Guide (POG).

It serves as the single source of truth for document existence, ownership, status, dependencies, and lifecycle management.

The Document Catalog should be reviewed whenever new documents are created, revised, archived, or retired.

---

# Document Status

| Status | Description |
|---------|-------------|
| Draft | Under development |
| Review | Awaiting approval |
| Active | Approved for use |
| Archived | Historical reference |
| Retired | No longer maintained |

---

# Document Health

| Indicator | Meaning |
|-----------|---------|
| 🟢 | Current |
| 🟡 | Needs Review |
| 🔴 | Outdated |
| ⚫ | Retired |

---

# Controlled Document Register

| ID | Document | Category | Version | Status | Health | Location | Depends On | Notes |
|----|----------|----------|---------|--------|--------|----------|------------|-------|
| README | Project Overview | Overview | 1.0 | Active | 🟢 | / | — | Repository home page |
| CAT-001 | Document Catalog | Governance | 2.0 | Active | 🟢 | /docs | — | This document |
| FOUNDATION | Foundation | Foundation | 0.1 | Active | 🟢 | /docs | — | |
| ARCHITECTURE | Architecture | Architecture | 1.0 | Active | 🟢 | /docs | FOUNDATION | |
| GOVERNANCE | Governance | Governance | 1.0 | Active | 🟢 | /docs | FOUNDATION | |
| DATA_CLASSIFICATION | Policy | Policy | 1.0 | Active | 🟢 | /docs | GOVERNANCE | |
| INDEX | Documentation Index | Navigation | 1.0 | Active | 🟢 | /docs | — | |
| STD-DOC-001 | Documentation Standard | Standard | 1.0 | Active | 🟢 | /docs/standards | GOVERNANCE | |
| ADR-README | ADR Framework | Architecture | 1.0 | Active | 🟢 | /docs/adr | GOVERNANCE | |
| ADR-0001 | Public/Private Repository Architecture | ADR | 1.0 | Active | 🟢 | /docs/adr | ADR-README | |
| IDEA_LOG | Idea Log | Backlog | 1.0 | Active | 🟢 | /docs/backlog | GOVERNANCE | |
| DECISION_LOG | Decision Log | Backlog | 1.0 | Active | 🟢 | /docs/backlog | GOVERNANCE | |

---

# Planned Documents

## Governance

- Roadmap
- Release Notes
- Change Log

## Standards

- Naming Standard
- Property Identification Standard
- Inspection Standard
- Maintenance Standard
- Vendor Management Standard
- Documentation Numbering Standard
- File Organization Standard

## Templates

- Property Profile
- Vendor Profile
- Maintenance Log
- Inspection Checklist
- Tenant Tour Scorecard
- Move-In Checklist
- Move-Out Checklist
- Annual Property Review

## Operations

(To be maintained in the future Private POG Repository.)

---

# Catalog Maintenance Rules

Whenever a controlled document is:

- Created
- Revised
- Renamed
- Moved
- Archived
- Retired

…the Document Catalog shall be updated during the same commit whenever practical.

---

# Quality Review Checklist

Before publishing any controlled document verify:

- ☐ Document does not already exist.
- ☐ Correct directory selected.
- ☐ Documentation Standard followed.
- ☐ Version assigned.
- ☐ Status assigned.
- ☐ Cross references added.
- ☐ Added to INDEX.md.
- ☐ Added to DOCUMENT_CATALOG.md.
- ☐ Public/Private classification verified.
- ☐ ADR required? (If applicable)

---

# Guiding Principle

If a document is important enough to maintain, it is important enough to catalog.

If it is important enough to catalog, it is important enough to govern.