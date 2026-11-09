# email-blaster

- Owner: Dmitri Volkov (@dmitri)
- Status: Blocked
- Sprint: S38
- Priority: Low
- Version: 0.1.0

Bulk campaign sender; blocked pending a deliverability audit and suppression-list integration.

## Acceptance criteria
- Respect the global suppression list
- Throttle outbound mail per domain

## Delivery
Entry point: campaigns/send.py
Automated checks: 5
