# iRemedy Website v8 — Change Log

**Project:** `iremedy-website-v8`
**Live:** https://antp23.github.io/iremedy-website-v8/
**Local:** `/Users/berniemac/projects/iremedy-website-v8/index.html`
**Repo:** github.com/antp23/iremedy-website-v8 (gh-pages branch)

Use these `CHG-XXX` numbers to reference specific states when picking up work across sessions (WhatsApp, web, etc.).

---

## Active State

**Current:** CHG-014 — Homepage redesign (routing cards, 6-section structure, FAQ)
**Date:** 2026-05-05

---

## Change History

### CHG-014 — Homepage full redesign
**Date:** 2026-05-05
**Commit:** `5550bed`
- Section 01: New hero — routing cards (Manufacturers / Providers & Pharmacies / Government & Policy), static credential line, ticker moved below cards
- Section 02: "What We Do" — direct distribution copy, hub-spoke SVG, proof line callout
- Section 03A: Technology — MetaCommerceRx, "Patent-protected AI. Running in production.", terminal widget
- Section 03B: TradeSpy dark callout — `#212E3E` background, 3 stat cards (129,140 / 412 / 89)
- Section 04: Trusted By — logo bar (UPS + 4 placeholders), testimonial placeholder cards
- Section 05: Stats updated — `129,140 NDCs Monitored` replaces `<10% Domestic API Mfg.`
- Section 06: FAQ accordion — 7 Q&A pairs

---

### CHG-013 — Add Government nav item and audience page
**Date:** 2026-05-05
**Commit:** `2736c1d`
- New nav item: Manufacturers · Providers · Pharmacies · **Government** · Platform · TradeSpy · Company
- New page `#page-government`: federal distribution + TradeSpy COO callout
- Government added to footer Markets column

---

### CHG-012 — Information architecture restructure
**Date:** 2026-05-05
**Commit:** `1fb68ff`
- Nav rebuilt: Manufacturers · Providers · Pharmacies · Platform · TradeSpy · Company | Login · Get Started
- "Solutions" dropdown removed entirely
- "Engage" → "Get Started" (accent blue button)
- New Platform placeholder page (`#page-platform`): MetaCommerceRx + 10-patent chips
- TradeSpy elevated to top-level nav
- Legacy pages archived: `page-legacy-direct`, `page-legacy-technology`, `page-legacy-logistics`, `page-legacy-incubator` (HTML preserved, removed from routing)
- Footer: Solutions → Platform (MetaCommerceRx + TradeSpy); Services → Markets
- Homepage CTAs relinked: Smart Distribution → Providers ("Learn More →"); Platform → Platform page

---

### CHG-011 — Brand color palette update
**Date:** 2026-05-05
**Commit:** `2024f58`
- `--teal` → `#0064A5` (Medium Persian Blue — primary headings/links)
- `--cerulean: #00ACE6` added (Vivid Cerulean — hover states, badges)
- `--ink` → `#212E3E` (Imperial Primer — body text + hero bg)
- `--ink-2` → `#3D4D5E`
- `--hero-bg` → `#212E3E`
- All inline SVG hex codes updated to match
- `btn-teal:hover` → cerulean

---

### CHG-010 — Media page: press releases section
**Date:** 2026-05-04
**Commit:** `8e18572`
- 20 press releases from iremedy.com/news added below media tiles
- Real dates, titles, URLs, category tags (newest → oldest: Feb 2026 → 2023)

---

### CHG-009 — Media page: Supply Side Podcast tile
**Date:** 2026-05-04
**Commit:** `a1c42be`
- Replaced Operation Warp Speed tile with The Supply Side Podcast tile

---

### CHG-008 — Mission page: "(and then everything)" parenthetical
**Date:** 2026-05-04
**Commit:** `eeb3b59`
- Added "(and then everything)" after "healthcare supply chain." in hero headline

---

### CHG-007 — Leadership page redesign
**Date:** 2026-05-04
**Commits:** `6f038ca`, `a414715`
- 3-section layout: Executive Team (Tony, Anthony, Amanda) + 6 board placeholders + Special Advisors (Murray, Willem)
- 4-column grid, 90px avatar silhouettes ("PHOTO PENDING")

---

### CHG-006 — Smart Distribution SVG & layout
**Date:** 2026-05-04
**Commits:** `1d0fb52`, `2ef87e9`, `fcbcc03`
- Animated hub-and-spoke SVG added (iRemedy Direct → 6 endpoints)
- SVG max-width 850px, column ratio 1.6:1
- Homepage reordered: Smart Distribution (02) before Platform (03)

---

### CHG-005 — TradeSpy page redesign
**Date:** 2026-05-04
**Commits:** `6b91285`, `842273a`
- Light background replacing dark intel-briefing aesthetic
- American flag SVG in hero
- Animated pipeline SVG (ORCHESTRATOR → FIELD/SCORING AGENTS → RECONCILER)
- Full content sections: Three Layers, Architecture, Live Today, Federal Governance, CTA

---

### CHG-004 — Homepage hero update
**Date:** 2026-05-04
**Commits:** `565e0cb`, `d1c448b`, `3463e7d`
- Headline: "AI Distribution. / Smarter supply. Better care."
- Platform section headline and description expanded
- Panel 3 (The Network) and Panel 4 (The Position) removed — homepage now 3 panels

---

### CHG-003 — Nav: audience items to top nav
**Date:** 2026-05-04
**Commits:** `a153f99`, `a4dcf6e`
- Manufacturers, Providers, Pharmacies moved to top-level nav
- Nav font size increased 0.6rem → 0.9rem

---

### CHG-002 — v8 initial build
**Date:** 2026-05-03 (approx)
**Commit:** `56d8e49`
- Dark editorial design, credibility strip, stats strip
- Homepage panels: Mission, Platform, Network, Position
- Incubator promoted, audience subpages scaffolded

---

### CHG-001 — v8 project created
**Date:** 2026-05-03 (approx)
**Commit:** `56d8e49`
- Repo created: github.com/antp23/iremedy-website-v8
- gh-pages branch, single-file HTML SPA
- Base design system: Playfair Display + IBM Plex Mono + Inter, cream/dark palette

---

## Pending / Known TODOs

- Leadership board: 6 director names, bios, photos needed
- All executive headshots: "PHOTO PENDING" throughout
- Testimonials (Section 04): 2 real quotes needed
- Logo bar (Section 04): 4 client logos needed
- Trusted By / Logo placeholders: [Client Logo 2–5]
- Platform page: full MetaCommerceRx content pass needed
- Chloride RV Park: Formspree endpoint needs real account before going external
