# invoice-parser

- Owner: Priya Raman (@priya)
- Status: Implemented
- Sprint: S35
- Priority: Critical
- Version: 2.1.3

Extracts line items from supplier invoices in PDF and CSV form and reconciles them against open purchase orders.

## Acceptance criteria
- Handle invoices up to 40 pages
- Flag price and quantity mismatches above 1%
- Emit a structured reconciliation report per batch

## Delivery
Entry point: service/parse_invoice.py
Automated checks: 88
