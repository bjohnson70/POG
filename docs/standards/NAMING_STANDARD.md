# POG Naming Standard

**Document ID:** STD-NAME-001
**Version:** 1.0
**Status:** Adopted
**Published:** 2026-08-02

---

# Purpose

This standard establishes naming conventions for documents, folders, templates, identifiers, and operational records throughout the Property Operations Guide (POG).

Consistent naming improves readability, discoverability, automation, and long-term maintainability.

---

# Objectives

POG naming should be:

- Predictable
- Consistent
- Searchable
- Human readable
- Automation friendly

---

# General Rules

Use:

- UPPERCASE for controlled document filenames.
- Underscores (_) between words.
- No spaces.
- No special characters.
- Markdown (.md) for documentation.

Examples:

```
DOCUMENT_CATALOG.md
PROPERTY_PROFILE_TEMPLATE.md
INSPECTION_STANDARD.md
```

---

# Folder Names

Folders should be lowercase.

Examples:

```
docs/
standards/
templates/
adr/
operations/
backlog/
reference/
```

---

# Controlled Document IDs

Controlled documents receive permanent identifiers.

Examples:

```
CAT-001
STD-DOC-001
STD-NAME-001
ADR-0001
TMP-001
POL-001
ARC-001
GOV-001
```

Document IDs never change, even if filenames do.

---

# Template Naming

Templates should end with:

```
_TEMPLATE.md
```

Examples:

```
PROPERTY_PROFILE_TEMPLATE.md
VENDOR_PROFILE_TEMPLATE.md
TENANT_SCORECARD_TEMPLATE.md
```

---

# Standard Naming

Standards should end with:

```
_STANDARD.md
```

Examples:

```
NAMING_STANDARD.md
DOCUMENTATION_STANDARD.md
MAINTENANCE_STANDARD.md
```

---

# Property Identifiers

Each managed property should receive a permanent identifier.

Example:

```
POG-SD-001
POG-EG-001
POG-DEN-001
```

Identifiers should never be reused.

---

# Vendor Identifiers

Example:

```
VEN-0001
VEN-0002
```

---

# Tenant Identifiers

Example:

```
TEN-2026-001
TEN-2026-002
```

---

# Applicant Identifiers

Example:

```
APP-2026-001
```

---

# Project Identifiers

Example:

```
PRJ-2026-004
```

---

# Idea Identifiers

Ideas follow the established convention:

```
IDEA-YYYYMMDD-###
```

Example:

```
IDEA-20260802-001
```

---

# Decision Identifiers

```
DEC-YYYYMMDD-###
```

---

# ADR Identifiers

Sequential numbering.

```
ADR-0001
ADR-0002
ADR-0003
```

---

# Version Numbers

Semantic versioning is used.

Examples:

```
1.0
1.1
1.2
2.0
```

---

# Guiding Principle

Names should describe **what something is**, not **where it currently lives**.

Good names survive reorganizations.