# StoryMap Assets

This folder contains public assets for **The Future of Mobility** GIS StoryMap.

Assets are organized for use through GitHub Pages, allowing images and reference documents to be linked directly from ArcGIS StoryMaps or other web-based presentation tools.

## Public Asset Library

The public asset library is available at:

```text
https://ddecamerica.github.io/the-future-of-mobility/
```

## Folder Structure

```text
storymap-assets/
├── README.md
│
└── assets/
    ├── images/
    │   ├── cover/
    │   ├── logos/
    │   └── sections/
    │
    └── documents/
        └── guidance/
```

## Asset Categories

### `assets/images/cover/`

Hero and opening visuals for the StoryMap.

Current examples:

```text
future-mobility-cover-hero-01.png
future-mobility-cover-hero-02.png
```

### `assets/images/logos/`

DDEC logo files and project branding assets.

Current examples:

```text
ddec-logo-primary-black.png
ddec-logo-reverse-white.png
```

### `assets/images/sections/`

Section graphics, statistical cards, and visual storytelling assets.

Current examples:

```text
pbc-stat-new-residents-90k-01.png
pbc-stat-population-2030-163m-01.png
pbc-stat-visitors-fy2024-25-106m-01.png
pbc-stat-drive-alone-77pct-01.png
pbi-stat-passengers-85m-01.png
```

Mini versions may be used when a lighter or more compact version of a graphic is needed.

Example:

```text
pbc-stat-drive-alone-77pct-01-mini.png
```

### `assets/documents/guidance/`

PDF guidance documents and reference files for StoryMap production.

Current examples:

```text
future-mobility-storymap-guidance.pdf
future-mobility-storymap-guidance-optimized.pdf
```

## Public URL Patterns

Use this structure for image assets:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/[folder]/[filename]
```

Example:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/cover/future-mobility-cover-hero-01.png
```

Use this structure for document assets:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/documents/guidance/[filename]
```

Example:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/documents/guidance/future-mobility-storymap-guidance.pdf
```

## Naming Rules

Use simple, stable, web-safe file names.

Rules:

1. Use lowercase letters.
2. Use hyphens instead of spaces.
3. Avoid underscores, parentheses, accents, and special characters.
4. Keep names descriptive enough to understand the file purpose.
5. Use numbering when multiple versions or variations exist.
6. Use `mini` only for intentionally smaller or compact versions.
7. Do not rename or move assets after their URLs are used in the StoryMap.

Good:

```text
future-mobility-cover-hero-01.png
pbc-stat-drive-alone-77pct-01.png
pbc-stat-drive-alone-77pct-01-mini.png
ddec-logo-primary-black.png
future-mobility-storymap-guidance.pdf
```

Avoid:

```text
Future Mobility Cover Final.png
PBC Stat FINAL FINAL (2).png
DDEC Logo White Version New.png
The-Future-of-Mobility-Story-Map-Guidance.pdf
```

## Updating Assets

Once an asset URL has been added to the StoryMap, keep the file name and folder location unchanged.

For minor corrections, replace the existing file using the same file name.

For major revisions, create a new versioned file and update the StoryMap link intentionally.

Example:

```text
future-mobility-cover-hero-01.png
future-mobility-cover-hero-02.png
```

## Dynamic GIS Maps

Dynamic maps are expected to be managed directly inside the GIS/StoryMap environment.

Static map exports do not need to be stored here unless they are required as standalone images, backup visuals, or non-interactive graphics.
