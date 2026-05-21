# GCHA Project - Master Decisions Log

## Decision 1: Bangalore Vendor Documentation Bypass (Chapter 1)
**Context:** A vendor in Bangalore offered to deliver the Mobile App two months early if we skip the Security Documentation phase.
**Decision:** REJECTED.
**Justification:** While early delivery is tempting, skipping documentation drastically increases the "Residual Risk" to public safety in a healthcare context. It also violates our Administrative Performance Quality standards, making future maintenance and compliance audits nearly impossible.

## Decision 2: Buy vs. Build for Cairo Servers (Chapter 2)
**Context:** Cairo local servers cannot handle the AI engine data load. Options: Build (upgrade local data center for $2M) vs. Buy (Cloud subscription for $500k/year).
**Decision:** BUILD (Upgrade Local Data Center).
**Justification:** Although the upfront CapEx of $2M is higher, a localized "Build" approach guarantees strict data privacy compliance and gives us full governance over sensitive clinical records. Given the strategic nature of healthcare data, minimizing security vulnerabilities outweighs the short-term cost savings of a cloud subscription.
