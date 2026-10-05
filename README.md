# After the Bell

Standalone short-form Boys' Love manhwa project for sequential 9:16 image generation.

## Repository Structure

```
story-after-the-bell/
├── README.md
├── characters/
│   ├── HAN_SEO_JUN.md
│   └── YOO_MIN_JAE.md
├── style/
│   └── VISUAL_STYLE_GUIDE.md
├── story/
│   ├── SCRIPT.md
│   └── STORYBOARD.md
└── references/
    └── README.md
```

## Source-of-Truth Order

Before generating any story image, read:

1. `characters/HAN_SEO_JUN.md`
2. `characters/YOO_MIN_JAE.md`
3. `style/VISUAL_STYLE_GUIDE.md`
4. `story/SCRIPT.md`
5. `story/STORYBOARD.md`

Approved character reference images may be added later under `references/`. They are visual continuity aids only. No external manhwa inspiration image is stored in this repository.

## Commands

- **Start** or **Generate Image 1** — generate Image 1 only.
- **Next Image** — generate the next numbered image only.
- **Redo** — regenerate the current image without advancing.
- **Redo textless** — regenerate the current image without dialogue or captions.
- **Next Image Textless** — advance one image and generate it without text.
- **Show current image number** — report the current scene number only.

## Generation Rules

- Generate one story image at a time unless explicitly told otherwise.
- Never redesign a character between images.
- Preserve face, hair, body proportions, height relationship, uniform, and established props.
- Use the exact dialogue in `story/SCRIPT.md`.
- Use `story/STORYBOARD.md` for scene, camera, action, expression, and continuity.
- Use a vertical 9:16 composition.
- Keep critical faces and text away from extreme top/bottom TikTok UI zones.
- Maintain the time-of-day progression from late afternoon to early evening.
- Do not add a sequel hook or Part 2. This is a complete one-shot.

## Conflict Priority

1. Explicit instruction from the user in the current chat
2. Character files
3. Visual style guide
4. Script
5. Storyboard
6. Previously approved/generated image continuity

## Story

**Title:** After the Bell  
**Format:** Standalone one-shot  
**Genre:** Boys' Love / School Romance  
**Length:** 8 images  
**Ending:** Complete
