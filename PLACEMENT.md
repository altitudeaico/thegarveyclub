# The Garvey Club — Image Placement Manifest

**Last updated:** 25 April 2026 — revised after Mac's feedback round 1
**Status:** Active — supersedes earlier placement guidance

This manifest tells the developer (and Cowork) exactly which images go in which sections of thegarveyclub.com. All images already exist in this repo — no new images need to be uploaded. This document maps section → filenames.

---

## 1. Top carousel (above-fold rolling banner)

**Section on site:** Rolling banner immediately under hero ("Empower. Elevate. Excel.")

**Mac's feedback:** Mix portrait and landscape — include people-at-the-table images so visitors who don't scroll still see them. Specifically include `garvey-rolling-05.jpg`.

**Images to use (in this order):**

| Order | Filename | Orientation | Notes |
|-------|----------|-------------|-------|
| 1 | `rolling/garvey-rolling-05.jpg` | Portrait | Mac specifically requested this in top carousel |
| 2 | `rolling/garvey-rolling-09.jpg` | Landscape | People-at-table shot, fills carousel cleanly |
| 3 | `rolling/garvey-rolling-07.jpg` | Portrait | Mac requested |
| 4 | `rolling/garvey-rolling-08.jpg` | Portrait | Mac requested |
| 5 | `rolling/garvey-rolling-01.jpg` | Portrait | Original carousel image |
| 6 | `rolling/garvey-rolling-02.jpg` | Portrait | Original carousel image |

**Direct URLs:**

```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-05.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-09.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-07.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-08.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-01.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-02.jpg
```

**Display note:** Most images are portrait (1800×2400). For a horizontal carousel slot, expect to use `object-fit: cover` with sensible focal point, or design the carousel to accommodate portrait orientation. The single landscape (09) will display fully without cropping.

---

## 2. Bottom carousel (lower rolling banner)

**Section on site:** Rolling banner placed lower on page (originally between Values and Membership).

**Mac's feedback:** Mix it up here too with people-at-the-table shots.

**Images to use (in this order):**

| Order | Filename | Orientation | Notes |
|-------|----------|-------------|-------|
| 1 | `rolling/garvey-rolling-03.jpg` | Portrait | |
| 2 | `rolling/garvey-rolling-04.jpg` | Portrait | |
| 3 | `rolling/garvey-rolling-06.jpg` | Portrait | |
| 4 | `rolling/garvey-rolling-10.jpg` | (verify) | Likely landscape — people shot |
| 5 | `rolling/garvey-rolling-11.jpg` | (verify) | Likely landscape |
| 6 | `rolling/garvey-rolling-13.jpg` | (verify) | |

**Direct URLs:**

```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-03.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-04.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-06.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-10.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-11.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-13.jpg
```

---

## 3. "Proximity is Power" section — Three landscape pictures

**Section on site:** The "Why The Garvey Club? — Because proximity is power" section.

**Mac's feedback:** Replace the picture gallery layout here with **three landscape pictures** that show the whole group.

**This replaces the previous gallery grid in this location.**

**Images to use (in this order, left to right):**

| Order | Filename | Dimensions | Notes |
|-------|----------|------------|-------|
| 1 | `gallery/garvey-gallery-01a.jpg` | 1080×620 landscape | Mac specifically requested |
| 2 | `gallery/garvey-gallery-03.jpg` | 1600×972 landscape | Mac specifically requested |
| 3 | `gallery/garvey-gallery-07.jpg` | 1600×1200 landscape | Mac specifically requested |

**Direct URLs:**

```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-01a.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-03.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-07.jpg
```

**Layout instruction:** Three images displayed side-by-side as a 3-column row on desktop, stacking on mobile. Equal heights, full width. Each image should display the whole group — no cropping that hides faces. `object-fit: cover` with `object-position: center` is sensible default.

---

## 4. Image gallery (further down page)

**Section on site:** The remaining gallery section (was previously a larger grid; check current site for exact location after the "Proximity is Power" change above).

**Images to use:** Lowest-numbered gallery images not already used in "Proximity is Power."

| Filename | Notes |
|----------|-------|
| `gallery/garvey-gallery-01.jpg` | |
| `gallery/garvey-gallery-02.jpg` | |
| `gallery/garvey-gallery-04.jpg` | |
| `gallery/garvey-gallery-05.jpg` | |
| `gallery/garvey-gallery-06.jpg` | |
| `gallery/garvey-gallery-08.jpg` | |
| `gallery/garvey-gallery-09.jpg` | |
| `gallery/garvey-gallery-10.jpg` | |
| `gallery/garvey-gallery-11.jpg` | |
| `gallery/garvey-gallery-12.jpg` | |

**Direct URLs:**

```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-01.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-02.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-04.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-05.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-06.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-08.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-09.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-10.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-11.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-12.jpg
```

---

## 5. "Why Join The Garvey Club?" feature image

**Section on site:** Membership section — single portrait-orientation image beside membership criteria text.

**Image:**

```
gallery/garvey-gallery-13.jpg
```

**Direct URL:**

```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-13.jpg
```

---

## 6. Brand / social meta

| Use | File |
|-----|------|
| Site logo | `brand/tgc-logo.jpg` |
| Open Graph (Facebook, LinkedIn, Twitter, WhatsApp link previews) | `brand/tgc-og-1200x630.jpg` |
| Square social (Instagram, some LinkedIn) | `brand/tgc-og-1200x1200.jpg` |

---

## Summary of unused images

These are available as buffer/swap options but not currently mapped to a section:

- `rolling/garvey-rolling-05b.jpg` — duplicate-number alternate
- `rolling/garvey-rolling-14.jpg`, `15.jpg`, `16.jpg` — verify orientation, may be useful
- `gallery/garvey-gallery-04a.jpg`, `06b.jpg` — variant alternates

If any of the mapped images don't visually fit a section, swap from this list rather than re-cropping.

---

## Notes for Cowork / developer

**This manifest is the source of truth.** If it conflicts with anything in the earlier placement brief or the README, this manifest wins. It reflects Mac's feedback round 1 (received 25 April 2026).

**Do not rename or move files in the repo.** The URLs in this manifest reference exact filenames that are now stable.

**Production hosting:** Same recommendation as before — these GitHub raw URLs are fine for staging and reference, but final production should serve images from the GHL media library. When that migration happens, only the URL prefix changes; filenames stay identical.
