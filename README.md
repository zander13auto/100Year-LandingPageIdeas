# 100Year-LandingPageIdeas

Concept landing-page redesigns for the WordPress.com **100-Year Plan** and **100-Year Domain** products. Built as part of the dotcom 2026 brand evolution exploration.

These are **idea drafts** — not production marketing copy. The goal was to test:

- A continuity-system narrative (Special Trust + Century Proxy + Long-Term Investment) as the structural backbone rather than a feature list.
- A scroll-driven "you are here in the century" timeline as the page's visual centerpiece.
- A vocabulary that avoids brittle absolutes (never, forever, endowment) in favor of grounded language (century, lifetime, decades, Special Trust, special-purpose proxy).
- A pricing model surfaced as a one-time decision: **$38,000 for the Plan**, **$2,000 for the Domain**, paid once.

---

## 📄 Pages

### [100-year-plan.html](./100-year-plan.html)

The full hosting product. Hero with stat band, three-pillar continuity model, the "what if Automattic isn't here" honest-answer block, a row of long-lived institutions for context, customer cards, the stability/price block, feature grid, video testimonials, and a tailored FAQ. **Vertical century rail** runs along the right edge on desktop, tracking page scroll from the current year to current year +100.

### [100-year-domain.html](./100-year-domain.html)

The domain-only product. Hero leads with a **domain search input** (yourname + TLD dropdown) and the four eligible TLDs surfaced as pills: `.com`, `.org`, `.net`, `.blog`. Same three-pillar continuity model, stability/price card, feature grid, customer cards, video testimonials, and a domain-specific FAQ. **Horizontal century rail** is pinned to the bottom of the viewport, sliding from current year → current year +100 as you scroll.

---

## 🎨 Design tokens

- Background: gray-100 `#101517`, gray-90 `#1d2327`
- Accent: warm gold `#e8c08c`
- CTA: WP blue `#3858E9`
- Type: **Recoleta** (serif headlines, italic accents), **Inter** (UI / body)

All year stamps auto-update via inline `getFullYear()` JS — the timelines say **Year / Year+100** dynamically, so the pages don't need to be re-published as the calendar moves forward.

---

## 🪞 Live demos

If GitHub Pages is enabled (see the Pages section in repo settings), both pages are live at:

- `https://zander13auto.github.io/100Year-LandingPageIdeas/100-year-plan.html`
- `https://zander13auto.github.io/100Year-LandingPageIdeas/100-year-domain.html`

The `index.html` in this repo provides a small gallery linking to both.

---

## 🔗 Related

The two scroll-driven timeline effects used here (vertical + horizontal rails) are also packaged as standalone, drop-in components in [`zander13auto/time-effects`](https://github.com/zander13auto/time-effects).

---

## 📜 Status

These are early conceptual drafts intended as discussion material, not finished marketing copy. Pricing claims, structural details (trust mechanics, investment percentages, refund windows), and customer references are illustrative and would need legal, product, and brand-team review before any production use.
