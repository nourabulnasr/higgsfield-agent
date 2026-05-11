# ESM CAMPAIGN — REFERENCE BIBLE
> Ground truth for all prompt writing. Every prompt must be cross-checked against this file before it is shown for approval.  
> This file overrides the Shoot Bible on product specifics, character descriptions, and environment color.  
> Last updated: 2026-05-09 — built from direct analysis of character sheets, product photos, and beach reference.

---

## MALE CHARACTER
**Soul Character ID:** `4c9a7714-db4d-4cd0-84cb-295ddff5d01e`  
**Source:** Character sheet — "MAN / Confident Minimalist / Age 30s"

### Face
- Shape: Angular oval — strong square jawline, defined cheekbones, slightly prominent brow ridge
- Eyes: Dark brown, deep-set, calm and focused — not wide or expressive
- Nose: Defined, medium width, straight bridge
- Expression default: Composed, neutral, slightly serious — not smiling unless pose requires it

### Skin
- Tone: Medium warm olive — Egyptian Mediterranean. A light-to-medium brown with warm undertone, not pale, not dark. Think sun-touched but not deeply tanned.
- Texture: Naturally smooth with visible pores on cheeks and forehead — real skin, not plastic

### Hair
- Color: Dark brown, near-black
- Cut: Short, clean taper/fade on the sides, slightly longer and textured on top with natural wave. Clean hairline.
- No bleach, no colored highlights

### Beard
- Full, close-cropped, evenly trimmed dark beard covering jaw, chin, and upper lip fully
- Density: Thick and even — not patchy, not heavy/untrimmed
- This beard is a strong feature — always include it in prompts

### Build
- Medium-athletic. Broad shoulders, fit but not bulky. Natural proportions — no gym-exaggerated physique.
- Height impression: Tall, around 5'11"–6'1"

### Character drift — flag immediately if:
- Face is lighter/paler than described (character is NOT white or very light-skinned)
- Beard is missing, thin, or patchy
- Hair is long, curly afro, or bleached (the product photo FRONT.jpg model is NOT this character)
- Build looks teenage or very thin (the unwanted product models are NOT this character)

---

## FEMALE CHARACTER
**Soul Character ID:** `bb654e16-946c-4bd9-a051-6d36597ac210`  
**Source:** Character sheet — "WOMAN / Effortless Natural / Age 30s"

### Face
- Shape: Oval, softer than the male — rounded jawline, high but not sharp cheekbones
- Eyes: Warm brown, slightly almond-shaped, natural and expressive
- Nose: Medium, slightly defined
- Expression default: Warm, calm, natural — approachable without being commercial

### Skin
- Tone: Light-medium warm olive — slightly lighter than the male, Mediterranean sun-kissed beige. Natural imperfections welcome (slight freckles, pore visibility).

### Hair
- Color: Dark brown (not black, not highlighted)
- Style: Medium-long, falls past shoulders, slight natural wave/loose texture — NOT styled, NOT blowout-straight, NOT curly. It moves naturally and has volume at mid-length.
- Often loose and slightly tousled — never pinned up or severely styled

### Build
- Average-slim. Natural female proportions — not editorial-thin, not heavily curvy. Looks like a real woman in her 30s.
- Medium height

### Character drift — flag immediately if:
- Hair is pin-straight blowout or tightly curly (both wrong)
- Skin is very pale/northern European or very dark
- Face looks younger than 28 or older than 38
- Body is unrealistically proportioned

---

## PRODUCTS — GROUND TRUTH FROM PHOTOS

> The models in the product photos are NOT the campaign characters. Ignore their faces. Read garments only.

---

### M-FS — Full Olive Linen Set *(Unisex)*

**Color:** Muted sage-olive — desaturated olive green with a slight grey undertone. In natural light it reads as khaki-olive. NOT vivid green, NOT military green. More like the color of aged brass or dry Mediterranean shrubs.

**Fabric:** Heavily crinkled woven fabric — the crinkle is deep, random, and structural, not just surface texture. The fabric has a **slight satin sheen/luster** — it catches directional light and creates light-and-shadow variation across the surface. This is likely a linen-viscose blend or crinkled cupro, NOT flat matte linen. This sheen is a key visual characteristic.

**Shirt construction:**
- Short-sleeve camp collar shirt — collar is wide, flat, open lapel-style (no collar band, lies completely flat)
- 5 dark/near-black buttons down the center front placket
- Left chest patch pocket (small, square)
- Boxy-oversized cut, drop shoulder, very wide short sleeves
- Hemline hits at mid-hip
- No back graphic or print — clean back

**Shirt worn style:** Usually worn open with white crew-neck undershirt visible at the V-opening

**Pants construction:**
- EXTREMELY wide leg — palazzo-width. The leg opening is very wide, creating a flowing column of fabric. Not just "wide leg" — this is a dramatic, fashion-forward width.
- Floor-length (touches the ground on the model)
- Waistband with button/zipper closure (no drawstring visible)
- Belt loops present
- Fabric falls in heavy, fluid, vertical columns — very dramatic drape
- Same heavily crinkled sheen fabric as shirt

**Bible correction:** The Shoot Bible says "dark buttons" — CONFIRMED correct. Also says "natural crinkle texture in fabric" — CONFIRMED but undersells the sheen quality. Add sheen to all M-FS prompts.

---

### M-FSB — Full Beige Linen Set *(Unisex)*

**No product photos exist.** Build all prompts from M-FS reference with these color changes:

**Color:** Warm ivory/natural parchment — the color of unbleached linen, slightly warmer than pure white. Think: the inside of a linen napkin, or natural undyed cotton. NOT stark white, NOT cream-yellow. A very quiet, almost neutral warm tone.

**All construction details identical to M-FS** — same cut, same sheen fabric, same wide leg, same camp collar, same pocket placement. Only the color changes.

**Prompt rule:** Replace every olive/green/sage reference with: *warm ivory-parchment, unbleached linen tone*

---

### M-PO — Linen Polo Olive *(Male only)*

**Reinstated 2026-05-09:** This product exists. Same exact cut as M-PB (beige polo), different colorway.

**Color:** Muted sage-olive — exact same olive as M-FS shirt and trousers. Same desaturated olive-green with grey undertone.

**Fabric:** Same heavily crinkled slub fabric as M-FS/M-PB — viscose blend with subtle satin sheen and luster on raised crinkle ridges. NOT matte linen.

**Construction:** Identical to M-PB:
- PULLOVER BOXY SHIRT — not a full-button-front garment
- HALF PLACKET at center front from collar to mid-chest with 3 GOLD/BRASS rounded buttons
- Wide, flat, open collar — large camp/lapel-style, lies completely flat with no collar band
- Very wide, boxy short sleeves — almost kimono sleeve width
- Extremely oversized, box-shaped silhouette
- Left chest patch pocket (square, same as M-FS and M-PB)
- Short hemline hitting at hip
- Back: completely clean, no graphic

**Product accuracy gate:** Must say GOLD/BRASS buttons + camp collar + satin-sheen olive crinkle fabric. Never dark buttons, never polo-band collar.

---

### M-PB — Linen Polo Beige *(Male only)*

**Bible correction — significant:** The Shoot Bible describes "dark rounded buttons" — **THIS IS WRONG.** The actual buttons are **GOLD/BRASS colored, rounded, ornate-looking**. Correct all prompts.

**Color:** Warm ivory/parchment — nearly identical to M-FSB color, slightly warmer

**Fabric:** Same heavily crinkled sheen fabric as M-FS/M-FSB

**Construction:**
- This is a PULLOVER BOXY SHIRT — not a full-button-front garment. No buttons down the full front.
- HALF PLACKET at center front from collar to mid-chest only, with 3 GOLD/BRASS rounded buttons
- Wide, flat, open collar — a large camp/lapel-style collar, almost like exaggerated shirt lapels lying flat. NOT a traditional polo collar with a band.
- Very wide, boxy short sleeves — almost kimono sleeve width
- Extremely oversized, box-shaped silhouette — volume throughout
- Left chest patch pocket (square, same as M-FS)
- Short hemline hitting at hip
- Back: completely clean, no graphic, slight center back seam

**Key visual:** The exaggerated wide collar + half-placket with gold buttons is the most distinctive element. It gives the piece a casual-luxury feel, somewhere between a caftan and a short-sleeve shirt.

---

### U1 — White T-shirt *(Unisex)*

**Color:** Bright off-white cotton — very close to pure white, minimal warmth

**Fabric:** Heavy cotton, matte, opaque. Natural fabric creasing from wear.

**Cut:** Oversized boxy, drop shoulder, short sleeve, crew neck

**Front logo (exact):**
- "esm.studio" — small, charcoal/dark grey sans-serif font, centered on left chest area
- "originals" — directly below it, in salmon-coral red cursive/script font, approximately same width as "esm.studio" above
- Two-line stacked logo, subtle in scale — not a huge chest print

**Back graphic (exact — from BACK.jpg studio reference):**
- Centered on upper back, large and bold
- Top: Small black barcode printed just below the collar (between shoulder blades)
- Middle: "esm.studio" in large BLACK bold semi-italic sans-serif (stylized, slightly condensed)
- Bottom: "originals" in SALMON-CORAL-RED cursive/script font, larger in scale than the block text above it, sweeping from left to right and slightly beyond the width of "esm.studio", with a subtle red outline/shadow giving it depth
- The "originals" script overlaps slightly with the bottom of "esm.studio"

---

### U2 — Grey T-shirt *(Unisex)*

**Color:** Medium heather grey — mid-tone, neither light grey nor charcoal. Slight warmth.

**Fabric and cut:** Identical to U1

**Front logo:** Identical to U1 (same "esm.studio" + coral "originals" on left chest)

**Back graphic:** Identical layout to U1 — same barcode, same "esm.studio" bold black, same coral-red "originals" cursive sweep. The coral-red prints with slightly more visual contrast on the grey base.

---

### U3 — Quarter Zip Beige/Black *(Unisex)*

**Bible correction:** The Shoot Bible calls this a "summer knit fabric" — **WRONG.** This is a smooth woven fabric, NOT knit. It drapes and behaves like a lightweight woven cotton or poly-cotton blend.

**Color:** Warm sand/khaki-beige base with thin vertical black pinstripes. Stripes are very fine — approximately 2-3mm wide, spaced approximately 5-8mm apart. The overall impression reads as "beige with dark stripes" not "striped pattern."

**Construction:**
- FRONT ZIPPER: Center front zipper running from collar down to approximately mid-chest. Zipper pull visible.
- COLLAR: Wide, flat, pointed camp collar — large lapel-style, lies completely flat. NOT a traditional polo collar.
- Short sleeve, slightly fitted (more fitted than the linen pieces), hits at hip
- No chest pocket on this garment
- Back: Clean, same pinstripe fabric, no graphic

**Key visual:** The combination of wide flat camp collar + front zipper is distinctive and unusual. The stripes are fine enough that the garment reads as solid from a distance but shows texture up close.

---

### U4 — Quarter Zip White/Black *(Unisex)*

**Color:** White/off-white base with identical thin dark vertical pinstripes

**Construction and cut:** Identical to U3. Only difference is the base color (white vs beige).

---

### F-OC — Olive Chemise *(Female only)*

**Color:** Same sage-olive as M-FS — same fabric family, same crinkle sheen quality

**Construction:**
- Open button-front chemise/shirt — worn OPEN, not closed
- Camp collar, same wide flat style as M-FS shirt
- Short sleeve, boxy/oversized
- Worn over white bandeau/tube top (crop top visible underneath through open front)
- Hits approximately at hip

---

### F-OS — Olive Skirt *(Female only)*

**Bible correction — critical:** The Shoot Bible says "relaxed A-line drape" — **THIS IS WRONG.** The skirt is **STRAIGHT and close-fitting** through the hips and thighs, falling in a straight column to the floor. It is NOT A-line, NOT flowing, NOT full.

**Color:** Same sage-olive as F-OC chemise — matching set

**Construction:**
- Maxi length — floor-length, just touching the ground
- SIDE SLIT on one side reaching to approximately mid-calf
- Straight silhouette — fitted through hips, straight fall to floor
- Flat or elasticated waistband (no visible drawstring)
- Same crinkle sheen fabric as the chemise

**Key visual:** The pairing of a loose open chemise over a straight fitted maxi skirt creates an interesting silhouette contrast — volume on top, column on bottom. The side slit provides movement and ease.

---

### F-BG — Beige Full Set *(Female only)*

**Bible correction — major:** Multiple details are wrong in the Shoot Bible. Corrected here from photos.

**Color:** Warm ivory/natural parchment — same as M-PB and M-FSB, unbleached linen tone

**Top construction:**
- LONG SLEEVES — the Shoot Bible says "wide short sleeves" but the photos clearly show long, wide sleeves. The sleeves are long and have a batwing/kimono cut — very wide at the shoulder, tapering or staying wide to the wrist.
- Wide open V-neck or deeply open collar — no collar band
- Oversized/boxy silhouette with a gathered or drawstring element at the waist
- Very flowing and voluminous — creates a robe-like, draped silhouette

**Pants construction:**
- Wide-leg, relaxed fit
- **KEY FEATURE:** Multiple small knotted fabric tie-loops clustered along the **outer side seams** of the lower pants legs — visible on the outer side of each leg only, NOT around the full ankle hem. They create a gathered/bunched decorative effect running down the outer side of each leg near the hem. This is the most recognizable design detail of this product.
- Floor-length

**Prompt rule:** Always specify side-seam tie detail on F-BG. Say "outer side seams only" — never "around the full hem" or "ankle fringe." The side placement is what makes this correct.

---

### F-LB — Light Blue Full Set *(Female only)*

**Color:** Soft chambray-blue — medium-light, slightly desaturated blue with a hint of grey. Closer to French work-wear blue or washed chambray than to powder blue or sky blue. The fabric has a slight texture that catches light.

**Top construction:** Similar boxy, wide silhouette to F-BG. Wide open collar. Voluminous.

**Pants construction:**
- Same tie detail as F-BG — multiple small knotted fabric tie-loops along the **outer side seams** of the lower legs, visible on the outer side of each leg only, NOT around the full hem
- Wide-leg, relaxed
- Floor-length

**Bible note:** The Shoot Bible says "ribbon tie details at lower calf/ankle" — the placement is outer side seams only, not all around. Always prompt "outer side seams" specifically.

---

## BEACH ENVIRONMENT
**Source:** Aerial photo of North Coast Egypt / Sahel (Mediterranean coast, Marassi area or similar compound beach)

### Water
- Color: **Vivid bright turquoise** — genuinely electric-looking. This IS the authentic color of the Egyptian North Coast Mediterranean sea. Do not mute it to "teal-green." The real water earns its brightness.
- Transparency: High visibility into the shallows — the sand shows through in shallow areas, creating variation from bright turquoise at depth to pale aqua near shore
- Character: Calm, low waves lapping at shoreline, very shallow entry

**Bible revision:** The Shoot Bible says "turquoise water rendered as natural teal-green not electric blue." The reference photo shows the water IS genuinely vivid turquoise. The rule should be "vivid natural turquoise — authentic North Coast color, not artificially blue, not muted teal."

### Sand
- Color: Pale cream/off-white — very light, almost white in full sun. NOT golden or tan. This is fine, pale, bleached-looking Mediterranean sand.
- Texture: Fine grain, compacts slightly near waterline, dries quickly further up the beach

### Light Quality
- Mediterranean midday/late morning: High, bright, even
- White sand acts as a natural fill reflector — lifts shadows from below, reduces harsh under-eye shadows
- The combination of white sand + bright turquoise water creates a high-key, luminous environment

### Horizon
- Open, flat horizon — water meets a clear pale sky
- The location in reality has buildings behind the beach (white villas), but for generation purposes: **prompt for clean empty horizon, no structures**

### Environment summary for prompts
```
Fine pale cream-white sand beach, vivid natural turquoise Mediterranean 
water with gentle low waves, clear pale blue sky, open empty horizon 
where sea meets sky, no buildings or structures visible, raw and 
isolated coastal atmosphere
```

---

## CONSISTENCY RULES

### Before writing any prompt
1. Re-read the relevant product section above
2. Re-read the relevant character section above
3. If the bible says something different from the Shoot Bible — **this file wins**

### Product accuracy gates
- **M-PB buttons:** Must say GOLD/BRASS — never dark buttons
- **M-FS/M-FSB/M-PB fabric:** Must reference slight sheen/luster, not pure matte linen
- **F-OS skirt:** Must say STRAIGHT fitted column silhouette with side slit — never A-line
- **F-BG top:** Must say LONG sleeves — never short sleeves
- **F-BG and F-LB pants:** Must include the side-seam tie detail — "multiple knotted fabric ties along the outer side seams of the lower legs" — this is the key product identifier. Never say "around the full ankle hem."
- **U3/U4:** Must say woven fabric with front zipper and wide camp collar — not knit, not polo collar
- **T-shirt back prints:** Must reference barcode + bold "esm.studio" + coral-red "originals" script

### Character accuracy gates
- Male: Medium olive skin + full trimmed dark beard + short tapered dark hair — all three required
- Female: Light olive skin + dark brown medium-long natural wavy hair — both required
- If a generated image shows the wrong hair, skin, or missing beard: mark as character drift, do not use

### Environment accuracy gate
- Water must be vivid turquoise — if it renders as flat grey-blue or oversaturated cyan, flag it
- Sand must be pale cream/near-white — if it renders golden or tan, flag it
- No buildings, no umbrellas, no resort furniture

### Character IDs
- Male Soul ID: `4c9a7714-db4d-4cd0-84cb-295ddff5d01e`
- Female Soul ID: `bb654e16-946c-4bd9-a051-6d36597ac210`
- Always pass both IDs for couple shots
- If a solo male shot shows the wrong face: confirm Soul ID is set, then check prompt isn't overriding appearance

---

*This document is the product and character ground truth for the ESM Summer Campaign. Written from direct visual analysis of source materials. Supersedes the Shoot Bible on all product and character specifics.*
