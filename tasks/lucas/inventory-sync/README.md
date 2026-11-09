# inventory-sync

- Owner: Lucas Meyer (@lucas)
- Status: Implemented
- Sprint: S34
- Priority: High
- Version: 1.9.2

Reconciles warehouse stock counts with the storefront catalogue every 15 minutes and raises low-stock alerts.

## Acceptance criteria
- Tolerate duplicate warehouse events
- Never oversell during sync windows
- Alert buyers when cover drops below 5 days

## Delivery
Entry point: jobs/sync_stock.py
Automated checks: 71
