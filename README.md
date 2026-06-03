# The Future of Mobility

**Palm Beach County’s Connected Mobility Network**

This repository supports **The Future of Mobility**, a DDEC LLC GIS StoryMap prepared for the **2026 ULI West Palm Beach Forum**.

The StoryMap presents a connected mobility vision for Palm Beach County, with an initial focus on the **Downtown West Palm Beach / Palm Beach International Airport Connector**. The repository is used to host public-facing visual assets, reference documents, and project branding through GitHub Pages.

## Live Asset Library

The public asset library is available at:

```text
https://ddecamerica.github.io/the-future-of-mobility/
```

Use this page to browse and copy StoryMap-ready asset links.

## Purpose

This repository provides a stable public location for assets used in the StoryMap, including:

* Cover visuals
* Statistical graphics
* DDEC logo files
* StoryMap guidance documents
* Public links for externally hosted media

The goal is to keep all StoryMap support files organized, easy to reference, and stable throughout production.

## Repository Structure

```text
the-future-of-mobility/
│
├── index.html
├── README.md
├── LICENSE
│
└── storymap-assets/
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

## Asset Link Format

Image assets use this URL structure:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/[folder]/[filename]
```

Document assets use this URL structure:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/documents/[folder]/[filename]
```

Example image link:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/cover/future-mobility-cover-hero-01.png
```

Example document link:

```text
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/documents/guidance/future-mobility-storymap-guidance.pdf
```

## StoryMap Production Notes

Use GitHub Pages links when adding externally hosted media or reference files to ArcGIS StoryMaps.

Once an asset URL has been added to the StoryMap, keep the file name and folder location unchanged. For minor corrections, replace the file using the same name. For major revisions, create a versioned file and update the StoryMap link intentionally.

Dynamic GIS maps are managed directly inside the GIS/StoryMap environment. Static map exports should only be added to this repository if they are needed as standalone images.

## Naming Convention

Use lowercase file names with hyphens.

Good examples:

```text
future-mobility-cover-hero-01.png
pbc-stat-drive-alone-77pct-01.png
ddec-logo-primary-black.png
future-mobility-storymap-guidance.pdf
```

Avoid:

```text
Future Mobility Cover Final.png
Map FINAL FINAL (2).png
The-Future-of-Mobility-Story-Map-Guidance.pdf
```

## Maintained By

**DDEC LLC**
Transportation Engineering & Mobility Advisory
West Palm Beach, Florida
