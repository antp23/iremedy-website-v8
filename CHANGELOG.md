# iRemedy Website v8 — Change Log

**Project:** `iremedy-website-v8`
**Live:** https://antp23.github.io/iremedy-website-v8/
**Local:** `/Users/berniemac/projects/iremedy-website-v8/index.html`
**Repo:** github.com/antp23/iremedy-website-v8 (gh-pages branch)

Use these `CHG-XXX` numbers to reference specific states when picking up work across sessions (WhatsApp, web, etc.).

---

## Active State

**Current:** CHG-017 — Manufacturers page full redesign
**Date:** 2026-05-05

---

## Change History

### CHG-017 — Manufacturers page full redesign
**Date:** 2026-05-05
**Commit:** `0a15d50`
- Replaced thin 2-section placeholder with full 10-section conversion page
- Section 01: Hero — dark bg, headline, italic subheadline, proof strip, two CTAs (Get Started + See the Incubator anchor)
- Section 02: The Gap — two-col body copy, callout "iRemedy closes that gap"
- Section 03: Two Paths — Incubator card (full stack, pricing callout $5K–$15K) + DaaS card, side-by-side
- Section 04: Infrastructure — dark bg, 4 stat blocks (18M+ sqft / 95% / 200+ / 24/7), supporting copy
- Section 05: MetaCommerceRx — two-col with 5 numbered cap-list features, demo CTA
- Section 06: Built For — two-col, 6 client type tiles in 2×3 grid
- Section 07: Social Proof — 3-col client grid (Spectrum Medical, GLVUS, FlexGRIP, CathCare, Speranza + "your company here"), testimonial placeholder
- Section 08: Process — 5-step cap-list + timeline callout card (2–6 weeks)
- Section 09: FAQ — 7 manufacturer-specific accordion Q&As
- Section 10: CTA — dark bg, full-width, Get Started + Anthony contact line

---

### CHG-016 — Nav and footer logo replacement
**Date:** 2026-05-05
**Commit:** `56c589a`
- Replaced text "iREMEDY.com" in nav with `iRemedy_Logo_wo_Slogan.png` (36px tall, links to home)
- Replaced text "iREMEDY HEALTHCARE COMPANIES" in footer with same logo (28px tall)
- Both logo files added to `assets/`: `iRemedy_Logo_wo_Slogan.png`, `iRemedy_Logo_White_Text.png`

---

### CHG-015 — Global type scale polish pass
**Date:** 2026-05-05
**Commit:** `cf960ab`
- Panel headline reduced: `clamp(3rem,6.5vw,7rem)` → `clamp(2.5rem,5vw,4.5rem)`
- Body text enforced at 1rem minimum: `.sec-body`, `.cap-body`, `.blist li`, `.callout p`, `.p-text`
- Footer: links → 0.875rem, address → 0.8rem, col headers → 0.8rem, tagline → 0.875rem
- Stats: label → 0.75rem, sub → 0.875rem
- Buttons: 0.65rem → 0.875rem
- Cert badges: 0.52rem → 0.8rem, padding increased
- Eyebrow / panel-eyebrow labels: 0.58rem → 0.8rem
- Hero: max-width 90vw constraint, headline margin-bottom 2.5rem, credential strip → 0.8rem
- Routing cards: body text → 1rem, CTA links → 0.8rem
- Card 3: link updated to Government page, CTA → "See Government Solutions →"
- FAQ: expanded to full content width (removed max-width:820px)
- FAQ questions: 1.05rem → 1.125rem (all 7); answers: 0.9rem → 1rem (all 7)
- Trusted By credential line: 0.56rem → 0.8rem
- Footer: Supply Side Podcast link added below address

---

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
