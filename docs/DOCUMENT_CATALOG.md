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

Guiding Principle

If a document is important enough to maintain, it is important enough to catalog.

If it is important enough to catalog, it is important enough to verify.