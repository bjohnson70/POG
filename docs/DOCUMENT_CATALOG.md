POG Document Catalog

Document ID: CAT-001
Version: 2.1
Status: Active
Published: 2026-08-02
Last Verified: 2026-08-02 (PDT)

---

Purpose

The Document Catalog is the authoritative inventory of all controlled documents within the Property Operations Guide (POG).

It serves as the single source of truth for document existence, status, location, dependencies, and lifecycle management.

The catalog distinguishes between:

- Documents verified as present
- Documents requiring review or synchronization
- Documents planned but not yet created
- Documents archived or retired

---

Verification Summary

Repository verification was performed against the "main" branch of:

bjohnson70/POG

Verification confirmed:

- 17 controlled POG documents exist.
- The repository also contains "README.md" and "LICENSE".
- All proposed documents through the Property Lifecycle Standard have been created.
- The previous catalog did not include six completed standards.
- No reusable template documents have been created yet.
- "README.md", "INDEX.md", and this catalog are being synchronized following verification.

---

Document Status

Status| Description
Draft| Under development
Review| Awaiting approval
Active| Approved for use
Accepted| Formal decision approved
Adopted| Approved standard
Planned| Identified but not yet created
Archived| Retained for historical reference
Retired| No longer maintained

---

Document Health

Indicator| Meaning
🟢| Present and current
🟡| Present but needs review or synchronization
🔵| Planned but not created
🔴| Missing when expected
⚫| Retired

---

Controlled Document Register

ID| Document| Category| Version| Status| Health| Location| Depends On| Verification Notes
README| Project Overview| Overview| 1.1| Active| 🟢| "/README.md"| —| Updated following repository verification
FOUNDATION| POG Foundation| Foundation| 0.1| Active| 🟢| "/docs/FOUNDATION.md"| —| Present and verified
ARCHITECTURE| POG Architecture| Architecture| 1.0| Active| 🟢| "/docs/ARCHITECTURE.md"| FOUNDATION| Present and verified
GOVERNANCE| POG Governance| Governance| 1.0| Active| 🟢| "/docs/GOVERNANCE.md"| FOUNDATION| Present and verified
DATA_CLASSIFICATION| Data Classification Standard| Policy| 1.0| Active| 🟢| "/docs/DATA_CLASSIFICATION.md"| GOVERNANCE| Present and verified
INDEX| Documentation Index| Navigation| 1.1| Active| 🟢| "/docs/INDEX.md"| CAT-001| Updated following repository verification
CAT-001| Document Catalog| Governance| 2.1| Active| 🟢| "/docs/DOCUMENT_CATALOG.md"| GOVERNANCE| This document
ADR-README| ADR Framework| Architecture| 1.0| Active| 🟢| "/docs/adr/README.md"| GOVERNANCE| Present and verified
ADR-0001| Public and Private Repository Architecture| ADR| 1.0| Accepted| 🟢| "/docs/adr/ADR-0001-Public-Private-Repository-Architecture.md"| ADR-README, DATA_CLASSIFICATION| Present and verified
IDEA_LOG| POG Idea Log| Backlog| 1.0| Active| 🟢| "/docs/backlog/IDEA_LOG.md"| GOVERNANCE| Present and verified
DECISION_LOG| POG Decision Log| Backlog| 1.0| Active| 🟢| "/docs/backlog/DECISION_LOG.md"| GOVERNANCE| Present and verified
STD-DOC-001| Documentation Standard| Standard| 1.0| Adopted| 🟢| "/docs/standards/DOCUMENTATION_STANDARD.md"| GOVERNANCE| Present and verified
STD-NAME-001| Naming Standard| Standard| 1.0| Adopted| 🟢| "/docs/standards/NAMING_STANDARD.md"| STD-DOC-001| Present and verified
STD-PROP-001| Property Identification Standard| Standard| 1.0| Adopted| 🟢| "/docs/standards/PROPERTY_IDENTIFICATION_STANDARD.md"| STD-NAME-001| Present and verified
STD-MAINT-001| Maintenance Standard| Standard| 1.0| Adopted| 🟢| "/docs/standards/MAINTENANCE_STANDARD.md"| STD-PROP-001| Present and verified
STD-INSP-001| Inspection Standard| Standard| 1.0| Adopted| 🟢| "/docs/standards/INSPECTION_STANDARD.md"| STD-PROP-001, STD-MAINT-001| Present and verified
STD-VEND-001| Vendor Management Standard| Standard| 1.0| Adopted| 🟢| "/docs/standards/VENDOR_MANAGEMENT_STANDARD.md"| STD-PROP-001, STD-MAINT-001| Present and verified
STD-LIFE-001| Property Lifecycle Standard| Standard| 1.0| Adopted| 🟢| "/docs/standards/PROPERTY_LIFECYCLE_STANDARD.md"| STD-PROP-001, STD-INSP-001, STD-MAINT-001, STD-VEND-001| Present and verified

---

Repository Support File

The following file supports the repository but is not treated as a controlled POG framework document.

File| Status| Health| Location| Notes
Apache License 2.0| Active| 🟢| "/LICENSE"| Governs reuse and distribution of the public framework

---

Planned Documents — Not Yet Created

Governance and Project Management

Proposed ID| Document| Status| Health| Proposed Location
TBD| Roadmap| Planned| 🔵| "/docs/backlog/ROADMAP.md"
TBD| Release Notes| Planned| 🔵| "/docs/RELEASE_NOTES.md"
TBD| Change Log| Planned| 🔵| "/CHANGELOG.md"

---

Additional Standards

Proposed ID| Document| Status| Health| Proposed Location
STD-NUM-001| Document Numbering Standard| Planned| 🔵| "/docs/standards/DOCUMENT_NUMBERING_STANDARD.md"
STD-FILE-001| File Organization Standard| Planned| 🔵| "/docs/standards/FILE_ORGANIZATION_STANDARD.md"
TBD| Tenant Evaluation Standard| Planned| 🔵| "/docs/standards/TENANT_EVALUATION_STANDARD.md"

---

Reusable Templates

Proposed ID| Document| Status| Health| Proposed Location
TMP-PROP-001| Property Profile Template| Planned| 🔵| "/docs/templates/PROPERTY_PROFILE_TEMPLATE.md"
TMP-ANNUAL-001| Annual Property Review Template| Planned| 🔵| "/docs/templates/ANNUAL_PROPERTY_REVIEW_TEMPLATE.md"
TMP-INSP-001| Inspection Checklist Template| Planned| 🔵| "/docs/templates/INSPECTION_CHECKLIST_TEMPLATE.md"
TMP-MAINT-001| Maintenance Log Template| Planned| 🔵| "/docs/templates/MAINTENANCE_LOG_TEMPLATE.md"
TMP-VEND-001| Vendor Profile Template| Planned| 🔵| "/docs/templates/VENDOR_PROFILE_TEMPLATE.md"
TMP-VEND-002| Vendor Evaluation Template| Planned| 🔵| "/docs/templates/VENDOR_EVALUATION_TEMPLATE.md"
TMP-TEN-001| Tenant Tour Scorecard Template| Planned| 🔵| "/docs/templates/TENANT_TOUR_SCORECARD_TEMPLATE.md"
TMP-MOVE-001| Move-In Checklist Template| Planned| 🔵| "/docs/templates/MOVE_IN_CHECKLIST_TEMPLATE.md"
TMP-MOVE-002| Move-Out Checklist Template| Planned| 🔵| "/docs/templates/MOVE_OUT_CHECKLIST_TEMPLATE.md"
TMP-PRJ-001| Capital Improvement Project Template| Planned| 🔵| "/docs/templates/CAPITAL_IMPROVEMENT_PROJECT_TEMPLATE.md"

---

Private Operations Documents

Property-specific operational documents have intentionally not been created in the public repository.

Future private records may include:

- Property profiles containing actual property information
- Tenant and applicant records
- Maintenance histories
- Inspection reports
- Vendor contact records
- Work orders
- Improvement project records
- Financial and insurance references
- Property-specific photographs

These records must comply with the Data Classification Standard and ADR-0001.

---

Restricted Records

Restricted information shall not be stored in this public repository.

Examples include:

- Tenant applications
- Credit reports
- Government identification numbers
- Banking information
- Passwords and API keys
- Door, alarm, or access codes
- Wi-Fi credentials
- Signed confidential legal documents

Restricted information belongs in appropriately protected and encrypted storage.

---

Current Synchronization Status

The following repository synchronization work is complete:

- [x] Verify controlled files physically present in GitHub.
- [x] Identify completed standards missing from the catalog.
- [x] Prepare an updated root "README.md".
- [x] Prepare an updated "docs/INDEX.md".
- [x] Prepare an updated "docs/DOCUMENT_CATALOG.md".

The following work remains:

- [ ] Commit the three synchronized files.
- [ ] Verify the three committed files in GitHub.
- [ ] Assign controlled IDs to foundation documents if the numbering standard is adopted.
- [ ] Create the Document Numbering Standard.
- [ ] Create the File Organization Standard.
- [ ] Begin the reusable template phase.
- [ ] Establish the Private Operations Repository and Secure Vault model before creating real property records.

---

Catalog Maintenance Rules

Whenever a controlled document is:

- Created
- Revised
- Renamed
- Moved
- Archived
- Retired

The Document Catalog shall be updated during the same commit whenever practical.

A repository verification should compare:

1. Files physically present in GitHub
2. Files listed in the Controlled Document Register
3. Files identified as planned
4. Document IDs, versions, statuses, and locations
5. Navigation links in "INDEX.md" and "README.md"

---

“Verify Files” Procedure

When the instruction “Verify Files” is given, the POG repository should be reviewed to confirm:

1. Expected files exist in GitHub.
2. File contents reflect the approved versions.
3. Document headers contain the expected ID, version, and status.
4. Created files are listed in the Controlled Document Register.
5. Uncreated files remain listed as Planned.
6. "README.md" and "INDEX.md" provide accurate navigation.
7. Public files do not contain Private or Restricted information.
8. Any discrepancies are documented and corrected.

---

Quality Review Checklist

Before publishing any controlled document, verify:

- [ ] The document does not already exist.
- [ ] The correct directory is selected.
- [ ] The Documentation Standard is followed.
- [ ] A permanent Document ID is assigned when applicable.
- [ ] The version is assigned or updated.
- [ ] The status is assigned.
- [ ] Cross-references are included.
- [ ] The document is added to "INDEX.md".
- [ ] The document is added to "DOCUMENT_CATALOG.md".
- [ ] Public, Private, or Restricted classification is confirmed.
- [ ] The need for an ADR is evaluated.
- [ ] No personally identifiable, confidential, or security-sensitive information is exposed.

---

---

# Standards

## Documentation and Repository Standards

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| STD-DOC-001 | Documentation Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-NAME-001 | Naming Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-NUM-001 | Document Numbering Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-FILE-001 | File Organization Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |

---

## Property Operations Standards

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| STD-PROP-001 | Property Identification Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-MAINT-001 | Maintenance Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-INSP-001 | Inspection Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-VEND-001 | Vendor Management Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-LIFE-001 | Property Lifecycle Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |
| STD-PHOTO-001 | Photo Documentation Standard | 1.0 | Adopted | 🟢 | 2026-08-05 |

---

# Template Library

Templates are reusable documents intended to be copied into the future Private Operations Repository.

The public repository shall contain only blank templates or fictional examples.

Completed operational records belong in the Private Operations Repository.

---

## Property Management Templates

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| TMP-PROP-001 | Property Profile Template | 1.0 | Template | 🟢 | 2026-08-05 |
| TMP-ANNUAL-001 | Annual Property Review Template | 1.0 | Template | 🟢 | 2026-08-05 |
| TMP-INSP-001 | Inspection Checklist Template | 1.0 | Template | 🟢 | 2026-08-05 |
| TMP-MAINT-001 | Maintenance Log Template | 1.0 | Template | 🟢 | 2026-08-05 |
| TMP-PRJ-001 | Capital Improvement Project Template | 1.0 | Template | 🟢 | 2026-08-05 |

---

## Vendor Management Templates

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| TMP-VEND-001 | Vendor Profile Template | 1.0 | Template | 🟢 | 2026-08-05 |
| TMP-VEND-002 | Vendor Evaluation Template | 1.0 | Template | 🟢 | 2026-08-05 |

---

## Rental Operations Templates

| ID | Document | Version | Lifecycle | Health | Verified |
|----|----------|---------|-----------|--------|-----------|
| TMP-TEN-001 | Tenant Tour Scorecard Template | 1.0 | Template | 🟢 | 2026-08-05 |
| TMP-MOVE-001 | Move-In Checklist Template | 1.0 | Template | 🟢 | 2026-08-05 |
| TMP-MOVE-002 | Move-Out Checklist Template | 1.0 | Template | 🟢 | 2026-08-05 |

---

# Planned Documents

## Governance

| Proposed ID | Document | Lifecycle |
|--------------|----------|-----------|
| TBD | Roadmap | Planned |
| TBD | Release Notes | Planned |
| TBD | Change Log | Planned |

---

## Future Standards

| Proposed ID | Document | Lifecycle |
|--------------|----------|-----------|
| STD-TEN-001 | Tenant Evaluation Standard | Planned |
| STD-RET-001 | Records Retention Standard | Planned |
| STD-PRIV-001 | Private Repository Standard | Planned |
| STD-VAULT-001 | Secure Vault Standard | Planned |

---

## Future Examples

The following example documents are planned:

- Property Profile Example
- Annual Property Review Example
- Inspection Checklist Example
- Maintenance Log Example
- Vendor Profile Example
- Vendor Evaluation Example
- Tenant Tour Example
- Move-In Example
- Move-Out Example
- Capital Improvement Example

All example documents shall contain fictional data only.

---

# Private Operations Repository

The following completed operational records belong in the future Private Operations Repository:

- Completed Property Profiles
- Annual Property Reviews
- Inspection Reports
- Maintenance Logs
- Vendor Records
- Vendor Evaluations
- Capital Improvement Projects
- Tenant Tour Records
- Move-In Records
- Move-Out Records
- Property Photographs
- Financial Records
- Insurance Information
- Warranty Records

---

# Repository Verification Procedure

The command **"Verify Files"** performs a complete validation of the POG repository.

Verification shall confirm:

1. Expected files exist.
2. No unexpected duplicate files exist.
3. File names comply with the Naming Standard.
4. Document headers contain the correct:
   - Document ID
   - Version
   - Status
5. Every controlled document appears in this catalog.
6. Every controlled document appears in the Documentation Index.
7. Cross-references remain valid.
8. Public documents contain no Private or Restricted information.
9. Repository statistics remain accurate.

Any discrepancies shall be documented and corrected before the repository is considered synchronized.

---

# Verification History

| Date | Catalog Version | Verified By | Notes |
|------|----------------:|-------------|-------|
| 2026-08-02 | 2.0 | ChatGPT | Initial repository verification |
| 2026-08-05 | 3.0 | ChatGPT | Repository synchronized following completion of the Version 1.0 framework, template library, and governance updates |

---

# Repository Maintenance Rules

Whenever a controlled document is:

- Created
- Revised
- Renamed
- Moved
- Archived
- Deprecated
- Retired

the following documents shall be reviewed and updated as necessary:

- README.md
- INDEX.md
- DOCUMENT_CATALOG.md

Repository verification should be performed after significant repository changes.

---

# Version Control Rules

Each controlled document shall contain:

- Document ID
- Version
- Status
- Published Date
- Revision History

Document IDs remain permanent.

Version numbers change as the document evolves.

Filenames may change if needed, but Document IDs shall remain unchanged unless the document is formally replaced.

---

# Quality Assurance Checklist

Before publishing a controlled document, verify:

- [ ] Correct repository location
- [ ] Correct filename
- [ ] Correct Document ID
- [ ] Version updated
- [ ] Status updated
- [ ] Revision history updated
- [ ] Related documents listed
- [ ] Included in INDEX.md
- [ ] Included in DOCUMENT_CATALOG.md
- [ ] Naming Standard followed
- [ ] Documentation Standard followed
- [ ] Public/Private classification verified
- [ ] No sensitive information included

---

# Future Enhancements

The following enhancements have been identified for future development:

- Private Operations Repository
- Secure Vault architecture
- Fictional example library
- Mobile application
- Voice dictation for property logs
- AI-assisted maintenance recommendations
- Property Health Score
- Visual Property History timeline
- Vendor Performance Score
- Operational dashboards and analytics
- Automated recurring maintenance scheduling
- Search and reporting capabilities

Future enhancements shall be evaluated through the Architecture Decision Record (ADR) process when they introduce significant architectural or governance changes.

---

# Configuration Management Philosophy

The Document Catalog serves as the Configuration Management Database (CMDB) for the POG framework.

Its purpose is to answer four questions:

1. What documents exist?
2. Where are they located?
3. What is their current status?
4. When were they last verified?

Maintaining this catalog ensures the repository remains organized, trustworthy, and ready for long-term growth.

---

# Guiding Principle

If a document is important enough to maintain, it is important enough to catalog.

If it is important enough to catalog, it is important enough to verify.

If it is important enough to verify, it is important enough to protect.

Guiding Principle

If a document is important enough to maintain, it is important enough to catalog.

If it is important enough to catalog, it is important enough to verify.