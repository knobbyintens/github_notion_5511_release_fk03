# churn-scorer

- Owner: Amir Ahmed (@ahmed)
- Status: Implemented
- Sprint: S34
- Priority: High
- Version: 1.4.0

Scores account churn risk nightly from engagement, billing and support signals, then publishes risk bands to the customer profile store.

## Acceptance criteria
- Score refresh completes before 04:00 UTC
- Risk bands calibrate against last quarter's cancellations
- Failed scoring runs raise an on-call alert

## Delivery
Entry point: src/score.py
Automated checks: 63
