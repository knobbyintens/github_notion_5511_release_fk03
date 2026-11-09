# image-pipeline

- Owner: Kenji Sato (@kenji)
- Status: Implemented
- Sprint: S36
- Priority: Medium
- Version: 2.3.5

Batch normalisation pipeline for catalogue imagery: EXIF stripping, responsive resizing and WebP conversion.

## Acceptance criteria
- Process 10k assets per hour
- Keep colour profiles consistent
- Retry failed conversions twice before quarantining

## Delivery
Entry point: pipeline/run.py
Automated checks: 39
