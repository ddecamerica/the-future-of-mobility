# The Future of Mobility

**Palm Beach County's Connected Mobility Network**

This repository is a comprehensive production toolkit for **The Future of Mobility**, a DDEC LLC GIS StoryMap prepared for the **2026 ULI West Palm Beach Forum**. It serves as the central hub for all StoryMap assets, production standards, and documentation.

The StoryMap presents a connected mobility vision for Palm Beach County, with an initial focus on the **Downtown West Palm Beach / Palm Beach International Airport Connector**—exploring infrastructure needs, community engagement, traffic safety, and regional economic opportunity.

## What's Included

This repository contains everything needed for professional StoryMap production:

### 📦 **Asset Library** (40+ Assets)
- **Cover Images**: Hero visuals and opening graphics for StoryMap introduction
- **Statistical Cards**: 18 data visualization cards with multiple design variations (full and mini versions)
  - Drive-alone commute rates (77%)
  - Population growth projections (163M by 2030)
  - Annual tourism (106M visitors)
  - New resident growth (90K)
  - PBI passenger volume (85M)
- **Branding**: DDEC logo files (primary black and reverse white)
- **Guidance Documents**: Production standards and reference materials

### 📋 **Production Standards**
- Naming conventions for consistent, stable URLs
- Visual system and typography guidelines
- Asset organization by category and purpose
- Contribution guidelines for team collaboration
- Asset inventory tracking and maintenance

### 🌐 **GitHub Pages Interface**
A professional web interface at [ddecamerica.github.io/the-future-of-mobility](https://ddecamerica.github.io/the-future-of-mobility) for browsing and copying asset links directly into ArcGIS StoryMaps.

### 📚 **Documentation**
- Asset categorization and usage
- URL patterns and link structure
- File naming best practices
- Versioning and update protocols
- Team contribution workflow

## Live Asset Library

The public asset library is available at:

```
https://ddecamerica.github.io/the-future-of-mobility/
```

Use this page to browse, search, and copy StoryMap-ready asset links.

## Repository Structure

```
the-future-of-mobility/
├── index.html                    # Interactive asset browser and production guide
├── README.md                     # This file
├── LICENSE
│
└── storymap-assets/
    ├── README.md                 # Asset library documentation
    ├── CONTRIBUTING.md           # Contribution guidelines
    ├── INVENTORY.md              # Asset inventory and tracking
    │
    └── assets/
        ├── images/
        │   ├── cover/            # Hero and opening visuals (2 images)
        │   ├── logos/            # DDEC branding (2 logos)
        │   └── sections/         # Statistics and data viz (36 images)
        │
        └── documents/
            └── guidance/         # Production guidance PDFs (2 documents)
```

## Asset Categories

### Cover Images
Hero and opening visuals for StoryMap introduction. Located in `assets/images/cover/`.

**Current**: 2 cover variants

### Statistical Graphics
Data visualization cards for key metrics across multiple design variations. Located in `assets/images/sections/`.

**Current**: 18 statistics with full and mini versions
- Drive-alone commute patterns (3 variants)
- Population projections (3 variants)
- Annual visitor volume (3 variants)
- New resident migration (3 variants)
- Airport passenger volume (3 variants)

### Logos
DDEC project branding marks. Located in `assets/images/logos/`.

**Current**: 2 logos (primary black and reverse white)

### Guidance Documents
StoryMap production standards and reference materials. Located in `assets/documents/guidance/`.

**Current**: 2 PDFs (full and optimized versions)

## Asset Link Format

Image assets use this URL structure:

```
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/[folder]/[filename]
```

Document assets use this URL structure:

```
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/documents/[folder]/[filename]
```

### Example Image Links

```
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/cover/future-mobility-cover-hero-01.png
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/sections/pbc-stat-drive-alone-77pct-01.png
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/logos/ddec-logo-primary-black.png
```

### Example Document Links

```
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/documents/guidance/future-mobility-storymap-guidance.pdf
```

## Production Standards

### Naming Convention

Use lowercase file names with hyphens for consistency and URL stability.

**Good examples:**
```
future-mobility-cover-hero-01.png
pbc-stat-drive-alone-77pct-01.png
pbc-stat-drive-alone-77pct-01-mini.png
ddec-logo-primary-black.png
future-mobility-storymap-guidance.pdf
```

**Avoid:**
```
Future Mobility Cover Final.png
Map FINAL FINAL (2).png
The-Future-of-Mobility-Story-Map-Guidance.pdf
```

### URL Stability

Once an asset URL has been added to the StoryMap production, keep the file name and folder location unchanged. For minor corrections, replace the file using the same name. For major revisions, create a new versioned file and update the StoryMap link intentionally.

### Visual System

The StoryMap uses **Noto Sans** as the primary typeface with a clear typographic hierarchy:

- **Noto Sans Bold**: Major section titles and hero headings
- **Noto Sans SemiBold**: Navigation, labels, and captions
- **Noto Sans Medium**: Body copy and narrative text

### Asset Quality Standards

| Category | Recommended Format | Max Size |
|----------|-------------------|----------|
| Cover | JPG, PNG | 2MB |
| Sections | JPG, PNG | 1.5MB |
| Maps | JPG, PNG | 2MB |
| Logos | PNG (transparent) | 500KB |

## Contributing

To add new assets to the library:

1. Follow the naming convention (lowercase, hyphens)
2. Place the file in the appropriate category folder
3. Update `storymap-assets/INVENTORY.md` with asset details
4. Submit changes via pull request or direct commit

See `storymap-assets/CONTRIBUTING.md` for detailed contribution guidelines.

## StoryMap Production Notes

Use GitHub Pages links when adding externally hosted media or reference files to ArcGIS StoryMaps. This ensures all StoryMap visuals are sourced from this stable, public repository.

Dynamic GIS maps are managed directly inside the GIS/StoryMap environment. Static map exports should only be added to this repository if they are needed as standalone images.

## Asset Inventory

Current inventory summary:

| Category | Count | Status |
|----------|-------|--------|
| Cover Images | 2 | ✅ Ready |
| Statistical Graphics | 36 | ✅ Ready |
| Logos | 2 | ✅ Ready |
| Guidance Documents | 2 | ✅ Ready |
| **TOTAL** | **42** | **✅ Ready** |

For detailed inventory with file sizes, resolution, and usage notes, see `storymap-assets/INVENTORY.md`.

## Project Context

**Project**: The Future of Mobility: Palm Beach County's Connected Mobility Network

**Focus Area**: Palm Beach International Airport to Downtown West Palm Beach Connector

**Prepared by**: DDEC LLC – Transportation Engineering & Mobility Advisory

**Forum**: 2026 ULI West Palm Beach Forum

**Topics**: Advanced Mobility Systems, Connected Transportation, Regional Economic Development, Transit-Oriented Connectivity

## Technology & Platforms

- **Repository**: GitHub with public GitHub Pages hosting
- **StoryMap Platform**: ArcGIS StoryMaps
- **Asset Formats**: PNG, JPG (images); PDF (documents)
- **Web Interface**: Interactive HTML asset browser
- **License**: GNU General Public License v3.0

## Maintained By

**DDEC LLC**
Transportation Engineering & Mobility Advisory
West Palm Beach, Florida

---

**Last Updated**: June 2026
**Total Assets**: 42 production-ready files
**Repository Size**: ~221 MB
**Status**: Active production use for 2026 ULI Forum StoryMap
