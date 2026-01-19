# ESP32-S3-Box-3 Utilities Display

A dedicated **Home Assistant companion display** for real-time and monthly household utility usage, built on **ESPHome** for the **ESP32-S3-Box-3**.

This project replaces the voice assistant features of the Box-3 with a clean, **e-ink-inspired dashboard** designed for at-a-glance readability. It currently displays live and aggregated **electricity usage** from Home Assistant (Emporia) and is structured to easily add **gas and water meters** as they come online.

---

## ✨ Features

- ESP32-S3-Box-3 touch display (no voice assistant)
- E-ink / paper-style UI (grayscale, high contrast, minimal design)
- Live electric power usage (W / kW)
- Daily and monthly electric energy totals (kWh)
- Gas and water sections (placeholder / demo data)
- Touch input support for future interactions
- Native ESPHome + Home Assistant integration

---

## 📷 Screenshots

> Coming soon  
> (Add screenshots here once the layout is finalized)

---

## 🧰 Hardware

- **ESP32-S3-Box-3**
- Built-in:
  - 320×240 LCD
  - Capacitive touch (GT911)
  - Backlight control

No additional hardware is required for the display itself.

---

## 🏠 Home Assistant Requirements

### Electric (Emporia)
- `sensor.house_electric_meter_power_minute_average` (W)
- `sensor.house_electric_meter_energy_today` (kWh)
- `sensor.house_electric_meter_energy_this_month` (kWh)

Gas and water sensors will be added later and are currently simulated with demo values.

---

## 🚀 Installation

1. Clone the repository
2. Copy `secrets.example.yaml` to `secrets.yaml`
3. Add your Wi‑Fi credentials
4. Flash with ESPHome (USB or OTA)

---

## 🧪 Development Notes

- UI is rendered using a custom display lambda for maximum control
- Optimized for a paper / e‑ink aesthetic
- Gas and water values are currently placeholders
- Screen updates are event‑driven for performance

---

## 🗺 Roadmap

- Gas meter integration
- Water meter integration
- Optional true e‑paper display variant
- Layout and refresh configuration
- Screenshot documentation

---

## 📄 License

MIT License (recommended)

---

## 🙌 Credits

Built with ESPHome and Home Assistant.
