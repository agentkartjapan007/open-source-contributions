# Contributing to this tracker

Thanks for helping keep this honest and useful. This repo is a log of work that already landed in public — not a place to discover or disclose new issues.

## What to add

Only document:

1. **Merged pull requests** in upstream open-source projects (CI, tests, docs, fixes, and similar).
2. **Already-public** GitHub Security Advisories (GHSA) or CVE records that credit us by name or GitHub handle.
3. Short notes that link back to those sources.

## What not to add

- Unpublished vulnerabilities, private vendor reports, or write-ups waiting on disclosure approval.
- Exploit PoCs or reproduction steps for issues that do not have a fix yet.
- CVE or GHSA IDs we are not clearly credited on, or that we cannot verify independently.
- Speculative or unverified claims.

If in doubt, leave it out until there is a public link.

## Workflow

1. Confirm the PR is **merged**, or the advisory/CVE is **public** and credits us.
2. Add a row to [`contributions/tracker.csv`](contributions/tracker.csv) with:
   - `date` — when the PR merged or the advisory was published (YYYY-MM-DD)
   - `project` — upstream project name
   - `type` — one of `PR`, `advisory`, or `docs`
   - `link` — URL to the PR, GHSA, or CVE page
   - `note` — one short plain-language line
3. Optionally add a short markdown note under `contributions/` if more context helps, and link that note from the CSV `note` field or a follow-up PR description.
4. Open a PR to this repo with the CSV (and optional note) change. Keep the tone warm and factual.

## Style

- Prefer plain language over jargon.
- Always include a working public link.
- Never invent credit. If the advisory does not name us, do not list it.
