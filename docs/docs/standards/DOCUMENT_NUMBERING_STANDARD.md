POG Document Numbering Standard

Document ID: STD-NUM-001
Version: 1.0
Status: Adopted
Published: 2026-08-02

---

Purpose

This standard establishes the permanent document identification system used throughout the Property Operations Guide (POG).

Document IDs make files easier to reference, catalog, govern, automate, and maintain as the framework grows.

A document ID identifies the document independently from its filename or storage location.

---

Objectives

The POG document numbering system should be:

- Unique
- Permanent
- Predictable
- Human readable
- Easy to reference
- Scalable
- Suitable for automation

---

General Format

Controlled document IDs use the following structure:

<CATEGORY>-<SUBCATEGORY>-###

or, when no subcategory is necessary:

<CATEGORY>-###

Examples:

STD-DOC-001
STD-NAME-001
STD-MAINT-001
ADR-0001
CAT-001
TMP-INSP-001

---

Numbering Principles

Document IDs:

- Are assigned when a controlled document is created.
- Remain permanent for the life of the document.
- Do not change when a file is renamed.
- Do not change when a file is moved.
- Are never reused after a document is retired.
- Should be listed in the Document Catalog.
- Should appear near the top of the document.

---

Category Codes

Code| Category| Example
ARC| Architecture| ARC-001
ADR| Architecture Decision Record| ADR-0001
CAT| Catalog| CAT-001
GOV| Governance| GOV-001
POL| Policy| POL-DATA-001
STD| Standard| STD-MAINT-001
TMP| Template| TMP-INSP-001
LOG| Log or Register| LOG-IDEA-001
PLN| Plan or Roadmap| PLN-ROAD-001
REF| Reference| REF-VEND-001
PROC| Procedure| PROC-INSP-001
FORM| Operational Form| FORM-MOVE-001

Additional category codes may be created when necessary.

New codes should be documented in this standard before broad use.

---

Standard Subcategory Codes

Standards use short subject identifiers.

Code| Subject
DOC| Documentation
NUM| Document Numbering
NAME| Naming
FILE| File Organization
PROP| Property Identification
MAINT| Maintenance
INSP| Inspection
VEND| Vendor Management
LIFE| Property Lifecycle
TEN| Tenant Evaluation
DATA| Data Classification
SEC| Security
PRIV| Privacy
FIN| Financial Operations
INV| Inventory
PRJ| Projects
MOVE| Move-In and Move-Out
PHOTO| Photograph Management

Examples:

STD-DOC-001
STD-NUM-001
STD-PROP-001
STD-MAINT-001
STD-INSP-001

---

Template Subcategory Codes

Templates should use a subject code that identifies their operational purpose.

Examples:

TMP-PROP-001
TMP-ANNUAL-001
TMP-INSP-001
TMP-MAINT-001
TMP-VEND-001
TMP-TEN-001
TMP-MOVE-001
TMP-PRJ-001

Where multiple templates exist in the same category, the numeric sequence increases.

Example:

TMP-VEND-001 — Vendor Profile Template
TMP-VEND-002 — Vendor Evaluation Template

---

Architecture Decision Records

Architecture Decision Records use a single sequential series:

ADR-0001
ADR-0002
ADR-0003

ADR numbers are assigned sequentially and never reused.

Four digits are used to support long-term growth.

---

Logs and Registers

Logs may use either a controlled document ID or transaction-style entry IDs.

Controlled Log Document

Example:

LOG-IDEA-001
LOG-DEC-001

Individual Idea Entry

IDEA-YYYYMMDD-###

Example:

IDEA-20260802-001

Individual Decision Entry

DEC-YYYYMMDD-###

Example:

DEC-20260802-001

The log document and the entries within it use different identifiers.

---

Existing POG Documents

The following existing documents use established identifiers:

Document| ID
Document Catalog| CAT-001
Documentation Standard| STD-DOC-001
Naming Standard| STD-NAME-001
Document Numbering Standard| STD-NUM-001
Property Identification Standard| STD-PROP-001
Maintenance Standard| STD-MAINT-001
Inspection Standard| STD-INSP-001
Vendor Management Standard| STD-VEND-001
Property Lifecycle Standard| STD-LIFE-001
Public and Private Repository Architecture| ADR-0001

---

Foundation Document IDs

The initial foundation documents were created before the formal numbering standard.

The following IDs are reserved for future adoption:

Document| Reserved ID
POG Foundation| GOV-FOUND-001
POG Architecture| ARC-001
POG Governance| GOV-001
Data Classification Standard| POL-DATA-001
Documentation Index| CAT-INDEX-001
Idea Log| LOG-IDEA-001
Decision Log| LOG-DEC-001

Assigning these reserved IDs requires updating:

- The document header
- The Document Catalog
- The Documentation Index
- Any related cross-references

The filenames do not need to change solely because an ID is assigned.

---

Sequential Numbering

Numbers are assigned sequentially within each category and subcategory.

Examples:

TMP-VEND-001
TMP-VEND-002
TMP-VEND-003

A missing number should not normally be reused.

If a planned document is cancelled after an ID is reserved, the identifier should be marked as:

Reserved — Not Used

This preserves the historical sequence.

---

Version Numbers and Document IDs

A document ID and version number serve different purposes.

Example:

Document ID: STD-MAINT-001
Version: 1.2

The document ID identifies the controlled document.

The version identifies the current revision.

Updating a document does not create a new document ID unless the original document is retired and replaced by a substantively different document.

---

Superseded Documents

When one document replaces another:

- The original ID remains associated with the retired document.
- The replacement receives a new ID when it is a new controlled document.
- The Document Catalog records the relationship.
- The retired document identifies the document that superseded it.

Example:

STD-MAINT-001 — Retired
Superseded by: STD-MAINT-002

Minor and major revisions of the same standard normally retain the original ID.

---

File Naming Relationship

Document IDs do not need to appear in filenames.

Preferred:

MAINTENANCE_STANDARD.md

Document header:

Document ID: STD-MAINT-001

This preserves readable filenames while allowing permanent document identification.

An ID may be included in a filename when useful, especially for sequential records such as ADRs.

Example:

ADR-0001-Public-Private-Repository-Architecture.md

---

Assignment Procedure

Before assigning a document ID:

1. Confirm that the document does not already exist.
2. Identify the correct document category.
3. Select the correct subject code.
4. Review the Document Catalog for the next available number.
5. Reserve the identifier.
6. Add the identifier to the document header.
7. Add the document to the Document Catalog.
8. Add the document to the Documentation Index when appropriate.
9. Verify that the identifier is unique.

---

Quality Checks

Before publishing a numbered document, verify:

- [ ] The category code is correct.
- [ ] The subcategory code is correct.
- [ ] The number is unique.
- [ ] The number has not been reused.
- [ ] The ID appears in the document header.
- [ ] The ID appears in the Document Catalog.
- [ ] The filename follows the Naming Standard.
- [ ] Cross-references use the correct ID.
- [ ] The version number is separate from the document ID.

---

Related Documents

- "docs/standards/DOCUMENTATION_STANDARD.md"
- "docs/standards/NAMING_STANDARD.md"
- "docs/DOCUMENT_CATALOG.md"
- "docs/INDEX.md"
- "docs/GOVERNANCE.md"

---

Guiding Principle

A filename tells a reader where a document is today.

A document ID tells the organization what the document is for its entire life.