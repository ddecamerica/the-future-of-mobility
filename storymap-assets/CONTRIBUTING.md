# Contributing to Asset Library

This document provides guidelines for contributing assets to the PBI–Downtown APM Connector storymap asset library.

## 📋 Asset Guidelines

### File Naming Convention

Use clear, descriptive names with lowercase letters and hyphens:

```
[category]-[description]-[version].extension
```

**Examples:**
- `existing-conditions-01.jpg`
- `crash-analysis-map.jpg`
- `project-logo.png`

### File Format Requirements

| Category | Recommended Format | Max Size |
|----------|-------------------|----------|
| Cover | JPG, PNG | 2MB |
| Sections | JPG, PNG | 1.5MB |
| Maps | JPG, PNG | 2MB |
| Logos | PNG (for transparency) | 500KB |

### Image Quality Standards

- **Cover & Section Images:** Minimum 1920x1080px for web quality
- **Maps:** High resolution (2000x2000px minimum) for clarity
- **Logos:** Vector format preferred; if raster, use PNG with transparency

## 📤 Upload Process

### Via GitHub Web Interface

1. Navigate to the appropriate folder: `storymap-assets/assets/images/[category]/`
2. Click "Add file" → "Upload files"
3. Drag and drop your image(s)
4. Add commit message describing the upload
5. Commit to the `main` branch

### Via Git Command Line

```bash
# Clone the repository
git clone https://github.com/ddecamerica/the-future-of-mobility.git
cd the-future-of-mobility

# Navigate to the category folder
cd storymap-assets/assets/images/[category]

# Add your file
cp /path/to/your/image.jpg ./

# Commit and push
git add .
git commit -m "Add [description] to [category]"
git push origin main
```

## 🔍 Before Uploading

- [ ] File follows naming convention
- [ ] Image meets quality standards
- [ ] File size is within limits
- [ ] Correct category folder selected
- [ ] No duplicate files exist
- [ ] Copyright/licensing is clear

## 🔗 Accessing Your Asset

After uploading, your asset will be available at:

```
https://ddecamerica.github.io/the-future-of-mobility/storymap-assets/assets/images/[category]/[filename]
```

**Note:** GitHub Pages may take 1-2 minutes to update after pushing changes.

## 📝 Documentation Updates

After adding new assets, update `README.md` with:

1. Asset filename and location
2. Brief description
3. Any version information
4. Relevant usage notes

## 🚨 Issues or Questions?

- Review the [README.md](./README.md)
- Check existing assets for naming examples
- Refer to the [GitHub repository](https://github.com/ddecamerica/the-future-of-mobility)

---

**Last Updated:** June 3, 2026
