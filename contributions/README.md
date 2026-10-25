# Contributions tracker

This folder holds the living list of our open-source contributions.

## Files

- [`tracker.csv`](tracker.csv) — the main log. Add one row per merged PR or public advisory we are credited on.

## Columns

| Column | Meaning |
|--------|---------|
| `date` | YYYY-MM-DD when the PR merged or the advisory was published |
| `project` | Upstream project name |
| `type` | `PR`, `advisory`, or `docs` |
| `link` | Public URL (PR, GHSA, or CVE page) |
| `note` | Short plain-language summary |

## Example row

The CSV includes a commented example line (starting with `#`) so the format is clear. Replace it with real entries as work lands. Do not invent CVEs or claim credit without a public source.
