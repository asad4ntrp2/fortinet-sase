# Changelog

All notable changes to the **Fortinet Unified SASE — Portfolio & Architecture Reference** are documented here.
Format loosely follows [Keep a Changelog](https://keepachangelog.com/). Dates are in `YYYY-MM-DD`.

---

## [1.2.0] — 2026-06-25

### Added
- **Visitor counter** — VisitorBadge.io "Page views" badge in the page footer and the README (no signup, no cookies), matching the approach used in the `infoblox-interview-guide` repo.
- **Project status** section + this **CHANGELOG.md** to track progress.
- Status/format badges in the README header.

## [1.1.0] — 2026-06-25

### Added
- **Section 7 — Sovereign SASE** (Data Sovereignty & Deployment Control):
  - Definition and rationale (data-residency, government, defense, critical infrastructure).
  - **Figure 5 — deployment spectrum** diagram: ① Fortinet-hosted → ② Service-provider-hosted (in-country) → ③ Self-hosted (full sovereign / air-gap capable).
  - "What you control" cards, standard-vs-sovereign comparison table, and "who needs it" segment chips.
  - Glossary entry and hero pill for Sovereign SASE.

### Changed
- Renumbered sections to **1–13** and figures to **1–7** (Sovereign SASE inserted after Datacenter Connectivity).
- README contents table and briefing updated to include Sovereign SASE.

## [1.0.0] — 2026-06-25

### Added
- Initial single-page HTML reference (`index.html`) — self-contained, responsive, print-friendly, all diagrams as inline SVG. Sections:
  1. What is Fortinet SASE
  2. Product Portfolio (Fig 1: 4-layer portfolio map)
  3. Roles & Where Used
  4. Reference Architecture (Fig 2)
  5. Service Connectivity — SIA / SPA / Secure SaaS (Fig 3)
  6. Datacenter Connectivity — SD-WAN hub vs ZTNA (Fig 4)
  7. Feature Matrix
  8. Licensing Model (Fig 5)
  9. Costing Model — worked 1,000-user example
  10. Core Use Cases
  11. Industry Integration Blueprints (Fig 6)
  12. Summary & Glossary
- **README.md** — briefing, contents table, local-view steps, and verified Fortinet reference links.
- Published to GitHub and enabled **GitHub Pages** (live URL); set the repo "About" website link.
- Author credit (**Asad Yaseen**) in the page footer and README.

### Notes
- All pricing/licensing figures are **illustrative planning placeholders**, not quotes.
- Commit history authored solely by **Asad Yaseen** (no third-party co-author trailers).

---

## Pending / ideas
- Optional: GoatCounter for full analytics dashboard (countries, referrers, daily trends) if richer stats are wanted later.
- Optional: top-of-page clickable Table of Contents and a print-optimized PDF export.
