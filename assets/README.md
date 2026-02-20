# Chess Coders Assets

This folder contains assets scraped from the current chesscoders.com website for use in the redesign project.

---

## 📁 Folder Structure

### `/logo` (2 files)
Chess Coders logo files
- `chesscoders-logo.png` (300x107px, 2.9KB)
- `chesscoders-logo-2.png` (300x107px, 3.2KB)

**Status:** ✅ Extracted
**Note:** Both appear to be the same logo. May need vector (SVG) version for better scaling.

---

### `/team` (20 files)
Team member photos from the team page
- 14 actual team members (per content)
- Additional files may be duplicates or placeholders
- Mix of PNG and JPG formats
- File sizes range from 1.3KB to 532KB

**Status:** ✅ Extracted
**Note:** Photos need to be matched to team member names:
1. Tiberiu - CEO
2. Victor - Chief Technical Officer
3. Bogdan - CEO
4. Mihai - Senior Fullstack Developer
5. Sebi - Mid-Level UI/UX Developer
6. Șerban - Mid-Level Project Manager
7. Alexandra - Mid-Level Fullstack Developer
8. Claudiu - Mid-Level Fullstack Developer
9. Artur - Mid-Level Fullstack Developer
10. Denisa - Junior Fullstack Developer
11. Robert - Junior Fullstack Developer
12. Mario - Junior Fullstack Developer
13. Gabi - Junior Designer
14. Alexandra - Junior Quality Assurance Engineer

**Action Needed:** Match photos to names and rename files accordingly (e.g., `team-tiberiu-georgescu.jpg`)

---

### `/projects` (21 files)
Project screenshots and showcase images
- Mix of desktop screenshots and project thumbnails
- File sizes range from 2.9KB to 1.4MB
- High-resolution images available (up to 2547x1919px)

**Status:** ✅ Extracted
**Note:** Projects need to be identified and labeled:
- File names are currently generic (project-01.png, etc.)
- Need to match to actual project names from portfolio
- Featured project: Superliga.ro (2024)

**Action Needed:** Match images to project names and create descriptions

---

### `/clients` (3 files)
Client/partner logos
- `client-01.png` (500x205px, 6.6KB)
- `client-02.png` (768x965px, 14KB)
- `client-03.png` (690x361px, 13KB)

**Status:** ⚠️ Partial
**Note:** Only 3 logos extracted. Website mentions clients in 6 countries and partnerships with global companies.

**Action Needed:** Need more client/partner logos from:
- Belgium, USA, Spain, Romania, UK, Ireland
- Partner companies mentioned on site

---

### `/misc` (45+ files)
Additional images scraped but not yet categorized
- Icons, UI elements, background images
- Various sizes and formats
- Includes the 3D chess piece visualization images
- Some may be decorative elements

**Status:** ✅ Available for review
**Note:** This folder contains all raw scraped images. Valuable assets should be moved to appropriate folders.

---

### `/partners` (0 files)
Partner logos folder - currently empty

**Status:** ❌ Not extracted
**Action Needed:** Extract partner logos from website

---

## 📊 Asset Inventory Summary

| Category | Expected | Extracted | Status |
|----------|----------|-----------|--------|
| Logo files | 1-2 | 2 | ✅ Complete |
| Team photos | 14 | 20 | ✅ Complete (needs mapping) |
| Project screenshots | 10-15 | 21 | ✅ Complete (needs labeling) |
| Client logos | 10+ | 3 | ⚠️ Partial |
| Partner logos | 5+ | 0 | ❌ Missing |
| 3D Chess pieces | 3 | 0 | ❌ Not on website |

---

## 🎯 Next Steps

### High Priority
1. **Map team photos to names** - Match each photo to the correct team member
2. **Identify projects** - Label project screenshots with actual project names
3. **Extract more client/partner logos** - Find logos from client companies

### Medium Priority
1. **Find or create SVG logo** - Current PNGs are low resolution
2. **Optimize images** - Compress large files while maintaining quality
3. **Create favicon set** - Generate from logo

### Low Priority
1. **Sort misc folder** - Categorize remaining images
2. **Extract background textures** - If needed for redesign
3. **Create WebP versions** - For better performance

---

## 🔗 Source

All assets extracted from: https://chesscoders.com
- Team page: /team
- Work/Portfolio: /work
- Home page: /
- Services pages: /services/*

**Extraction Date:** February 20, 2026

---

## 📝 Notes

- Image quality varies - some are high-res, others are thumbnails
- No 3D chess piece models found (these were likely custom-created for the site)
- Some images may be from Framer's built-in libraries
- Consider reaching out to Chess Coders for original high-quality assets
