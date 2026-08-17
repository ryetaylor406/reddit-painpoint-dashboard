# Reddit Pain-Point Dashboard

Live dashboard for the Reddit pain-point monitor: proof that customers are already asking for what Rye Taylor Consulting fixes.

- **Data:** classified Reddit posts across 6 niches (agency, bookkeeping, ecommerce, nocode, real estate, small business)
- **Triage:** ⭐ Interested / ✉️ Contacted / ❌ Passed + notes, synced across devices via the Apps Script webhook
- **Regenerate:** run `run_all.py --commit` in the monitor project, then push the new `index.html` here

Static single-file HTML. Deployed via GitHub Actions (`.github/workflows/pages.yml`).
