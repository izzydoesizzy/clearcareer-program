# The Job Search Ignition System — Program Landing Page

Static site for the May 2026 group coaching program launch. Hosted on GitHub Pages.

**Live:** https://izzydoesizzy.github.io/clearcareer-program/

---

## Pages

| Page | File | What It Does |
|------|------|-------------|
| **Program page** | `index.html` | Main sales page. Program overview, deliverables, pricing, ROI calculator, client results, testimonials, FAQ, and CTA. |
| **Outcomes report** | `outcomes.html` | Data-driven report from 58 surveyed members. Charts, stats, NPS, salary data, confidence shift, AI fluency. Linked from the program page. |
| **Ambassador sharing kit** | `share.html` | Copy-paste messages for past clients and ambassadors to share the program via LinkedIn, email, text, and Instagram. |

## Program Details

- **Name:** The Job Search Ignition System
- **Format:** 8-week accelerator, virtual, open to Canada + US
- **Launch date:** May 4, 2026
- **Spots:** 15
- **Pricing:** $2,497 (pay in full) / 3x $899 / Klarna up to 12 months
- **Bonuses:** Private 1:1 strategy session + GoPlace VIP Mastermind Retreat in Markham (late May)

## Tech

- Pure static HTML/CSS/JS. No build tools, no frameworks, no dependencies.
- Hosted via GitHub Pages (deploys on push to `main`).
- Dark theme (`#0a0f1a` background, Inter font, blue/green/gold/pink accent system).
- Interactive salary/ROI calculator in vanilla JS.
- SVG icons inline (Feather-style, stroke-based).
- Charts are CSS horizontal bars with percentage widths.
- Donut chart is inline SVG with `stroke-dasharray`.
- Print-friendly styles included on all pages.
- Mobile responsive.

## Referral Campaign

The program page is linked from personalized referral emails sent to 46 past clients (managed in the `izzy-master-profile` repo under `daily-ops/REFERRAL-CAMPAIGN.md`).

**Referral incentive:** $250 cash per signup. Referred person gets a bonus 1:1 session + VIP Mastermind Retreat at GoPlace Spa.

## Related Repos

| Repo | What |
|------|------|
| `clearcareer-client-manager` | CLI + web dashboard for managing clients, deliverables, AI agents |
| `clearcareer-website` | Main marketing site (joinclearcareer.com), Astro + Tailwind |
| `izzy-master-profile` | Izzy's master profile, strategy docs, daily ops, referral campaign |
