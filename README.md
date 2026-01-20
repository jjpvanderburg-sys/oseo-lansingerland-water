# oseo-lansingerland-water
Demonstrator repository for OSEO.earth. This project explores satellite-based water detection and shoreline classification for the municipality of Lansingerland using Sentinel-2 data. The goal is to identify water bodies, shoreline zones, and assess potential for nature‑friendly banks using EO-derived indicators.
# OSEO — Lansingerland Water Detection & Shoreline Classification

**Repository for OSEO.earth demonstrator project.**  
This project focuses on water detection, shoreline identification, and bank classification using Sentinel-2 satellite data for the municipality of Lansingerland, the Netherlands.

## 🛰️ Objective

To build an end-to-end Earth Observation (EO) workflow that:

- Detects surface water using NDWI time series
- Identifies shoreline zones based on spatial transitions
- Classifies shorelines into three categories:
  1. Nature-friendly banks
  2. Non-nature-friendly and non-feasible
  3. Non-nature-friendly but potentially improvable

## 📍 Area of Interest

- **Location:** Municipality of Lansingerland, South Holland, Netherlands
- **Data Source:** Sentinel-2 imagery
- **AOI Format:** GeoJSON polygon (provided in `/data`)


## 🔧 Tools & Libraries

- `rasterio`, `geopandas`, `xarray`, `numpy`
- `matplotlib`, `seaborn`
- `earthpy`, `rioxarray`, `scikit-image`
- Optional: `openEO`, `Google Colab`, `QGIS`

## 📌 Project Status

This is an early-stage demonstrator.  
The goal is to validate the method on a single AOI before scaling.

## 📝 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) file for details.

---

Built with 💧, 🌍, and a touch of 🚀 by [OSEO.earth](https://oseo.earth)


## 📁 Repository Structure

