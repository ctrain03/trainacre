# Northern California CRE Website — Launch Guide

A complete static website: no build step, no framework. Every file in this folder gets uploaded as-is.

## What's here

| File | Purpose |
|---|---|
| `index.html` | Home page — all markets, services, FAQ |
| `san-francisco.html` / `.md` | SF city page + AI/SEO summary |
| `san-jose.html` / `.md` | San Jose & Silicon Valley |
| `sacramento.html` / `.md` | Greater Sacramento |
| `oakland-east-bay.html` / `.md` | Oakland & East Bay |
| `peninsula.html` / `.md` | SF Peninsula |
| `out-of-state-investors.html` / `.md` | Your differentiator page |
| `llms.txt` | AI-assistant discovery file (how ChatGPT/Claude/Perplexity find you) |
| `robots.txt`, `sitemap.xml` | Search-engine technical files |
| `styles.css` | Shared design |
| `GBP-PLAYBOOK.md` | Google Business Profile setup — the legitimate version |

Every page includes schema.org `RealEstateAgent` and `FAQPage` JSON-LD markup — this is what feeds Google rich results and AI answer engines.

## Site details — already filled in (2026-07-02)

All placeholders are populated across every file:

- **Name:** Chris M. Traina
- **Brokerage:** Delta Real Estate
- **CA DRE #:** 02013484 (in the footer of every page — required on all CA advertising)
- **Phone:** (408) 417-3393 (`tel:+14084173393` in links)
- **Email:** traina@me.com
- **Domain:** trainacre.com (in canonical tags, sitemap, robots.txt, llms.txt, all .md files) — **must be registered before launch**
- **Deal size range:** "$1M to $20M" on out-of-state-investors.html — adjust if this doesn't match your actual range

**Legal note:** your DRE license ID appears on every page as required for CA solicitation materials. Keep NAME + PHONE + brokerage identical everywhere (site, GBP, LinkedIn, LoopNet) — consistent "NAP" data is a local-SEO ranking factor.

## Deploying (pick one, ~10 minutes)

1. **Register trainacre.com** — Cloudflare Registrar (at-cost, ~$10/yr), Namecheap, or Porkbun. Backups also confirmed available on 2026-07-01: `norcalcre.com`, `norcalcommercialagent.com`, `trainacommercial.com`. If you pick a different domain, search-and-replace `trainacre.com` in all files.
2. **Netlify (easiest):** netlify.com → drag this folder onto the dashboard → done. Free tier, free SSL. Then add the custom domain under Site settings → Domain management.
   - Cloudflare Pages / Vercel / GitHub Pages all work identically for static files.
3. One domain only — do NOT buy one per city (doorway-site penalty risk, and it splits your ranking authority).

## After launch — the ranking checklist

1. **Google Search Console** — add the site, submit `sitemap.xml`.
2. **Google Business Profile** — follow `GBP-PLAYBOOK.md` (one Service Area Business, real address).
3. **Bing Webmaster Tools** — matters more than you'd think: Bing feeds ChatGPT's browsing.
4. **LoopNet / Crexi / CoStar agent profiles** — link to your site; these dominate commercial searches.
5. **LinkedIn** — profile headline: "Commercial Real Estate Agent | San Francisco · San Jose · Sacramento | Out-of-State Investor Specialist", link the site.
6. **Reviews** — after every closing, ask the client to mention city + property type.
7. **Content cadence** — one short market note per region per month (add as new pages) keeps the site fresh for both Google and AI engines. AI assistants disproportionately cite pages that answer questions directly — the FAQ format on every page is deliberate.
