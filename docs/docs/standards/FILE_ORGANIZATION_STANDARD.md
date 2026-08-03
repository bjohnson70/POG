# File Organization Standard

**Document ID:** STD-FILE-001
**Version:** 1.0
**Status:** Adopted
**Published:** 2026-08-03

---

# Purpose

This standard defines how files and directories are organized within the Property Operations Guide (POG).

A consistent directory structure improves discoverability, simplifies automation, supports future application development, and keeps the public and private repositories organized as they grow.

---

# Objectives

The file organization should be:

- Predictable
- Consistent
- Scalable
- Easy to navigate
- Friendly to both people and software

---

# Repository Philosophy

POG separates information into logical groups rather than by date.

Documents should be stored according to **purpose**, not author or chronology.

---

# Public Repository Structure

```
/
│
├── README.md
├── LICENSE
├── CHANGELOG.md                (Future)
│
└── docs/
    │
    ├── INDEX.md
    ├── DOCUMENT_CATALOG.md
    ├── FOUNDATION.md
    ├── ARCHITECTURE.md
    ├── GOVERNANCE.md
    ├── DATA_CLASSIFICATION.md
    │
    ├── adr/
    │
    ├── backlog/
    │
    ├── standards/
    │
    ├── templates/
    │
    ├── reference/
    │
    └── examples/
```

---

# Directory Definitions

## adr/

Architecture Decision Records.

Examples:

- ADR-0001
- ADR-0002

---

## backlog/

Living planning documents.

Examples:

- Idea Log
- Decision Log
- Roadmap

---

## standards/

Rules governing how POG operates.

Examples:

- Maintenance Standard
- Inspection Standard
- Vendor Management Standard

---

## templates/

Reusable operational templates.

Examples:

- Property Profile
- Inspection Checklist
- Maintenance Log
- Vendor Evaluation

Templates must never contain real customer or property information.

---

## reference/

Supporting documentation that explains concepts but is not itself a governing document.

Examples:

- Research
- Industry references
- External standards
- Best practices

---

## examples/

Illustrative sample documents using fictional data.

Examples:

- Sample inspection
- Sample maintenance history
- Sample vendor evaluation

No real property or tenant information should appear in examples.

---

# Private Repository Structure

The future Private Operations Repository should mirror the public repository where practical.

Suggested layout:

```
properties/
    POG-SD-001/
    POG-EG-001/

vendors/

projects/

maintenance/

inspections/

financial/

photographs/

tenants/

applications/
```

---

# Property Organization

Each property should have a dedicated directory.

Example:

```
POG-SD-001/

    inspections/

    maintenance/

    vendors/

    projects/

    inventory/

    photographs/
```

Property records should never be mixed together.

---

# Archive Strategy

Archived documents should remain readable.

Preferred structure:

```
archive/

    2026/

    2027/
```

Archived records should not be deleted unless required by law or retention policy.

---

# File Naming

All filenames shall comply with the Naming Standard.

Examples:

```
MAINTENANCE_STANDARD.md

PROPERTY_PROFILE_TEMPLATE.md

VENDOR_EVALUATION_TEMPLATE.md
```

---

# Cross References

Documents should reference:

- Document IDs
- Related Standards
- ADRs
- Templates

Avoid referencing file paths when a Document ID is sufficient.

---

# Future Automation

The directory structure is intentionally designed to support future:

- Mobile applications
- AI assistants
- Document generation
- Workflow automation
- Search indexing
- Version synchronization

---

# Related Documents

- Documentation Standard
- Naming Standard
- Document Numbering Standard
- Document Catalog

---

# Guiding Principle

A person unfamiliar with the repository should be able to locate any document within a few minutes without prior knowledge of the project.

Good organization reduces effort, improves consistency, and enables long-term growth.