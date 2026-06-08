# Staged from work PC on 2026-05-28

This folder was staged into nick-memory from Nick's work PC during a Cowork session because the glaizr repo wasn't cloned locally on the work machine.

## What's here

15 files of TAM/SAM/SOM research for Glaizr:
- 8 customer interview transcripts (primary evidence)
- 3 independent research source reports (Perplexity, GPT, Nick's working doc)
- 1 reconciled memo (the canonical document for board materials and the ATOG pitch)
- 1 ATOG pitch document for Monday 1 June 2026
- 2 READMEs explaining the structure

## Intended final destination

This research properly belongs in `NickWennerbom23/glaizr` (the glaizr working repo), NOT in nick-memory. It's staged here only because nick-memory was the only mounted repo at the time of staging.

## What to do from home PC

When Nick is back at the home PC where the glaizr repo IS cloned locally:

1. Pull latest nick-memory: `cd C:\Users\<user>\Documents\GitHub\nick-memory && git pull`
2. Move this entire folder into the glaizr repo:
   ```
   Move-Item C:\Users\<user>\Documents\GitHub\nick-memory\05-resources\glaizr-tam-research\* C:\Users\<user>\Documents\GitHub\glaizr\ -Force
   Remove-Item C:\Users\<user>\Documents\GitHub\nick-memory\05-resources\glaizr-tam-research -Recurse
   ```
3. Commit and push BOTH repos:
   ```
   # glaizr
   cd C:\Users\<user>\Documents\GitHub\glaizr
   git add . ; git commit -m "research: 2026-05-28 TAM/SAM/SOM v3 reconciled (Perplexity + GPT + transcripts)" ; git push origin main

   # nick-memory (record the removal)
   cd C:\Users\<user>\Documents\GitHub\nick-memory
   git add . ; git commit -m "memory: 2026-05-28 move glaizr-tam-research to glaizr repo" ; git push origin main
   ```

## Headline numbers (for quick reference, see research/memos/ for full)

- VIC strict-ICP TAM: **A$114-199M (mid A$156M)**
- AU strict-ICP TAM: **A$388-612M (mid A$500M)**
- ATOG 2yr exclusivity cost: **A$1.4-3.4M (mid A$2.4M)**
- Reconciled across 3 independent sources (Perplexity 1× / GPT 2× / Claude transcript-corrected 2×) with Crystal override (A$17-22M from transcript evidence beats desk-research A$5-8M)
