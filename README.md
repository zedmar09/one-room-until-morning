# One Room Until Morning

A standalone short-form adult Boys' Love manhwa project designed for sequential 9:16 TikTok image generation.

## Repository Structure

```
one-room-until-morning/
├── README.md
├── RELEASE_CHECKLIST.md
├── characters/
│   ├── HAN_SEO_JUN.md
│   └── YOO_MIN_JAE.md
├── style/
│   └── VISUAL_STYLE_GUIDE.md
├── story/
│   ├── SCRIPT.md
│   └── STORYBOARD.md
├── generation/
│   ├── README.md
│   ├── IMAGE_01_LAST_ROOM.md
│   ├── IMAGE_02_ELEVATOR.md
│   ├── ...
│   └── IMAGE_17_ONE_MORE_MORNING.md
└── references/
    └── README.md
```

## Story Setup

Han Seo-jun and Yoo Min-jae are adult university students who stopped speaking after an almost-kiss six months ago. They both attend a small university farewell dinner for Min-jae before his six-month internship in Busan. On the way home, a severe storm suspends late transport and leaves them stranded near the station. The only nearby hotel has one room left—and one bed. Each believes the other regretted what happened six months earlier. Seo-jun already knows Min-jae's morning train time from the farewell plans, so the night has a real deadline.

**Title:** One Room Until Morning  
**Format:** Standalone one-shot  
**Genre:** Adult BL / Forced Proximity / Mutual Pining / One Bed / Emotional Tension  
**Length:** 17 vertical images  
**Ending:** Complete; no Part 2 or sequel hook required.

## Source-of-Truth Order

Before generating any story image, read:

1. `characters/HAN_SEO_JUN.md`
2. `characters/YOO_MIN_JAE.md`
3. `style/VISUAL_STYLE_GUIDE.md`
4. `story/SCRIPT.md`
5. `story/STORYBOARD.md`

Approved character reference images may be added later under `references/`. They are visual continuity aids only. No external manhwa inspiration artwork is stored in this repository.

## Per-Image Generation Packets

The `generation/` folder contains **17 standalone Markdown files, one for each final image**.

Each `IMAGE_XX_*.md` file is designed to be sent to a separate image-generation thread and includes the character state, outfit, scenario, events, blocking, objects/props, camera, exact script, continuity, style, and hard constraints needed for that image.

Recommended workflow:

1. Approve and attach the character reference images.
2. Open the matching file under `generation/`.
3. Send that single Markdown file to the image-generation thread.
4. Instruct the thread to generate only that image from the packet and attached references.
5. Approve the result before moving to the next numbered file.

See `generation/README.md` for the full handoff workflow.

## Commands

- **Start** or **Generate Image 1** — generate Image 1 only.
- **Next Image** — generate the next numbered image only.
- **Redo** — regenerate the current image without advancing.
- **Redo textless** — regenerate the current image without dialogue or captions.
- **Next Image Textless** — advance one image and generate it without text.
- **Show current image number** — report the current image number only.

## Generation Rules

- Generate one story image at a time unless explicitly told otherwise.
- Never redesign a character between images.
- Preserve face, hair, body proportions, height relationship, clothing, and established props.
- Use the exact dialogue in `story/SCRIPT.md`.
- Use `story/STORYBOARD.md` for camera, blocking, expressions, location, and continuity.
- Use a vertical 9:16 composition.
- Keep critical faces and dialogue away from extreme TikTok UI zones.
- Maintain the progression from stormy night to soft morning.
- The characters are adults: Seo-jun is 22 and Min-jae is 23.
- Intimacy must remain consensual and non-explicit.
- Do not add nudity or explicit sexual content.
- Do not add a sequel hook. This is a complete one-shot.

## Conflict Priority

1. Explicit instruction from the user in the current chat
2. Character files
3. Visual style guide
4. Script
5. Storyboard
6. Previously approved/generated image continuity
