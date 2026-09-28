# Core Axis HQ — Site Rescue homepage preview

**Status:** review only · **do not** point `coreaxishq.com` here until Nero says go  
**Owner account:** `coreaxishq` on GitHub  
**Live production today:** https://coreaxishq.com (unchanged)

## What’s in this repo

Static preview of a reworked homepage that leads with the locked sprint offer:

**14-Day Site Rescue** — Good £1,450 / Better £1,950 (default) / Best £2,750

Open `docs/index.html` locally, or enable GitHub Pages on the `docs/` folder after push.

## What the live site does today (original)

Pulled from https://coreaxishq.com on 28 Sep 2026:

- **Stack:** Next.js (prerendered) behind Caddy on DigitalOcean
- **Look:** dark navy (`#0a101b`), blue accent, video hero, sticky nav, Manrope/Sora-style UI
- **Positioning:** “Stand out first. Then scale with systems.” / Digital Solutions Partner
- **Three equal service lanes:**
  1. Digital Presence (websites, brand, UX)
  2. Systems & Automation (workflows, internal tools)
  3. Advanced Digital Builds (Web3, Telegram bots, NFT utilities)
- **Build directions:** Corporate Website · Modern Service Brand · Startup Landing · Specialist Interfaces
- **CTA:** “Start Project Brief” → on-page project form
- **Tone:** multi-lane agency/partner brochure — not a single productised cash offer

Source code for that live site was **not** in the connected `coreaxishq` GitHub account (0 public repos; no accessible `coreaxishq.com` / `website` repo via Cursor’s GitHub App). This preview is a **new** static draft from scratch, matching brand colours/logo, not a fork of production.

## What this preview changes

| Live today | This preview |
| --- | --- |
| Equal three-lane brochure | **Site Rescue** flagship above the fold |
| Generic “Start Project Brief” | Packages + 14-day process + book/email CTA |
| Advanced/Web3 emphasised early | Advanced builds kept as secondary “also build” |
| No fixed public prices | Transparent Good / Better / Best |
| Production indexable | `noindex` preview banner |

Multi-lane brand kept (websites / systems / advanced) so Core Axis is not trapped as “site rebuild only”.

## Local preview

```bash
cd docs && python3 -m http.server 4173
# open http://127.0.0.1:4173
```

## Production rule

Merging or deploying to `coreaxishq.com` needs Nero’s explicit OK after review.

## v2 (28 Sep 2026)
Studio-aligned rewrite: removed personal name from public face, matched live Core Axis visual language (orbs/grid/glass header), Site Rescue as flagship package under multi-lane brand.
