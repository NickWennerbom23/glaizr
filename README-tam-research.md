# Glaizr

AI-native takeoff + site-measure + workflow platform for the Australian specialist shower screen, mirror, splashback, wardrobe door, and wardrobe install industry. Closed-source Microsoft Azure environment per cohort customer.

**Built by:** Nick Wennerbom (founder, distribution, domain expert) + Courtney Smith (AltZero, dev) + Dave Dhanda (Kynection, build).

**Status as of 2026-05-28:** Pre-launch cohort recruitment. Founding cohort target 10, signups closing 30 June 2026. V1 build clock starts 1 July 2026. First product to cohort partners in 8 weeks.

## Repo structure

```
glaizr/
├── README.md                    # This file
├── research/
│   ├── memos/                   # Final reconciled analysis memos
│   ├── source-reports/          # Independent research inputs (Perplexity, GPT, working doc)
│   └── transcripts/             # Customer interview transcripts (primary evidence)
├── models/                      # Financial models, TAM/SAM/SOM spreadsheets, pricing
└── pitch/                       # Pitch deck materials, exclusivity scenarios, founder docs
```

## How to use this repo

**Look at `research/memos/2026-05-28-tam-sam-som-reconciled-v3.md` first.** That's the headline document for board materials, the ATOG pitch (Monday 1 June), and any subsequent investor/partner conversation. It reconciles three independent TAM estimates and overrides Crystal upward using transcript evidence.

**Transcripts** under `research/transcripts/` are the **primary evidence** for every company revenue estimate. If you're challenged on a number, the transcript is the source.

**Source reports** under `research/source-reports/` are the three independent research inputs:
1. Perplexity deep-research (under-counted Ventora consolidation, Crystal, Premium, ATOG)
2. GPT deep-research (closer to ground truth, but still under-counted Crystal)
3. Nick's working doc (original brain dump pre-transcript)

The reconciled memo weights these 1:2:2 (Perplexity gets half-weight) and then overrides Crystal upward because transcript evidence beats desk research.

## Reconciled headline numbers (2026-05-28)

| Region | Strict TAM (AUD) | SAM (AUD) | Early SOM 2-10% / 3yr |
|---|---|---|---|
| Victoria | A$114-199M (mid A$156M) | A$57-139M | A$1.1-13.9M |
| Australia | A$388-612M (mid A$500M) | A$194-428M | A$3.9-42.8M |
| California | A$160-225M | A$80-140M | A$1.6-14M |
| Texas | A$140-200M | A$70-120M | A$1.4-12M |
| UK (strict-ICP glass install) | A$280-470M | A$140-235M | A$2.8-23.5M |
| UK (wardrobe D2C, separate product) | A$442-600M | ~5 enterprise accounts | Different sales motion |

**ATOG VIC exclusivity cost (2yr): A$1.4-3.4M (mid A$2.4M).** Option A almost certainly outside ATOG's cash capacity. Option B (5% equity each to Ty + Ryan) remains the better close.

## Top 10 by revenue (reconciled)

**Australia:**
1. Ventora Glass (Stegbar+Regency consolidated) — A$100M
2. Civic Shower Screens & Wardrobes (QLD) — A$23-38M
3. ATOG (VIC) — A$19-27M
4. Premium Showers & Robes (VIC) — A$12-20M
5. Crystal Home Concepts (VIC) — A$17-22M [transcript-overridden]
6. Monaro Screens (ACT/NSW) — A$10-15M
7. Britone (NSW) — A$11-15M
8. Cesana Australia (multi-state) — A$4-8M
9. Adelaide Shower Screens (SA) — A$3-6M
10. Onyx Showerscreens (QLD) — A$2.4-3.6M

**Victoria:**
1. Ventora Glass VIC slice — A$28-35M
2. ATOG — A$19-27M
3. Crystal Home Concepts — A$17-22M
4. Premium Showers & Robes — A$12-20M
5. Pipers International (VIC ops) — A$5-10M
6. Cesana (VIC ops) — A$3-5M
7. Precision Shower Screens & Robes — A$3-5M
8. ASW — A$2-4M
9. Shower Ranger — A$2-4M
10. Executive Robes & Screens — ~A$2M (capped)

VIC long tail beyond top 10: 20-30 named operators (Speedy, Amazing, Prestige, Liberty, Jaycee, Mega, SI Glass, etc.) two-tier split A$4-7M top half, A$2-3M bottom half.

## Cross-repo links

This repo is the **working repo** for Glaizr. Cross-cutting context (active threads, decisions, relationships, session history) lives in [nick-memory](https://github.com/NickWennerbom23/nick-memory) under `01-memory/active-context/glaizr.md`.

Related working repos:
- [bowen-operations](https://github.com/NickWennerbom23/bowen-operations) — Bowen Storage operations (Nick's day job)
- [revisr-core](https://github.com/NickWennerbom23/revisr-core) — Revisr (Nick's AI compliance startup)
- [personal-growth](https://github.com/NickWennerbom23/personal-growth) — Property and equities portfolio
- [nick-memory](https://github.com/NickWennerbom23/nick-memory) — Persistent AI-accessible memory layer

## Validation work outstanding

1. ASIC filing for Ventora Group Pty Ltd — confirm A$100M is glass-only
2. ASIC/D&B for Crystal Home Concepts and Premium FY24/FY25
3. Civic 130-fitter claim → back-solve A$23-38M
4. Verify CreoGlass successor entity (original Ltd companies dissolved March/April 2025)
5. Contractors Wardrobe (CA) — confirm US$39M is CA-only or multi-state
6. UK strategy decision: Camp A (London glass installers, cohort model) vs Camp B (wardrobe D2C giants Sharps/Hammonds, enterprise sales motion)

## Pricing model (locked 2026-05-28)

- Onboarding: A$12,500 one-off
- Annual maintenance: A$6,500/year (first 10 users included)
- Per-additional-user: A$59/user/year
- Per-project: A$5 per **won** project (post-contract-signed, not at quote stage)
- 50% lifetime subscription discount for founding 10 cohort members
- Cohort signup deadline: 30 June 2026
