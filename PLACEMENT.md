# The Garvey Club — Image Placement Manifest

**Last updated:** 25 April 2026 — revised after Mac's feedback round 2 (Loom video)
**Status:** Active — supersedes all earlier placement guidance

This manifest tells the developer (and Cowork) exactly which images go in which sections of thegarveyclub.com. All images already exist in this repo. This document maps section → filenames.

---

## Section A — Top scrolling carousel (above-fold)

**Position 1 (first image, fixed by Mac):**
- `rolling/garvey-rolling-01.jpg`

**Position 2 (second image, fixed by Mac):**
- `rolling/garvey-rolling-04.jpg` (image of Claudine)

**Positions 3+:**
Existing carousel images previously used here, EXCLUDING `08.jpg` and `09.jpg` (which have been moved to the bottom rolling section). Most likely candidates:
- `rolling/garvey-rolling-05.jpg`
- `rolling/garvey-rolling-07.jpg`
- `rolling/garvey-rolling-02.jpg`
- `rolling/garvey-rolling-03.jpg`
- `rolling/garvey-rolling-06.jpg`

**Removed from this section:**
- `rolling/garvey-rolling-08.jpg` — moved to Section B
- `rolling/garvey-rolling-09.jpg` — moved to Section B

---

## Section B — Bottom rolling section

**Images:**
- `rolling/garvey-rolling-08.jpg`
- `rolling/garvey-rolling-09.jpg`

(Order between the two not specified by Mac — `08` then `09` recommended as default.)

This is a separate scrolling/rolling element from the top carousel. Mac explicitly distinguishes the two in his feedback.

---

## Section C — Gallery grid (3 × 2 on desktop)

### Top row

| Position | Filename | Content |
|---|---|---|
| 1 | `gallery/garvey-gallery-01a.jpg` | Group shot |
| 2 | `gallery/garvey-gallery-03.jpg` | Table layout |
| 3 | `gallery/garvey-gallery-07.jpg` | Table layout |

### Bottom row (newly added in this round)

| Position | Filename | Content |
|---|---|---|
| 1 | `gallery/garvey-gallery-01.jpg` | Long table — full dinner with TGC screen |
| 2 | `gallery/garvey-gallery-06b.jpg` | Round-table mastermind, ~5 people |
| 3 | `gallery/garvey-gallery-02.jpg` | B&W long table, wider angle |

**Visual flow (Mac's intent):** group → table → table → long table → short group → long table

**Layout:** 3-column × 2-row grid on desktop. Stack to 2 columns on tablet, single column on mobile.

---

## Section D — Brand / social meta (unchanged from prior version)

| Use | File |
|---|---|
| Site logo | `brand/tgc-logo.jpg` |
| Open Graph (Facebook, LinkedIn, Twitter, WhatsApp link previews) | `brand/tgc-og-1200x630.jpg` |
| Square social (Instagram, some LinkedIn) | `brand/tgc-og-1200x1200.jpg` |

---

## Direct URLs reference

### Top carousel
```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-01.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-04.jpg
```

### Bottom rolling
```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-08.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-09.jpg
```

### Gallery grid (top row)
```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-01a.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-03.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-07.jpg
```

### Gallery grid (bottom row)
```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-01.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-06b.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-02.jpg
```

---

## Unused images (available as buffer)

These are in the repo but not assigned to a section in this round:

**Rolling:** `garvey-rolling-05b.jpg`, `garvey-rolling-10.jpg`, `garvey-rolling-11.jpg`, `garvey-rolling-13.jpg`, `garvey-rolling-14.jpg`, `garvey-rolling-15.jpg`, `garvey-rolling-16.jpg`

**Gallery:** `garvey-gallery-04.jpg`, `garvey-gallery-04a.jpg`, `garvey-gallery-05.jpg`, `garvey-gallery-06.jpg`, `garvey-gallery-08.jpg`, `garvey-gallery-09.jpg`, `garvey-gallery-10.jpg`, `garvey-gallery-11.jpg`, `garvey-gallery-12.jpg`, `garvey-gallery-13.jpg`

---

## Notes for Cowork / developer

- This manifest is the source of truth. Conflicts with earlier briefs resolve in favour of this document.
- Do not rename or move files in the repo — URLs in this manifest reference exact filenames that are now stable.
- All images already exist in the repo. No new uploads required.
- Production hosting recommendation: when ready, migrate from GitHub raw to GHL media library. Filenames stay identical; only the URL prefix changes.
