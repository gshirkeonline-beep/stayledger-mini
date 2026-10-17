# StayLedger Mini V1.0

Offline-first room and billing tool for small Indian homestays with approximately 2–10 rooms.

## Scope

Room setup, stays, itemized charges, payments and refunds, read-only non-GST stay statements, local CSV exports, encrypted password-protected backups, and PWA support. No cloud database, paid API, AI service, or runtime dependency.

## Release boundary

The uploaded source is a verified prototype. Android/iPhone persistence, offline reload and restore, legal/compliance, and commercial validation remain incomplete. It is not production-ready or GST-compliant.

## Tests

Run npm test with Node 18+ to execute deterministic billing, booking-conflict, and backup-crypto tests. Generated screenshots and test-output files are excluded from this repository.

## Data handling

Guest records remain in browser storage on the device. CSV, image, and printed-PDF exports are unencrypted; encrypted backup files require the owner password.
