# Per-Image Generation Packets

These files are built for the workflow where **each image is generated in a separate ChatGPT thread**.

For each image:

1. Attach **both approved character references**: `seo-jun-reference.png` and `min-jae-reference.png`. These are mandatory identity locks.
2. For Images **2–17**, also attach the immediately previous approved story image as a continuity lock.
3. For **Image 7**, attach both approved **Image 6** and approved **Image 5**; Image 5 is required to preserve the exact rooftop flashback appearance and environment.
4. Send the matching `IMAGE_XX_*.md` packet to the generation thread.
5. Ask: **"Generate this image exactly from the attached packet, required character references, and continuity image(s). Generate one image only."**
6. Approve the result before moving to the next numbered packet.

Do not generate a story image before both character references are approved. Do not generate Images 2–17 without their required prior approved continuity image(s).

Each packet is intentionally self-contained and includes:
- required attachment instructions
- character appearance and outfit state
- scenario/location
- exact events and blocking
- objects and prop positions
- camera/composition
- exact script
- timing/continuity
- the critical visual-style locks needed to reproduce the full project look without separately sending the style guide
- hard generation constraints

## Files

- `IMAGE_01_LAST_ROOM.md` — Last Room
- `IMAGE_02_ELEVATOR.md` — Elevator
- `IMAGE_03_ONE_BED.md` — One Bed
- `IMAGE_04_SIX_MONTHS.md` — Six Months
- `IMAGE_05_FLASHBACK_ALMOST.md` — Flashback — Almost
- `IMAGE_06_THE_LAUGH.md` — The Laugh
- `IMAGE_07_FLASHBACK_MISUNDERSTANDING.md` — Flashback — Misunderstanding
- `IMAGE_08_WHAT_WE_THOUGHT.md` — What We Thought
- `IMAGE_09_TOMORROW.md` — Tomorrow
- `IMAGE_10_SOMETHING_HONEST.md` — Something Honest
- `IMAGE_11_STAY_STILL.md` — Stay Still
- `IMAGE_12_SAY_IT.md` — Say It
- `IMAGE_13_DONT.md` — Don't
- `IMAGE_14_TRY_ME.md` — Try Me
- `IMAGE_15_THE_KISS.md` — The Kiss
- `IMAGE_16_AFTER.md` — After
- `IMAGE_17_ONE_MORE_MORNING.md` — One More Morning

## Important

- `story/SCRIPT.md` remains the canonical master dialogue source.
- `story/STORYBOARD.md` remains the canonical master action/blocking source.
- These generation packets are image-specific portable copies designed for separate threads.
- The critical rendering locks from `style/VISUAL_STYLE_GUIDE.md` are embedded in every packet; the master style guide remains canonical if a packet is regenerated or audited.
- If the master story changes later, regenerate/re-audit the affected packet before using it.
- Do not store external inspiration artwork in this repository.
