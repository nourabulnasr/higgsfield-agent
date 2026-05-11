# higgsfield-agent — ESM Studio Campaign

This repo is the planning and decision layer for the ESM Studio summer campaign — a full studio lookbook and product photography shoot generated using Higgsfield AI (Nano Banana Pro model). It covers 12 products across ghost mannequin mockups, studio lookbook shots (4 angles per piece), bottoms solo, and a beach editorial. The campaign involves a male and a female Soul Character generated consistently across all shots.

---

## What this repo contains

Planning, status, and decision docs only — no image files.

```
CLAUDE.md                  — project operating rules and skill loading order
ESM_SHOOT_BIBLE.md         — original shot list and batch plan
ESM_REFERENCE_BIBLE.md     — ground truth for all prompts (product corrections, character gates)
DECISIONS.md               — every approved shot, redo, skip, and rule learned (running log)
SESSION_RESUME.md          — quick-start checklist for new sessions
skills/                    — Higgsfield and Seedance generation skill files
briefs/                    — prompt briefs by brand/date
ESM-DELIVERY-2026-05-11/
  README.md                — delivery package index
  CURRENT-STATUS.md        — per-product status table (approved / CDN-only / pending)
  NEXT-STEPS.md            — prioritised generation queue with credit estimates
images/ESM-campaign/CURATION.md  — generation tracker (all 12 products, all deliverables)
```

---

## Where the actual generated images live

- **Local disk:** `images/ESM-campaign/` and `ESM-DELIVERY-2026-05-11/` (excluded from this repo — ~2.5 GB)
- **Higgsfield server:** all approved shots are retrievable by job ID (IDs recorded in DECISIONS.md)
- **Character sheets:** `ESM SHOOT/2 charachter sheets/male model.png` and `female model.png` (local only — re-download from Higgsfield generate history if needed)

---

## How to use these files

Start here, in order:

1. **`CLAUDE.md`** — read this first every session. Sets generation settings, approval flow, and skill loading order.
2. **`ESM_REFERENCE_BIBLE.md`** — ground truth for every product's visual details and critical corrections. Read before writing any prompt.
3. **`DECISIONS.md`** — the live log of every shot decision. Shows what's approved, what was redone, and what rules were established along the way.
4. **`images/ESM-campaign/CURATION.md`** — full tracker across all 4 deliverables. Use this to see the complete status of every shot.
5. **`ESM-DELIVERY-2026-05-11/CURRENT-STATUS.md`** — quick summary table: what's on disk, what's CDN-only, what's pending.
6. **`ESM-DELIVERY-2026-05-11/NEXT-STEPS.md`** — the generation queue in priority order with credit estimates.

---

## Naming convention

**Plain English only in conversation and status docs.** No symbol codes.

| Plain English | Code (filenames only) |
|---|---|
| Olive linen set — men | M-FS |
| Beige linen set — men | M-FSB |
| Beige linen polo — men | M-PB |
| Olive linen polo — men | M-PO |
| White t-shirt — unisex | U1 |
| Grey t-shirt — unisex | U2 |
| Beige quarter-zip — unisex | U3 |
| White quarter-zip — unisex | U4 |
| Olive chemise — women | F-OC |
| Olive long skirt — women | F-OS |
| Beige set — women | F-BG |
| Light blue set — women | F-LB |
