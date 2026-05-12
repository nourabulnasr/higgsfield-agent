# ESM CAMPAIGN — GENERATION PIPELINE
> This document is the locked operating procedure for all ESM studio shot generation.
> Built from empirical testing across 6+ attempts per shot type.
> Last updated: 2026-05-12

---

## WORKING RULES (proven across all approved shots)

### Reference Stack — Non-Negotiable

1. **Character anchor FIRST** — most recent approved campaign studio shot of the same model at the same angle (front for front, back for back, side for side)
2. **Garment anchor SECOND** — approved ghost mannequin mockup of the target product
3. **NO worn-product photos** — any image containing a human wearing the garment CANNOT be used as a reference. The model copies the person in the image regardless of prompt instructions. Zero exceptions.

### Prompt Structure

- Use labeled sections: GARMENT / CHARACTER / STYLING / LIGHTING / CAMERA / STYLE
- Lead with the most critical constraint (e.g. button count)
- Positive framing — describe what you want, not what to avoid (exception: button count negative constraint is acceptable)
- Full sentences, not tag soups

### Approval Rules

- **Only Nour approves shots.** Agent generates and documents only. Never declare "approved" or "passing."
- One shot at a time during methodology testing
- Show: filepath + job ID + credit cost + visual observations (no verdict)
- Wait for explicit approval before generating the next shot

### Generation Settings

- Model: Nano Banana Pro (`nano_banana_2`)
- Resolution: 4K
- Aspect ratio: 4:5 (studio lookbook) / 1:1 (detail shots)
- enhance_prompt: OFF — prompts are precisely engineered, never let model rewrite

---

## KNOWN LIMITATIONS

### Button Count Bias (Nano Banana Pro)

**Problem:** Nano Banana Pro has a training-data prior toward 4-button polos. This bias persists regardless of:
- Prompt text emphasis ("THREE BUTTONS", "CRITICAL", "count: one two three")
- Button-count-first prompt structure
- Negative constraints ("not 4, not 5")
- AI-generated ghost mannequin references (they inherit the same bias)
- Flux Kontext post-edit attempts

**Tested and failed:** v3, v4, v5, v6 (4 generation attempts) + v6-kontext (Flux Kontext edit)

**Current hypothesis under test:** Real photograph crops used as surgical detail references may override the training bias because the model treats photographs as ground-truth data with higher fidelity than AI-generated references.

---

## PENDING TEST — v7 Crop-Reference Methodology

**Theory:** Crop a tight close-up from a real product photograph showing exactly 3 buttons on a polo placket. Use this crop as a dedicated "button authority" reference (second in stack, after character anchor, before ghost mannequin).

**Reference stack for v7:**
1. `SL-MPB-F.png` — character anchor
2. `reference/details/olive-polo/placket-3buttons.png` — button authority (crop from real photo)
3. `MK-MPO ghost mannequin` — overall silhouette + color

**If v7 passes button count:** This becomes the locked Stage 1 methodology and batch generation begins (4 shots per product simultaneously).

**If v7 fails:** Wait for Nour to deliver new real product photographs. Do not attempt further prompt engineering.

---

## STAGE 2 — SURGICAL FIXES (post-generation)

**Tool:** Flux Kontext (`flux_kontext`) — image editing model, context-aware, no manual mask required.
**Cost:** 1.5 credits per edit job
**Total per shot:** 4 cr (Stage 1) + 1.5 cr (Stage 2 if needed) = 5.5 cr

**When to use:** Any spec deviation that is localised (button count, collar shape, color saturation, pocket placement). Do not use for character drift or full garment reconstruction.

**Flux Kontext limitations:** Tested on button count removal — result was still 4 buttons. May not be reliable for structural button count changes. Further testing required.

---

## BATCH GENERATION (locked after v7 passes)

Once the front shot methodology is locked:
- Generate back + side + detail simultaneously (3 shots in parallel)
- All 3 use the same reference stack with angle-appropriate adjustments
- Cost: 4 credits × 3 = 12 credits per batch
- Show all 3 together for batch approval

---

## DELIVERY STRUCTURE

- Ghost mannequin: `images/ESM-campaign/studio-lookbook/[PRODUCT]/MK-[CODE].png`
- Studio shots: `images/ESM-campaign/studio-lookbook/[PRODUCT]/SL-[CODE]-[ANGLE].png`
- Detail crops: `reference/details/[PRODUCT]/[detail-name].png`
