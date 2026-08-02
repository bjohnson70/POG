# POG Data Classification Standard

**Version:** 1.0
**Status:** Adopted
**Published:** 2026-08-02

# Purpose

The purpose of this standard is to ensure that Property Operations Guide (POG) documentation protects sensitive information while allowing the operational framework itself to remain open, reusable, and version controlled.

---

# Classification Levels

## PUBLIC

Information that may be published to a public GitHub repository.

Examples include:

- Framework documentation
- Standards
- Templates
- Checklists
- Example documents using fictional data
- Operating procedures
- Maintenance schedules
- Inspection forms
- Decision Records (ADR)
- Public roadmaps
- Enhancement requests
- Feature ideas

---

## PRIVATE

Operational information that identifies a specific property or individual.

Examples include:

- Property addresses
- Tenant names
- Applicant information
- Lease documents
- Vendor contact information
- Maintenance history
- Property photographs
- Insurance information
- Tax records
- Mortgage information

Private documentation belongs in a future Private POG repository.

---

## RESTRICTED

Highly sensitive information that should never be stored in a public repository.

Examples include:

- Banking information
- Social Security Numbers
- Driver License Numbers
- Credit reports
- Tenant applications
- Signed leases
- Alarm codes
- Door lock codes
- Security system configurations
- Passwords
- API keys
- Wi-Fi credentials

Restricted information should reside only in an encrypted vault or other protected storage.

---

# Repository Architecture

POG consists of three logical layers:

1. Public Framework Repository
2. Private Operations Repository
3. Secure Vault

Each layer references the next using document identifiers rather than embedding sensitive information.

---

# Guiding Principles

- Public by default.
- Private by necessity.
- Restricted by design.
- Templates should never contain real customer or tenant information.
- Documentation should reference private records using IDs instead of names whenever possible.
- The public framework should always be reusable by any homeowner or property manager.

---

# Governance

This document applies to every future document created within the POG framework.

Questions regarding classification should always choose the more restrictive classification.