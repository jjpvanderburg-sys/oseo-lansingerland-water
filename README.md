# OSEO — Lansingerland Water Detection & Shoreline Classification

**Repository for OSEO.earth demonstrator project**  
This project focuses on water detection, shoreline identification, and bank classification using Sentinel-2 satellite data for the municipality of Lansingerland, the Netherlands.

---

## 🛰️ Objective

To build an end-to-end Earth Observation (EO) workflow that:

- Detects surface water using NDWI time series
- Identifies shoreline zones based on spatial transitions
- Classifies shorelines into three categories:
  1. Nature-friendly banks
  2. Non-nature-friendly and non-feasible
  3. Non-nature-friendly but potentially improvable

---

## 📍 Area of Interest

- **Location:** Municipality of Lansingerland, South Holland, Netherlands
- **Data Source:** Sentinel-2 imagery
- **AOI Format:** GeoJSON polygon (provided in `/data` folder)

---

## 📁 Repository Structure
oseo-lansingerland-water/
├── data/ <- Input data (GeoJSON, TIFFs)
├── notebooks/ <- Jupyter or Colab notebooks
├── scripts/ <- Python utility scripts
├── results/ <- Output files (GeoTIFFs, maps, stats)
├── requirements.txt <- Python dependencies
├── LICENSE <- Open source license (MIT)
└── README.md <- This file


---

## 🔧 Tools & Libraries

This project uses a number of open-source Python packages, including:

- `rasterio`, `geopandas`, `xarray`, `numpy`
- `matplotlib`, `seaborn`
- `earthpy`, `rioxarray`, `scikit-image`
- (optional) `openEO`, `Google Colab`, `QGIS`

## 🧪 Installation

You can install the required packages using:

```bash
pip install -r requirements.txt

