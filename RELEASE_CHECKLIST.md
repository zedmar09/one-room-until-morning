# Release Checklist — One Room Until Morning

Use this checklist before freezing the repository for image generation.

## Dialogue

- [ ] Every spoken line and narration in `story/STORYBOARD.md` matches `story/SCRIPT.md` exactly.
- [ ] No storyboard-only dialogue has been added.
- [ ] Image 11–17 dialogue order is unchanged and final.
- [ ] Scene 15 narration and Scene 17 final line match the script exactly.

## Rendering Medium

- [ ] Every reference and story packet explicitly requires **flat 2D Korean manhwa/webtoon cartoon rendering**.
- [ ] No file permits 3D/CGI, game-character rendering, photorealism, semi-realistic portrait painting, lifelike skin texture, pores, or photographic skin lighting.
- [ ] Anatomy remains stylized adult manhwa anatomy rather than realistic 3D anatomy.
- [ ] Skin, hair, clothing, and environments remain visibly illustrated with flat/cel or soft-cel treatment.

## Outfits

- [ ] Present-day outfits match both character files in every hotel image.
- [ ] Images 5 and 7 use the exact locked flashback outfits.
- [ ] Outer layers are worn in Images 1–3, hung near the entrance in Images 4–16, and worn again in Image 17.
- [ ] No new clothing, sleepwear, color changes, or accessory changes appear.

## Blocking

- [ ] Character height difference remains consistent: Min-jae taller than Seo-jun.
- [ ] Image 11 touch begins only after Seo-jun says **"...Yes."**
- [ ] Image 13: Min-jae stops at **"Don't."**; Seo-jun then lightly catches the front of Min-jae's black T-shirt.
- [ ] Image 14 remains pre-kiss; lips are still apart.
- [ ] Image 15: Min-jae leans in and pauses; Seo-jun closes the final distance.
- [ ] Image 16 contains no additional kissing or escalation.

## Props

- [ ] Min-jae's travel bag stays beside the luggage bench from Image 3 onward.
- [ ] Seo-jun's dark crossbody bag stays beside the chair near the window.
- [ ] The towel appears only in Image 11, is set on the luggage bench at the end, and is not held again.
- [ ] Phone appears as needed in Image 17; readable UI text is not required.
- [ ] Hotel room furniture and prop positions follow the locked room layout.

## Scene Timing

- [ ] Images 1–16 remain the same stormy night.
- [ ] Images 5 and 7 are the same rooftop flashback moment six months earlier.
- [ ] Min-jae is originally scheduled to leave the following morning for a six-month internship in Busan.
- [ ] Image 16 occurs immediately after the kiss.
- [ ] Image 17 occurs the following morning after the storm, with the train moved to that evening.

## File-to-File Consistency

- [ ] `characters/HAN_SEO_JUN.md` matches Seo-jun's storyboard appearance and actions.
- [ ] `characters/YOO_MIN_JAE.md` matches Min-jae's storyboard appearance, travel context, and actions.
- [ ] `style/VISUAL_STYLE_GUIDE.md` matches all outfit, prop, room-layout, consent, and blocking rules.
- [ ] `story/SCRIPT.md` remains the only source of spoken dialogue and narration.
- [ ] `story/STORYBOARD.md` remains the source for camera, action, continuity, and scene blocking.
- [ ] No unresolved `or`, optional outfit choice, alternate blocking, or temporary note remains in canonical files.

## Generation Packets

- [ ] All 17 files under `generation/IMAGE_01_*.md` through `generation/IMAGE_17_*.md` exist.
- [ ] Every packet's exact dialogue/caption matches `story/SCRIPT.md`.
- [ ] Every packet's events, blocking, camera, props, timing, and outfit state match `story/STORYBOARD.md` and the character files.
- [ ] Every packet embeds the project's critical visual-style locks and remains consistent with `style/VISUAL_STYLE_GUIDE.md`.
- [ ] Every packet requires both approved character reference images.
- [ ] Packet continuity references follow the locked map: Images 2–4 use the immediately previous image; Image 5 uses no story-image reference; Image 6 uses Image 4; Image 7 uses Image 5 only; Image 8 uses Image 6; Images 9–17 use the immediately previous image.
- [ ] No flashback packet is given a conflicting present-day continuity image, and no return-to-present packet is given a flashback image as its primary continuity lock.
- [ ] Image 3 does not visually advance into the Image 4 outerwear-removal state.
- [ ] Image 15 renders the narration as caption text only and never displays a `NARRATION` label.
- [ ] Any future canonical story/style change triggers re-audit or regeneration of the affected image packet(s).

## Freeze

- [ ] Both character reference images are approved before story Image 1 is generated.
- [ ] No story or continuity changes are made after freeze unless explicitly versioned.
- [ ] Repository is marked ready for sequential image generation.
