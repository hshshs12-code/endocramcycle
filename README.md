# ENRE Study Hub

A self-contained set of browser-based study references, split by exam ("mini").

**Open [`index.html`](index.html)** to choose a mini. The dark bar at the top of every page shows
which mini you're in and switches between them.

## Structure

| Page | What it is |
| --- | --- |
| [`index.html`](index.html) | Landing page — pick Mini 1 or Mini 2 |
| [`mini1.html`](mini1.html) | **Mini 1** hub — Endocrine & Reproductive (complete) |
| [`mini2.html`](mini2.html) | **Mini 2** hub — Female Reproductive (placeholder, no content yet) |

### Mini 1 — Endocrine & Reproductive

The complete set: pathology, physiology, pharmacology, biochemistry, embryology/anatomy, a
pattern-recognition reverse-lookup, seven quiz banks, a 2-day review planner, and the
password-protected Final Cram exam-intel page. Every table is searchable, filterable,
mobile-friendly and cross-linked; tap any figure to enlarge it.

### Mini 2 — Female Reproductive

Scaffolding only. The section is wired into the site and reachable from the nav and home page,
but the tiles on it are empty slots rather than working pages. Section names are provisional and
get renamed once the unit's real topic list is known.

## Notes

Everything runs entirely in the browser — no build step, no server, no accounts, no tracking.
Adding a page to a mini means dropping the HTML file in the repo root and adding one line to the
`MINIS` array in the shared site-kit nav block (identical on every page).
