# social-scheduler

- Owner: Noor Haddad (@noor)
- Status: Implemented
- Sprint: S36
- Priority: High
- Version: 1.6.1

Schedules approved social posts across channels with per-platform limits, retries and timezone-aware publish windows.

## Acceptance criteria
- Never publish unapproved content
- Honour per-channel rate limits
- Surface failed publishes for manual review

## Delivery
Entry point: scheduler/publish.py
Automated checks: 67
