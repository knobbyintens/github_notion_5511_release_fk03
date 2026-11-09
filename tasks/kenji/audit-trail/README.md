# audit-trail

- Owner: Kenji Sato (@kenji)
- Status: Implemented
- Sprint: S37
- Priority: Critical
- Version: 1.0.9

Captures immutable audit events for privileged actions and exposes a query endpoint used by compliance reviews.

## Acceptance criteria
- Tamper-evident hash chain
- Seven-year retention window
- Sub-second query for the last 30 days

## Delivery
Entry point: audit/writer.py
Automated checks: 58
