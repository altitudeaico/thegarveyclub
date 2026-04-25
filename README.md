# The Garvey Club — Image Assets

Image assets for the Garvey Club website rebuild.

## Folder structure

```
/
├── brand/      # Logo and social meta images
├── rolling/    # 16 rolling banner images
└── gallery/    # 16 curated gallery images
```

### Brand folder

| File | Dimensions | Use |
|------|-----------|-----|
| `tgc-logo.jpg` | 1280×720 | Source logo file |
| `tgc-og-1200x630.jpg` | 1200×630 | Open Graph / Twitter card (Facebook, LinkedIn, Twitter, WhatsApp link previews) |
| `tgc-og-1200x1200.jpg` | 1200×1200 | Square version for platforms that prefer 1:1 (some LinkedIn placements, Instagram) |

**For social meta tags, use:**

```html
<meta property="og:image" content="https://altitudeaico.github.io/thegarveyclub/brand/tgc-og-1200x630.jpg" />
<meta property="og:image:width" content="1200" />
<meta property="og:image:height" content="630" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:image" content="https://altitudeaico.github.io/thegarveyclub/brand/tgc-og-1200x630.jpg" />
```

Note: the URL above assumes GitHub Pages is enabled. If using raw GitHub URLs or hosting from GHL media library, swap the URL accordingly.

## Naming convention

Filenames preserve Mac's original numbering: `garvey-rolling-01.jpg`, `garvey-gallery-01.jpg`, etc.

**Variants and quirks:**

**Rolling folder:**
- No image 12 — Mac's sequence skipped this number. Intentional, not missing.
- `05` and `05b` — Mac sent two different images both numbered 5. Both preserved; use `05` first, `05b` as fallback.

**Gallery folder:**
- `01a`, `04a`, `06b` — Mac used letter suffixes for variants of those images. Treat as alternates: use `01` over `01a`, `04` over `04a`, `06` over `06b`.

## Image specs

All images processed for web use:

- **Format:** Progressive JPEG (HEIC originals converted to JPEG)
- **Max dimensions:** 2400px long edge (rolling), 1600px long edge (gallery)
- **Target file size:** Under 300KB where quality permits
- **EXIF orientation:** Correctly applied at processing time
- **Colour space:** sRGB

A few rolling images (06, 09, 11, 14) sit slightly over 300KB to preserve visual quality on detailed source files. All gallery images are under or at 300KB.

## Usage notes for the site build

**Rolling banner:**
- Use images in numerical order — Mac's numbering reflects priority
- For 3 banner slots, use 01, 02, 03
- `05b` is a fallback option only

**Gallery:**
- Use lowest numbers first
- Variant suffixes (`a`, `b`) are alternate options — use the base number first
- For a curated grid layout, equal aspect ratios preferred — crop where needed for cohesion

## Direct image URLs

Images are available via raw GitHub URLs:

```
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/rolling/garvey-rolling-01.jpg
https://raw.githubusercontent.com/altitudeaico/thegarveyclub/main/gallery/garvey-gallery-01.jpg
```

For higher performance / production use, consider enabling GitHub Pages on this repo or moving assets into the GHL media library.

## Source

Original images supplied by Mac (client) via Dropbox folders, April 2026. Processed and structured by Altitude AI Consulting.
