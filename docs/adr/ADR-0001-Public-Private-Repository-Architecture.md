# ADR-0001 – Public and Private Repository Architecture

**Status:** Accepted  
**Date:** 2026-08-02  
**Version:** 1.0

---

# Context

POG is intended to become a comprehensive operational framework for homeowners and small property owners.

Some documentation is generic and reusable by anyone.

Other documentation contains personally identifiable information (PII), financial records, tenant information, security details, and property-specific operational records.

Publishing all documentation in a public repository would expose sensitive information and reduce the framework's usefulness as an open project.

---

# Decision

POG shall adopt a three-layer architecture.

## Layer 1 – Public Framework Repository

Contains reusable documentation including:

- Standards
- Templates
- Architecture
- Governance
- Checklists
- Sample documents using fictional data
- ADRs
- Roadmaps

This repository is intended to be publicly accessible.

---

## Layer 2 – Private Operations Repository

Contains property-specific operational documentation.

Examples include:

- Property profiles
- Maintenance history
- Vendor records
- Inspection reports
- Tenant operations
- Improvement projects

This repository should remain private.

---

## Layer 3 – Secure Vault

Contains highly confidential information.

Examples include:

- Financial records
- Signed leases
- Credit reports
- Access credentials
- Alarm codes
- Banking information
- Insurance policies

These records should be stored only in encrypted, protected storage and should not reside in the public repository.

---

# Consequences

Benefits include:

- Enables POG to remain open source.
- Protects private information.
- Allows reusable documentation to benefit other homeowners.
- Simplifies sharing and collaboration.
- Reduces accidental disclosure of sensitive data.

Tradeoffs include:

- Additional repository management.
- Cross-referencing between public and private documentation.
- More deliberate document classification.

---

# Alternatives Considered

## Single Public Repository

Rejected because it cannot adequately protect private information.

## Single Private Repository

Rejected because it prevents sharing the framework with others and reduces collaboration.

## Hybrid Architecture

Accepted because it provides the best balance between openness, security, maintainability, and long-term growth.

---

# Related Documents

- FOUNDATION.md
- DATA_CLASSIFICATION.md
- ARCHITECTURE.md
- GOVERNANCE.md

---

# Notes

This ADR establishes the foundational architectural model for all future POG development.