# route-optimizer

- Owner: Dmitri Volkov (@dmitri)
- Status: Implemented
- Sprint: S36
- Priority: High
- Version: 3.0.1

Computes delivery routes for field crews under time-window, capacity and driver-shift constraints.

## Acceptance criteria
- Respect hard time windows
- Balance load across available vehicles
- Return an alternative route when the plan is infeasible

## Delivery
Entry point: solver/optimize.py
Automated checks: 96
