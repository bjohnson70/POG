POG Documentation Index

Document ID: CAT-INDEX-001
Version: 2.0
Status: Active
Published: 2026-08-02
Last Updated: 2026-08-05

---

Purpose

This index is the primary navigation document for the Property Operations Guide (POG).

It provides direct access to the framework’s foundation, governance, architecture, standards, backlog, and reusable templates.

For the authoritative inventory of created, planned, archived, and retired documents, refer to the "Document Catalog" (DOCUMENT_CATALOG.md).

---

Repository Overview

Document| Purpose
"README.md" (../README.md)| Repository overview and primary entry point
"LICENSE" (../LICENSE)| Apache License 2.0
"DOCUMENT_CATALOG.md" (DOCUMENT_CATALOG.md)| Authoritative document inventory and verification register

---

Foundation and Governance

ID| Document| Purpose| Status
GOV-FOUND-001| "FOUNDATION.md" (FOUNDATION.md)| Defines the core purpose and principles of POG| Active
ARC-001| "ARCHITECTURE.md" (ARCHITECTURE.md)| Defines the overall framework architecture| Active
GOV-001| "GOVERNANCE.md" (GOVERNANCE.md)| Defines governance, change management, and versioning| Active
POL-DATA-001| "DATA_CLASSIFICATION.md" (DATA_CLASSIFICATION.md)| Defines Public, Private, and Restricted information| Active
CAT-001| "DOCUMENT_CATALOG.md" (DOCUMENT_CATALOG.md)| Tracks existing, planned, archived, and retired documents| Active

---

Architecture Decision Records

ID| Document| Purpose| Status
ADR-README| "adr/README.md" (adr/README.md)| Defines the ADR process and lifecycle| Active
ADR-0001| "Public and Private Repository Architecture" (adr/ADR-0001-Public-Private-Repository-Architecture.md)| Establishes the public, private, and secure repository architecture| Accepted

---

Backlog and Continuous Improvement

ID| Document| Purpose| Status
LOG-IDEA-001| "backlog/IDEA_LOG.md" (backlog/IDEA_LOG.md)| Captures ideas without interrupting active work| Active
LOG-DEC-001| "backlog/DECISION_LOG.md" (backlog/DECISION_LOG.md)| Records decisions that do not require a full ADR| Active
TBD| "backlog/ROADMAP.md"| Future development roadmap| Planned

---

Standards

Documentation and Repository Standards

ID| Document| Purpose| Status
STD-DOC-001| "Documentation Standard" (standards/DOCUMENTATION_STANDARD.md)| Defines document structure, formatting, quality, and versioning| Adopted
STD-NAME-001| "Naming Standard" (standards/NAMING_STANDARD.md)| Defines naming conventions for files, folders, and identifiers| Adopted
STD-NUM-001| "Document Numbering Standard" (standards/DOCUMENT_NUMBERING_STANDARD.md)| Defines permanent controlled document identifiers| Adopted
STD-FILE-001| "File Organization Standard" (standards/FILE_ORGANIZATION_STANDARD.md)| Defines repository and directory organization| Adopted

Property Operations Standards

ID| Document| Purpose| Status
STD-PROP-001| "Property Identification Standard" (standards/PROPERTY_IDENTIFICATION_STANDARD.md)| Defines permanent property identifiers| Adopted
STD-MAINT-001| "Maintenance Standard" (standards/MAINTENANCE_STANDARD.md)| Defines preventive, corrective, predictive, and emergency maintenance| Adopted
STD-INSP-001| "Inspection Standard" (standards/INSPECTION_STANDARD.md)| Defines consistent property inspection practices| Adopted
STD-VEND-001| "Vendor Management Standard" (standards/VENDOR_MANAGEMENT_STANDARD.md)| Defines vendor selection, documentation, and evaluation| Adopted
STD-LIFE-001| "Property Lifecycle Standard" (standards/PROPERTY_LIFECYCLE_STANDARD.md)| Defines property lifecycle phases and related operations| Adopted
STD-PHOTO-001| "Photo Documentation Standard" (standards/PHOTO_DOCUMENTATION_STANDARD.md)| Defines consistent property photo capture, naming, and retention| Adopted

---

Reusable Templates

Completed templates must contain placeholders or fictional data only.

Completed records containing real property, tenant, vendor, financial, or security information belong in the future Private Operations Repository.

Property Management Templates

ID| Document| Purpose| Status
TMP-PROP-001| "Property Profile Template" (templates/PROPERTY_PROFILE_TEMPLATE.md)| Creates the master property record| Template
TMP-ANNUAL-001| "Annual Property Review Template" (templates/ANNUAL_PROPERTY_REVIEW_TEMPLATE.md)| Summarizes annual property condition and priorities| Template
TMP-INSP-001| "Inspection Checklist Template" (templates/INSPECTION_CHECKLIST_TEMPLATE.md)| Standardizes property inspections| Template
TMP-MAINT-001| "Maintenance Log Template" (templates/MAINTENANCE_LOG_TEMPLATE.md)| Records maintenance history and costs| Template
TMP-PRJ-001| "Capital Improvement Project Template" (templates/CAPITAL_IMPROVEMENT_PROJECT_TEMPLATE.md)| Plans and documents major property improvements| Template

Vendor Management Templates

ID| Document| Purpose| Status
TMP-VEND-001| "Vendor Profile Template" (templates/VENDOR_PROFILE_TEMPLATE.md)| Records vendor identity, services, licensing, and availability| Template
TMP-VEND-002| "Vendor Evaluation Template" (templates/VENDOR_EVALUATION_TEMPLATE.md)| Evaluates vendor performance on completed work| Template

Rental Operations Templates

ID| Document| Purpose| Status
TMP-TEN-001| "Tenant Tour Scorecard Template" (templates/TENANT_TOUR_SCORECARD_TEMPLATE.md)| Documents objective observations from prospective tenant tours| Template
TMP-MOVE-001| "Move-In Checklist Template" (templates/MOVE_IN_CHECKLIST_TEMPLATE.md)| Documents readiness and condition at occupancy start| Template
TMP-MOVE-002| "Move-Out Checklist Template" (templates/MOVE_OUT_CHECKLIST_TEMPLATE.md)| Documents condition and turnover needs at occupancy end| Template

---

Planned Documents

Governance and Project Management

Proposed ID| Document| Status
TBD| Roadmap| Planned
TBD| Release Notes| Planned
TBD| Change Log| Planned

Additional Standards

Proposed ID| Document| Status
STD-TEN-001| Tenant Evaluation Standard| Planned
TBD| Records Retention Standard| Planned
TBD| Private Repository Standard| Planned
TBD| Secure Vault Standard| Planned

Examples

Fictional examples may be created to demonstrate proper use of templates.

Examples must not contain real property, tenant, applicant, vendor, financial, or security information.

---

Private Operations

Property-specific operational records belong in a future private repository.

Examples include:

- Completed property profiles
- Maintenance histories
- Inspection reports
- Vendor contact records
- Tenant and applicant records
- Improvement projects
- Work orders
- Property photographs
- Financial and insurance references

Private records should use neutral identifiers whenever practical.

---

Restricted Records

Highly sensitive information must not be stored in this public repository.

Examples include:

- Tenant applications
- Credit reports
- Banking information
- Government identification numbers
- Passwords and API keys
- Alarm or door codes
- Wi-Fi credentials
- Signed confidential legal documents

Restricted records should remain in encrypted or otherwise protected storage.

---

Repository Philosophy

The public POG repository documents how properties should be operated.

The future private repository will document how specific properties are operated.

The Secure Vault will protect information that should not be stored in either repository.

---

Repository Verification

The instruction “Verify Files” directs a repository review to confirm:

1. Expected files exist in GitHub.
2. File contents match approved versions.
3. Document headers contain the correct ID, version, and status.
4. Created files are listed in this index and in the Document Catalog.
5. Planned but uncreated files remain identified as Planned.
6. Duplicate, stale, or incorrectly named files are identified.
7. Public files contain no Private or Restricted information.
8. Required governance documents are updated.

---

Continuous Improvement

POG is intended to evolve through:

- Ideas
- Decisions
- Architecture Decision Records
- Standards
- Templates
- Periodic repository verification

Every useful idea should be captured.

Not every idea requires immediate implementation.