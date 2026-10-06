# Per-Image Generation Packets

These files are built for the workflow where **each image is generated in a separate ChatGPT thread**.

For each image:

1. Attach **both approved character references**: `seo-jun-reference.png` and `min-jae-reference.png`. These are mandatory identity locks.
2. Attach the story-image continuity reference specified by the packet:
   - Images **2–4**: immediately previous approved image.
   - Image **5**: no story-image continuity reference; start the flashback from the packet + character references.
   - Image **6**: approved **Image 4**.
   - Image **7**: approved **Image 5 only**.
   - Image **8**: approved **Image 6**.
   - Images **9–17**: immediately previous approved image.
3. Send the matching `IMAGE_XX_*.md` packet to the generation thread.
4. Ask: **"Generate this image exactly from the attached packet, required character references, and specified continuity image. Generate one image only."**
5. Approve the result before moving to the next numbered packet.

Do not generate a story image before both character references are approved. Follow the packet-specific continuity map exactly; do not attach a visually conflicting present-day image to a flashback packet or vice versa.

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

## Rendering Medium Lock

Every packet uses the same non-negotiable medium: **flat 2D Korean manhwa/webtoon cartoon illustration**. Do not generate realistic people, semi-realistic digital portraits, 3D/CGI characters, game-character renders, photographic skin, realistic pores, or volumetric 3D musculature. Use crisp drawn linework, flat color blocks, simplified illustrated skin planes, and cel/soft-cel shading.

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
