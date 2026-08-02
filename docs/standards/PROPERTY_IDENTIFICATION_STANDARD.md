# Property Identification Standard

**Document ID:** STD-PROP-001
**Version:** 1.0
**Status:** Adopted
**Published:** 2026-08-02

---

# Purpose

This standard establishes how properties are uniquely identified within the Property Operations Guide (POG).

A Property ID serves as the primary reference for documentation, maintenance history, inspections, vendors, projects, photographs, financial records, and future automation.

Property IDs are permanent and never reassigned.

---

# Objectives

Property identifiers should be:

- Unique
- Human readable
- Permanent
- Location independent
- Scalable

---

# Property Identifier Format

```
POG-<LOCATION>-###
```

Examples:

```
POG-SD-001
POG-EG-001
POG-DEN-001
POG-PDX-001
```

Where:

- **POG** identifies the framework.
- **LOCATION** is a short geographic abbreviation.
- **###** is a sequential identifier.

---

# Location Codes

Examples:

| Code | Location |
|------|----------|
| SD | San Diego |
| EG | Elk Grove |
| SAC | Sacramento |
| DEN | Denver |
| PDX | Portland |
| PHX | Phoenix |

Additional codes may be added as needed.

---

# Naming Principles

A Property ID:

- Never changes due to ownership changes.
- Never changes due to tenant changes.
- Never changes because of renovations.
- Never gets reused after retirement.

---

# Property Metadata

Each property should maintain the following metadata:

- Property ID
- Property Name (optional)
- Property Type
- General Location
- Status
- Date Added
- Date Retired (if applicable)

---

# Property Status

Examples:

- Planned
- Active
- Seasonal
- Vacant
- Rented
- Under Renovation
- Retired
- Sold

---

# Relationship to Other Records

Every operational record should reference its associated Property ID.

Examples include:

- Maintenance Logs
- Inspection Reports
- Vendor Records
- Improvement Projects
- Equipment Inventory
- Annual Reviews
- Photographs
- Tenant Records (Private Repository)

---

# Directory Structure Example

```
POG-SD-001/
    inspections/
    maintenance/
    vendors/
    projects/
    inventory/
```

This structure is intended for the future Private Operations Repository.

---

# Examples

Public documentation:

```
Inspection Checklist Template
```

Private documentation:

```
POG-SD-001
2026 Annual Inspection
Vendor Record VEN-004
```

---

# Guiding Principle

Every property should have exactly one permanent identifier.

Everything else references the property.

Nothing references an address.