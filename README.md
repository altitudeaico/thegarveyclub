# The Garvey Club — Image Assets

Image assets for the Garvey Club website rebuild.

## Folder structure

```
/
├── rolling/    # Rolling banner images (currently 16 images)
└── gallery/    # Curated gallery images (to be added)
```

## Naming convention

Filenames preserve Mac's original numbering: `garvey-rolling-01.jpg` through `garvey-rolling-16.jpg`.

**Note on numbering:**
- Mac's original sequence skipped number 12 — there is no `garvey-rolling-12.jpg`. This is intentional, not a missing file.
- Mac sent two different images both numbered 5. Both are preserved: `garvey-rolling-05.jpg` and `garvey-rolling-05b.jpg`. Use 05b only if more images are needed; 05 takes priority.

## Image specs

All images have been processed for web use:

- **Format:** Progressive JPEG (HEIC originals converted)
- **Max dimensions:** 2400px on long edge (rolling), 1600px on long edge (gallery)
- **Target file size:** Under 300KB where quality permits (some larger source images sit at 300–370KB to preserve visual quality)
- **EXIF orientation:** Correctly applied — rotation handled at processing time
- **Colour space:** sRGB

## Usage notes for the site build

**Rolling banner:**
- Use images in numerical order — Mac's numbering reflects priority
- Drop highest numbers if fewer slots are needed (e.g. for 3 banner slots, use 01, 02, 03)
- `05b` is a duplicate-number resolution; use only as a fallback option

**Gallery:**
- Same priority rule — use lowest numbers first
- For a curated grid, equal aspect ratios are preferred — crop where needed for cohesion

## Direct image URLs

Once GitHub Pages is enabled (or via raw.githubusercontent.com), image URLs follow this pattern:

```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-01.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-01.jpg
```

## Source

Original images supplied by Mac (client) via Dropbox folders, April 2026. Processed and structured by Altitude AI Consulting.
