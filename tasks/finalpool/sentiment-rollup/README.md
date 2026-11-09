# sentiment-rollup

- Owner: Mira Chen (@mira)
- Status: Implemented
- Sprint: S35
- Priority: Medium
- Version: 1.2.0

Aggregates product review sentiment by category and week and reports week-over-week trend deltas.

## Acceptance criteria
- Deduplicate syndicated reviews
- Report sampling confidence
- Expose dashboards for category owners

## Delivery
Entry point: analytics/rollup.py
Automated checks: 44
