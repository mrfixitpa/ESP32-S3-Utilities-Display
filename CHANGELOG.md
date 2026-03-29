# Changelog

All notable changes to this project will be documented in this file.

---

## [0.2.13] - 2026-03-29

### Changed
- Replaced live water flow (GPM) with daily usage
- Water card now displays:
  - Day (gal)
  - Week (gal)
  - Month (gal)

### Improvements
- Fixed layout overflow issue on Water card
- Improved spacing and alignment within existing pill design
- Maintains clean, readable layout without increasing card size

### Notes
- Electricity and Gas sections unchanged
- No changes to fonts, icons, or display structure

---

## [0.2.12] - 2026-03-29

### Added
- Weekly water usage display on Water card

### Changed
- Replaced dummy water sensors with real Home Assistant entities
- Water card now displays:
  - Current flow rate (GPM)
  - Weekly usage (gallons)
  - Monthly usage (gallons)

### Notes
- No changes to layout, spacing, fonts, or other utility cards
- Electricity and Gas sections remain unchanged

---

## [0.2.11] - Previous Release

### Changed
- Adjusted Outdoor temperature label spacing for visual alignment with Indoor
- Minor layout refinement only

## v0.2.11
- Fine-tuned Outdoor label spacing (+4px)
- Finalized symmetric top-row alignment

## v0.2.10
- Fixed Outdoor label / temperature overlap
- Added explicit spacing gap to mirror Indoor layout

## v0.2.9
- Reworked top-row alignment using mirrored anchors
- Improved Indoor vs Outdoor symmetry

## v0.2.8
- Fixed MDI font download issue (invalid unpkg version)
- Switched to verified MDI font release

## v0.2.7
- Removed invalid glyphs from MDI font
- Ensured degree symbol renders only from text fonts

## v0.2.6
- First stable utilities dashboard
- Electricity, Gas, Water pill cards
- HVAC icon logic added
