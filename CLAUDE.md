# HIGGSFIELD AGENT — Project Rules


## Skill Loading Order — MANDATORY, NEVER SKIP

Run this sequence before any generation task:

1. Read `~/.claude/skills/NANOBANANA_BRAIN.md` — prompt engineering rules and four-layer method
2. Read `~/.claude/skills/HIGGSFIELD_BRAIN.md` — platform knowledge and pipeline logic
3. Read the relevant Seedance skill in `./skills/` for the task category
4. Read `~/.claude/skills/KLING_BRAIN.md` — only if doing video or animation
5. Use `/higgsfield:generate` or the Higgsfield CLI to execute

This order is mandatory. Brain files control creative quality. CLI skills handle execution only. Never skip the brain files.


## Tools Active in This Project

- Higgsfield CLI (primary — replaces browser automation)
- `/higgsfield:generate` skill for image generation
- Seedance 2.0 skills in `./skills/`
- Soul Character tool for consistent characters across a shoot


## Generation Workflow (CLI-Based)

Claude can select models programmatically:
- **Images**: Soul, Nano Banana Pro
- **Video**: Seedance, Kling 3.0, Veo 3.1

Jobs run async — submit and poll. No browser babysitting.
Images download directly to the project folder.

**Per-job steps:**
1. Read brain files (see Skill Loading Order above)
2. Build prompt using four-layer method (Subject, Light, Camera, Emotional Register)
3. Show prompt to user and wait for approval before generating
4. Submit job via `/higgsfield:generate` or CLI
5. Poll until complete, download to output folder
6. Review results with user — iterate one variable at a time


## Approval Gate — NEVER SKIP

Before executing any generation:
- Show the full prompt
- State the model, aspect ratio, and count
- Wait for explicit user approval

Do not generate speculatively. One confirmation per batch.


## Brief Structure

Extract all six elements from every brief before building a prompt:

1. **Brand** — name, tone, positioning
2. **Product** — what it is, what it does, key visual features
3. **Platform** — TikTok / Instagram Reels / YouTube Shorts / other
4. **Audience** — who sees this, what they care about
5. **Mood** — the emotional register of the campaign
6. **Reference feeling** — what the best reference image or video makes you feel


## Reference Image Analysis Protocol

When a reference image is provided, analyze it across six dimensions before building any prompt:

1. **Light** — source direction, quality (hard/soft), color temperature, falloff
2. **Color** — palette, saturation, contrast, dominant hues vs. accents
3. **Camera** — angle, crop, lens feel (wide/standard/telephoto), depth of field
4. **Subject treatment** — texture, skin condition, material, expression, age
5. **Composition** — negative space, weight distribution, framing logic
6. **Emotional register** — what feeling does this image carry? what has this scene been through?

Never skip this analysis. It is how a reference becomes a prompt, not just a mood board.


## Output Organization

- Images: `./images/YYYY-MM-DD/[brand]-[shot-description]-[number].png`
- Videos: `./videos/YYYY-MM-DD/[brand]-[shot-description]-[number].mp4`
- Briefs: `./briefs/YYYY-MM-DD/[brand]-brief.md`

Always create the date folder before saving. Never mix dates or brands in the same folder.


## Memory Update — End of Every Session

Before closing, update `~/.claude/memory/general.md` with:
- What brand or project was worked on
- Which prompts performed best (copy the exact text)
- Aesthetic discoveries made this session
- What to try or avoid next time

This is not optional. Memory is how quality compounds across sessions.
