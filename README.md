# aus-forecast-districts

A public domain GeoJSON mapping project for Australia's official weather forecast districts, based on regional definitions by the Bureau of Meteorology (BoM).

## 🌏 Project Overview

The goal of this project is to provide a clean, open-source set of GeoJSON files delineating Australia's weather forecast districts — as defined and used by the Australian Bureau of Meteorology (BoM) for weather alerts, daily forecasts, and climate region mapping.

These forecast districts are essential for:
- Public weather visualizations
- Emergency alert systems
- Climate and environmental research
- Educational tools
- Community-led applications like early warning systems or geographic weather dashboards

## 🎯 Purpose and Motivation

Currently, there is no central, simple-to-use open GeoJSON dataset for these forecast districts. Many existing sources are fragmented, in outdated formats (e.g. DWG, SHP), or not web-ready.

This project addresses that gap by:
- Manually creating and verifying GeoJSON boundaries
- Prioritizing clarity and simplicity over file size or geometric complexity
- Making the data available under the MIT License for public reuse

## 📁 Project Structure

Each Australian state or territory will have its own folder and corresponding GeoJSON file(s):
/geojson/
├── VIC/
│   └── vic_forecast_districts.geojson
├── NSW/
│   └── nsw_forecast_districts.geojson
├── QLD/
├── WA/
├── SA/
├── NT/
├── TAS/
└── ACT/

## ✅ Progress Tracker

| State / Territory | Status         | Notes                         |
|-------------------|----------------|-------------------------------|
| VIC               | 🟢 In Progress  | Intergrating from Gov Data    |
| NSW               | 🟡 In Progress  | Manual GeoJSON drawing        |
| QLD               | ⚪ Not Started  |                               |
| WA                | ⚪ Not Started  |                               |
| SA                | ⚪ Not Started  |                               |
| NT                | ⚪ Not Started  |                               |
| TAS               | ⚪ Not Started  |                               |
| ACT               | ⚪ Not Started  |                               |

## 📜 License

This project is licensed under the **MIT License** — you are free to use, modify, and redistribute the data with attribution.

## ⚠️ Disclaimer

This project is **not affiliated with the Bureau of Meteorology (BoM)** or any Australian government agency.

All boundary data is created or derived by hand based on publicly accessible maps or documents. While best efforts are made to ensure accuracy, **the provided GeoJSON files are for visualization and non-critical applications only**.

For life-threatening emergencies, disaster warnings, or official weather alerts, always refer to:
👉 [bom.gov.au](https://www.bom.gov.au)

Use at your own discretion.

## 💬 Contact

Maintained by [Jack You](mailto:jackyou1314@gmail.com). Contributions, suggestions, and corrections are welcome via pull requests or issues.

---

