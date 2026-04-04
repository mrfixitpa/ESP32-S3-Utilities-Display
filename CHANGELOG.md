# Changelog

All notable changes to this project will be documented in this file.

---

## [0.3.0] - 2026-04-03

### Added
- Full touch-enabled home screen navigation
- Dedicated Electric detail page
- Dedicated Water detail page
- Dedicated Weather page
- Auto-return to home after idle timeout
- Pressed-state visual feedback for touch interactions

### Changed
- Promoted project from pre-release to stable `v0.3.0`
- Updated climate page UI/UX and touch behavior
- Added weather access from the outdoor temperature area
- Replaced planned electric graph approach with a cleaner power-today layout
- Standardized labels, spacing, fonts, and page structure across detail pages

### Electric Page
- Added live power display
- Added power today
- Added monthly power
- Added monthly cost
- Added automatic W / kW display switching for live power

### Water Page
- Added daily gallons display
- Added weekly gallons display
- Added monthly total display
- Added monthly cost display
- Matched layout and typography to the Electric page

### Weather Page
- Added weather condition text and icon
- Added outdoor temperature
- Added outdoor humidity
- Added wind conditions
- Shortened wind display format to values like `13 mph W`

### Improvements
- Improved touch responsiveness
- Improved page-to-page consistency
- Improved alignment and spacing throughout the UI
- Improved climate button hit areas and feedback
- Improved overall responsiveness by reducing unnecessary redraws from placeholder gas sensors

### Notes
- Gas data remains placeholder / dummy data
- Home screen, climate page, electric page, water page, and weather page are now part of the stable release

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
