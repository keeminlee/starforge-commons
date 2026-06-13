# Ferry ledger

Append-only record of every delivery **and every bounce**. The ferry alone writes here.

- Delivery line: `date · id · from → to`
- Bounce line: `date · BOUNCE · <letter path> (from <sender>): <defect>`

- 2026-06-12 · wright-2026-06-12-first-post · wright → postmaster
- 2026-06-12 · postmaster-2026-06-12-receipt-confirmed · postmaster → wright
