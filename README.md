# ESP32-S3 Utilities Display

This repository contains an ESPHome package for the **ESP32-S3-Box-3** that implements a clean, black-and-white utilities dashboard (Electricity, Gas, Water).

## Overview

The display shows:

### Top Row
- Indoor temperature (left)
- Outdoor temperature (right)
- HVAC state icon in the center  
  - 🔥 Heating  
  - ❄ Cooling  
  - Blank when idle

### Main Area
- Electricity (Now / Month)
- Gas (Now / Month)
- Water (Now / Month)

The UI is intentionally minimal and high-contrast, optimized for e‑ink–style readability.

## Hardware
- ESP32-S3-Box-3
- Built-in ILI9XXX display

## Software
- ESPHome 2025.x+
- Arduino framework
- Home Assistant (sensor source)

## Fonts

- **Text:** Google Fonts – Figtree
- **Icons:** Material Design Icons (MDI webfont)

> Icons are rendered from the MDI font TTF.  
> Text (including the degree symbol °) is rendered from standard Google Fonts.

## Icons Used

| Purpose | Icon | Codepoint |
|------|------|----------|
| Electricity | Flash | F140C |
| Gas / Heating | Flame | F0238 |
| Water | Water Drop | F0E0A |
| Cooling | Snowflake | F0717 |

## Design Goals
- Black & white only
- High contrast
- Readable at a distance
- Pixel-precise layout
- No voice or touch dependencies

## Status
Stable (v0.2.11)
