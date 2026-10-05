# After the Bell

A standalone short-form Boys' Love manhwa project designed for sequential AI image generation and TikTok-style vertical storytelling.

## Workflow

This repository is the source of truth for the story.

Read these files before generating images:

1. `01_CHARACTER_BIBLE.md` — permanent character appearance and personality rules.
2. `02_VISUAL_STYLE_GUIDE.md` — permanent visual and composition rules.
3. `03_STORY_AFTER_THE_BELL.md` — story beats, dialogue, and image-by-image instructions.

## Generation Commands

When this repository is available as context, follow these commands:

- **Start** or **Generate Image 1** — generate Image 1 only.
- **Next Image** — generate the next numbered image only.
- **Redo** — regenerate the current image without advancing.
- **Redo textless** — regenerate the current image with no speech bubbles or captions.
- **Next Image Textless** — advance one image and generate it without text.
- **Show current image number** — report the current scene number without advancing.

## Core Rules

- Generate only one image at a time unless explicitly asked otherwise.
- Never redesign the characters between images.
- Never change hair, facial structure, eye color, uniform design, body proportions, or height relationship unless instructed.
- Never rewrite the dialogue on your own.
- Maintain continuity with all previously generated images.
- Preserve props and wardrobe continuity.
- Use a vertical 9:16 composition.
- Keep important faces and text away from extreme top and bottom UI zones.
- Use the exact story beat for the current image.
- If a previous generated image establishes a small visual detail that does not conflict with the character bible or style guide, preserve it in subsequent images.

## Continuity Priority

When instructions conflict, follow this order:

1. Explicit instruction from the user in the current chat.
2. `01_CHARACTER_BIBLE.md`
3. `02_VISUAL_STYLE_GUIDE.md`
4. `03_STORY_AFTER_THE_BELL.md`
5. Visual continuity established by previously accepted images.

## Story

**Title:** After the Bell  
**Format:** Standalone one-shot  
**Genre:** Boys' Love / School Romance  
**Length:** 8 vertical images  
**Ending:** Complete; no sequel or episode cliffhanger required.
